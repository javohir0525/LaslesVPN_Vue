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
          <i
            class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11"
            v-html="feather.icons.user.toSvg()"
          ></i>
          <div class="flex flex-col">
            <span class="text-2xl font-bold text-[#0B132A]">90+</span>
            <span class="text-xl text-[#4F5665]">Users</span>
          </div>
        </div>
        <hr class="border h-32 border-[#EEEFF2]" />
        <div class="flex items-center">
          <i
            class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11"
            v-html="feather.icons.map.toSvg()"
          ></i>
          <div class="flex flex-col">
            <span class="text-2xl font-bold text-[#0B132A]">30+</span>
            <span class="text-xl text-[#4F5665]">Locations</span>
          </div>
        </div>
        <hr class="border h-32 border-[#EEEFF2]" />
        <div class="flex items-center">
          <i
            class="text-[#F53838] bg-[#FFECEC] p-4 rounded-full mr-11"
            v-html="feather.icons.server.toSvg()"
          ></i>
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
        <img class="max-w-[508px]" src="./images/preference.png" alt="" />
        <div class="max-w-[420px]">
          <h3 class="text-[#0B132A] text-4xl font-medium mb-5">
            We Provide Many Features You Can Use
          </h3>
          <p class="text-[#4F5665] text-base mb-5">
            You can explore the features that we provide with fun and have their
            own functions each feature.
          </p>
          <ul class="space-y-2">
            <li class="flex mt-4 gap-2.5">
              <i
                class="bg-green-600 text-white rounded-xl"
                v-html="feather.icons['check-circle'].toSvg()"
              ></i
              ><span>Powerfull online protection.</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i
                class="bg-green-600 text-white rounded-xl"
                v-html="feather.icons['check-circle'].toSvg()"
              ></i
              ><span>Internet without borders.</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i
                class="bg-green-600 text-white rounded-xl"
                v-html="feather.icons['check-circle'].toSvg()"
              ></i
              ><span>Supercharged VPN</span>
            </li>
          </ul>
          <ul>
            <li class="flex mt-4 gap-2.5">
              <i
                class="bg-green-600 text-white rounded-xl"
                v-html="feather.icons['check-circle'].toSvg()"
              ></i
              ><span>No specific time limits.</span>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <!-- Plan -->
    <section class="mt-52">
      <div class="flex flex-col text-center items-center">
        <h2 class="text-[#0B132A] text-4xl font-medium">Choose Your Plan</h2>
        <p class="text-base text-[#4F5665] w-[520px] mt-5">
          Let's choose the package that is best for you and explore it happily
          and cheerfully.
        </p>
      </div>
      <!-- article 1 -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-5 mt-20">
        <article
          class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl flex flex-col"
        >
          <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box" />
          <span class="text-lg font-medium text-[#0B132A]">Free Plan</span>
          <ul class="mb-10">
            <li class="flex gap-6 mb-2.5 mt-7">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Unlimited Bandwitch</span>
            </li>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Encrypted Connection</span>
            </li>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>No Traffic Logs</span>
            </li>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Works on All Devices</span>
            </li>
          </ul>
          <div class="flex flex-col mt-auto">
            <span class="text-2xl font-medium text-[#0B132A] mb-5">Free</span>
            <button
              class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition"
            >
              Select
            </button>
          </div>
        </article>
        <!-- article 2 -->
        <article
          class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl flex flex-col"
        >
          <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box" />
          <span class="text-lg font-medium text-[#0B132A]">Premium Plan</span>
          <ul>
            <li class="flex gap-6 mb-2.5 mt-7">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Unlimited Bandwitch</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Encrypted Connection</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>No Traffic Logs</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Works on All Devices</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Connect Anyware</span>
            </li>
          </ul>
          <div class="flex flex-col mt-32">
            <span class="text-2xl font-medium text-[#0B132A] mb-5"
              >$9 <span class="text-[#4F5665]">/ mo</span></span
            >
            <button
              class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition"
            >
              Select
            </button>
          </div>
        </article>
        <!-- article 3 -->
        <article
          class="px-24 py-16 text-center border-2 border-[#DDDDDD] rounded-xl flex flex-col"
        >
          <img class="max-h-40 mb-7 mx-auto" src="./images/Box.png" alt="Box" />
          <span class="text-lg font-medium text-[#0B132A]">Premium Plan</span>
          <ul>
            <li class="flex gap-6 mb-2.5 mt-7">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Unlimited Bandwitch</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Encrypted Connection</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>No Traffic Logs</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Works on All Devices</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Connect Anyware</span>
            </li>
          </ul>
          <ul>
            <li class="flex gap-6 mb-2.5">
              <i class="text-green-600" v-html="feather.icons.check.toSvg()"></i
              ><span>Get New Features</span>
            </li>
          </ul>
          <div class="flex flex-col mt-32">
            <span class="text-2xl font-medium text-[#0B132A] mb-5"
              >$12 <span class="text-[#4F5665]">/ mo</span></span
            >
            <button
              class="text-[#F53838] px-14 py-2 border-2 border-[#F53838] rounded-full cursor-pointer hover:bg-[#F53855] hover:text-white transition"
            >
              Select
            </button>
          </div>
        </article>
      </div>
    </section>
    <!-- Map -->
    <section>
      <div class="flex flex-col text-center items-center mt-36">
        <h2
          class="text-4xl text-[#0B132A] font-medium mb-5 w-[380px] leading-12"
        >
          Huge Global Network of Fast VPN
        </h2>
        <p class="text-base text-[#4F5665] mb-40 w-[500px] leading-7">
          See
          <span class="text-[#4F5665] font-medium">LaslesVPN</span> everywhere
          to make it easier for you when you move locations.
        </p>
      </div>
      <div class="flex justify-center items-center">
        <img class="max-w-5xl" src="./images/world.png" alt="World" />
      </div>
      <div class="flex justify-center items-center mt-16">
        <img src="./images/companiesLogo.png" alt="CompaniesLogo" />
      </div>
    </section>
    <section>
      <div class="flex flex-col text-center items-center mt-32">
        <h3
          class="text-4xl text-[#0B132A] font-medium mb-5 w-[400px] leading-12"
        >
          Trusted by Thousands of Happy Customer
        </h3>
        <p class="text-base text-[#4F5665] w-[500px] leading-7">
          These are the stories of our customers who have joined us with great
          pleasure when using this crazy feature.
        </p>
      </div>
    </section>
    <!-- Customers -->
    <section>
      <div class="mt-24 flex relative overflow-hidden gap-12">
        <div
          class="absolute top-0 right-0 w-44 h-full bg-gradient-to-l from-white to-transparent"
        />
        <!-- article 1 -->
        <article
          class="border-2 border-[#DDDDDD] transition hover:border-[#F53838] rounded-xl shadow-md p-5 max-w-lg shrink-0"
        >
          <div class="flex items-center space-x-3">
            <img
              class="w-12 object-cover mr-5"
              src="./images/Users/user1.png"
              alt="User"
            />
            <div>
              <p class="text-xl text-[#0B132A] font-medium leading-7">
                Viezh Robert
              </p>
              <p class="text-sm text-[#4F5665] leading-7">Warsaw, Poland</p>
            </div>
            <div class="flex items-center gap-2 ml-auto">
              <p class="text-base text-[#0B132A] leading-7">4.5</p>
              <i class="text-amber-400" v-html="feather.icons.star.toSvg()"></i>
            </div>
          </div>
          <p class="text-base text-[#0B132A] mt-5 max-w-md">
            “Wow... I am very happy to use this VPN, it turned out to be more
            than my expectations and so far there have been no problems.
            LaslesVPN always the best”.
          </p>
        </article>
        <!-- article 2 -->
        <article
          class="border-2 border-[#DDDDDD] transition hover:border-[#F53838] rounded-xl shadow-md p-5 max-w-lg shrink-0"
        >
          <div class="flex items-center space-x-3">
            <img
              class="w-12 object-cover mr-5"
              src="./images/Users/user2.png"
              alt="User"
            />
            <div>
              <p class="text-xl text-[#0B132A] font-medium leading-7">
                Yessica Christy
              </p>
              <p class="text-sm text-[#4F5665] leading-7">Shanxi, China</p>
            </div>
            <div class="flex items-center gap-2 ml-auto">
              <p class="text-base text-[#0B132A] leading-7">4.5</p>
              <i class="text-amber-400" v-html="feather.icons.star.toSvg()"></i>
            </div>
          </div>
          <p class="text-base text-[#0B132A] mt-5 max-w-md">
            “I like it because I like to travel far and still can connect with
            high speed.”.
          </p>
        </article>
        <!-- article 3 -->
        <article
          class="border-2 border-[#DDDDDD] transition hover:border-[#F53838] rounded-xl shadow-md p-5 max-w-lg shrink-0"
        >
          <div class="flex items-center space-x-3">
            <img
              class="w-12 object-cover mr-5"
              src="./images/Users/user3.png"
              alt="User"
            />
            <div>
              <p class="text-xl text-[#0B132A] font-medium leading-7">
                Kim Young Jou
              </p>
              <p class="text-sm text-[#4F5665] leading-7">Seoul, South Korea</p>
            </div>
            <div class="flex items-center gap-2 ml-auto">
              <p class="text-base text-[#0B132A] leading-7">4.5</p>
              <i class="text-amber-400" v-html="feather.icons.star.toSvg()"></i>
            </div>
          </div>
          <p class="text-base text-[#0B132A] mt-5 max-w-md">
            “This is very unusual for my business that currently requires a
            virtual private network that has high security.”.
          </p>
        </article>
      </div>
      <div class="flex space-x-1 mt-22 justify-between">
        <div class="items-center">
          <button
            class="min-w-9 rounded-full bg-[#F53838] py-2 px-3 border border-transparent text-center text-sm text-white transition-all shadow-md hover:shadow-lg focus:bg-[#F53838] focus:shadow-none active:bg-[#F53838] hover:bg-red-600 active:shadow-none disabled:pointer-events-none disabled:opacity-50 disabled:shadow-none ml-2 cursor-pointer"
          ></button>
          <button
            class="max-w-2 rounded-full border border-slate-300 py-2 px-3 text-center text-sm transition-all shadow-sm hover:shadow-lg text-slate-600 hover:text-white hover:bg-slate-300 hover:border-slate-300 focus:text-white focus:bg-slate-300 focus:border-slate-300 active:border-slate-300 active:text-white active:bg-slate-400 disabled:pointer-events-none disabled:opacity-50 disabled:shadow-none ml-2 cursor-pointer"
          ></button>
          <button
            class="max-w-2 rounded-full border border-slate-300 py-2 px-3 text-center text-sm transition-all shadow-sm hover:shadow-lg text-slate-600 hover:text-white hover:bg-slate-300 hover:border-slate-300 focus:text-white focus:bg-slate-300 focus:border-slate-300 active:border-slate-300 active:text-white active:bg-slate-400 disabled:pointer-events-none disabled:opacity-50 disabled:shadow-none ml-2 cursor-pointer"
          ></button>
          <button
            class="max-w-2 rounded-full border border-slate-300 py-2 px-3 text-center text-sm transition-all shadow-sm hover:shadow-lg text-slate-600 hover:text-white hover:bg-slate-300 hover:border-slate-300 focus:text-white focus:bg-slate-300 focus:border-slate-300 active:border-slate-300 active:text-white active:bg-slate-400 disabled:pointer-events-none disabled:opacity-50 disabled:shadow-none ml-2 cursor-pointer"
          ></button>
        </div>
        <div class="flex items-center gap-5">
          <button
            class="w-full p-2 border-2 border-[#F53838] rounded-full cursor-pointer text-[#F53838] hover:shadow-md hover:bg-[#F53838] hover:text-white transition"
          >
            <i v-html="feather.icons['arrow-left'].toSvg()"></i>
          </button>
          <button
            class="w-full p-2 border-2 border-[#F53838] rounded-full cursor-pointer text-[#F53838] hover:shadow-md hover:bg-[#F53838] hover:text-white transition"
          >
            <i v-html="feather.icons['arrow-right'].toSvg()"></i>
          </button>
        </div>
      </div>
    </section>
    <!-- Subscribe -->
    <div class="flex justify-center w-full mt-16">
      <div class="flex shadow-lg p-12 rounded-xl">
        <div class="space-x-96">
          <h2
            class="text-4xl text-[#0B132A] font-medium max-w-[350px] leading-11"
          >
            Subscribe Now for Get Special Features!
          </h2>
          <p class="text-base text-[#4F5665] leading-7 mt-5">
            Let's subscribe with us and find the fun.
          </p>
        </div>
        <div class="flex items-center">
          <button
            class="px-10 py-4 rounded-xl text-white font-bold shadow-[#F53838] bg-[#F53838] cursor-pointer hover:bg-red-600 transition"
          >
            Subscribe Now
          </button>
        </div>
      </div>
    </div>
  </main>
  <!-- footer -->
  <footer class="p-9 container mx-auto">
    <div class="flex justify-between">
      <div class="mr-60">
        <img class="max-h-9 mb-5" src="./images/Logo.png" alt="Logo" />
        <p class="mb-8 max-w-[300px] text-base text-[#4F5665]">
          <span class="font-medium">LaslesVPN</span> is a private virtual
          network that has unique features and has high security.
        </p>
        <div class="flex gap-5 mb-8">
          <a class="text-[#F53838] p-3 shadow-lg rounded-full" href="#!"
            ><i v-html="feather.icons.facebook.toSvg()"></i
          ></a>
          <a class="text-[#F53838] p-3 shadow-lg rounded-full" href="#!"
            ><i v-html="feather.icons.twitter.toSvg()"></i
          ></a>
          <a class="text-[#F53838] p-3 shadow-lg rounded-full" href="#!"
            ><i v-html="feather.icons.instagram.toSvg()"></i
          ></a>
        </div>
        <span class="text-base text-[#AFB5C0]"
          >©2020Lasles<span class="text-base text-[#AFB5C0] font-medium"
            >VPN</span
          ></span
        >
      </div>
      <!-- Products -->
      <div>
        <span class="text-xl text-[#0B132A] font-medium leading-7"
          >Product</span
        >
        <nav>
          <ul class="space-y-2 text-base text-[#4F5665] leading-7">
            <li class="mt-5"><a href="#!">Download</a></li>
            <li><a href="#!">Pricing</a></li>
            <li><a href="#!">Locations</a></li>
            <li><a href="#!">Server</a></li>
            <li><a href="#!">Countries</a></li>
            <li><a href="#!">Blog</a></li>
          </ul>
        </nav>
      </div>
      <!-- Engage -->
      <div class="ml-36">
        <span class="text-xl text-[#0B132A] font-medium leading-7">Engage</span>
        <nav>
          <ul class="space-y-2 text-base text-[#4F5665] leading-7">
            <li class="mt-5"><a href="#!">LaslesVPN ? </a></li>
            <li><a href="#!">FAQ</a></li>
            <li><a href="#!">Tutorials</a></li>
            <li><a href="#!">About Us</a></li>
            <li><a href="#!">Privacy Policy</a></li>
            <li><a href="#!">Terms of Service</a></li>
          </ul>
        </nav>
      </div>
      <!-- Earn money -->
      <div class="ml-30">
        <span class="text-xl text-[#0B132A] font-medium leading-7"
          >Earn money</span
        >
        <nav>
          <ul class="space-y-2 text-base text-[#4F5665] leading-7">
            <li class="mt-5"><a href="#!">Affiliate</a></li>
            <li><a href="#!">Become Partner</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</template>

<script>
import feather from "feather-icons";

export default {
  data() {
    return { feather };
  },
};
</script>
