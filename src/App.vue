<template>
  <header
    class="p-8 flex items-center justify-between font-Rubik container mx-auto"
  >
    <img class="max-w-[149px]" src="./images/Logo.png" alt="Logo" />
    <nav>
      <ul class="flex gap-10 text-[#4F5665] text-base">
        <a href="#!"><li>About</li></a>
        <a href="#!"><li>Features</li></a>
        <a href="#!"><li>Pricing</li></a>
        <a href="#!"><li>Testimonials</li></a>
        <a href="#!"><li>Help</li></a>
      </ul>
    </nav>
    <div>
      <a class="mr-7 text-[#0B132A] font-medium text-base" href="#!">Sign In</a>
      <a
        class="px-11 py-3 border-[#F53855] border-2 rounded-4xl text-[#F53855] text-base font-medium hover:bg-[#F53855] hover:text-white transition"
        href="#!"
        >Sing Up</a
      >
    </div>
  </header>
  <!-- hero section -->
  <main class="p-8 mt-24 container mx-auto">
    <section>
      <div class="flex justify-between">
        <div class="max-w-[580px]">
          <h1
            class="text-[#0B132A] text-6xl leading-16 font-Rubik font-medium mb-5"
          >
            Want anything to be easy with
            <span class="font-bold">LaslesVPN.</span>
          </h1>
          <p class="text-base text-[#4F5665] mb-12">
            Provide a network for all your needs with ease and fun using
            LaslesVPN discover interesting features from us.
          </p>
          <button
            class="font-bold px-16 py-4 bg-[#F53838] text-white rounded-xl hover:bg-red-600 transition cursor-pointer"
          >
            Get Started
          </button>
        </div>
        <img class="max-h-96" src="./images/heroImg.png" alt="heroImg" />
      </div>
    </section>
    <!-- ULS information -->
    <section class="mt-32">
      <div class="px-24 py-20 flex justify-between rounded-xl shadow-md">
        <div class="flex items-center">
          <i class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11" v-html="feather.icons.user.toSvg()"></i>
          <div class="flex flex-col">
            <span class="text-2xl font-bold text-[#0B132A]">90+</span>
            <span class="text-xl text-[#4F5665]">Users</span>
          </div>
        </div>
        <hr class="border h-32 border-[#EEEFF2]">
        <div class="flex items-center">
          <i class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11" v-html="feather.icons.map.toSvg()"></i>
          <div class="flex flex-col">
            <span class="text-2xl font-bold text-[#0B132A]">30+</span>
            <span class="text-xl text-[#4F5665]">Locations</span>
          </div>
        </div>
        <hr class="border h-32 border-[#EEEFF2]">
        <div class="flex items-center">
          <i class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11" v-html="feather.icons.server.toSvg()"></i>
          <div class="flex flex-col">
            <span class="text-2xl font-bold text-[#0B132A]">50+</span>
            <span class="text-xl text-[#4F5665]">Servers</span>
          </div>
        </div>
      </div>
    </section>
    <!-- preference -->
    <section class="mt-28">
      <div class="flex justify-around items-center">
        <img class="max-w-[508px]" src="./images/preference.png" alt="">
        <div class="max-w-[420px]">
          <h3 class="text-[#0B132A] text-4xl font-medium mb-5">We Provide Many Features You Can Use</h3>
          <p class="text-[#4F5665] text-base mb-5">You can explore the features that we provide with fun and have their own functions each feature.</p>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i class="bg-green-600 text-white rounded-xl" v-html="feather.icons['check-circle'].toSvg()"></i><span>Powerfull online protection.</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i class="bg-green-600 text-white rounded-xl" v-html="feather.icons['check-circle'].toSvg()"></i><span>Internet without borders.</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i class="bg-green-600 text-white rounded-xl" v-html="feather.icons['check-circle'].toSvg()"></i><span>Supercharged VPN</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i class="bg-green-600 text-white rounded-xl" v-html="feather.icons['check-circle'].toSvg()"></i><span>No specific time limits.</span>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <!-- Plan -->
    <section class="mt-52">
      <div class="flex flex-col text-center">
        <h2 class="text-[#0B132A] text-4xl font-medium">Choose Your Plan</h2>  
        <p class="text-base text-[#4F5665] mt-5">Let's choose the package that is best for you and explore it happily and cheerfully.</p>
      </div>
      <!-- article 1 -->
       <div class="flex items-center justify-around mt-16">
         <article class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl">
           <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box">
           <span class="text-lg font-medium text-[#0B132A]">Free Plan</span>
           <ul>
             <li class="flex gap-6 mb-2.5 mt-7">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Unlimited Bandwitch</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Encrypted Connection</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>No Traffic Logs</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Works on All Devices</span>
             </li>
           </ul>
           <div class="flex flex-col mt-32">
             <span class="text-2xl font-medium text-[#0B132A] mb-5">Free</span>
             <button class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition">Select</button>
           </div>
         </article>
         <!-- article 2 -->
         <article class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl">
           <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box">
           <span class="text-lg font-medium text-[#0B132A]">Premium Plan</span>
           <ul>
             <li class="flex gap-6 mb-2.5 mt-7">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Unlimited Bandwitch</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Encrypted Connection</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>No Traffic Logs</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Works on All Devices</span>
             </li>
           </ul>
           <div class="flex flex-col mt-32">
             <span class="text-2xl font-medium text-[#0B132A] mb-5">$9 <span class="text-[#4F5665]">/ mo</span></span>
             <button class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition">Select</button>
           </div>
         </article>
         <!-- article 3 -->
         <article class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl">
           <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box">
           <span class="text-lg font-medium text-[#0B132A]">Premium Plan</span>
           <ul>
             <li class="flex gap-6 mb-2.5 mt-7">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Unlimited Bandwitch</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Encrypted Connection</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>No Traffic Logs</span>
             </li>
           </ul>
           <ul>
             <li class="flex gap-6 mb-2.5">
               <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i><span>Works on All Devices</span>
             </li>
           </ul>
           <div class="flex flex-col mt-32">
             <span class="text-2xl font-medium text-[#0B132A] mb-5">$12 <span class="text-[#4F5665]">/ mo</span></span>
             <button class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition">Select</button>
           </div>
         </article>
       </div>
    </section>
  </main>
</template>

<script>
import feather from "feather-icons";

export default {
  data() {
    return { feather };
  },
};
</script>
