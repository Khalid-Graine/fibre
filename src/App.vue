<template>
  <!-- parent -->
  <div class="font-poppins">
    <!-- header -->
    <header class="bg-first pb-2">
      <div class="container flex flex-wrap items-center justify-between p-1">
        <div class="ordero-1 w-14">
          <img src="./assets/img/logo.png" alt="" />
        </div>
        <ul
          class="order-3 mt-3 flex w-full justify-evenly gap-3 border-t border-gray-300 p-2 sm:order-2 sm:mt-0 sm:w-fit sm:border-none"
        >
          <li class="hover:effect">Community</li>
          <li class="hover:effect">Pricing</li>
          <li class="hover:effect">Features</li>
        </ul>
        <div class="order-2 flex sm:order-3">
          <button class="mr-2">Sign In</button>
          <button
            class="rounded-md bg-theblue p-1 px-2 text-white hover:opacity-70"
          >
            Sign up
          </button>
        </div>
      </div>
    </header>

    <div class="hidden h-[0.5px] bg-gray-300 sm:flex"></div>

    <!-- home -->
    <div class="bg-first pb-16 pt-5">
      <div
        class="container flex flex-col sm:flex-row sm:items-center sm:justify-center"
      >
        <div class="w-12/12 mx-auto sm:order-2 sm:w-11/12">
          <img src="./assets/img/hero-Illustration.png" alt="" class="" />
        </div>
        <div class="mt-2 flex flex-col gap-4 sm:order-1">
          <div class="hidden gap-1 sm:flex">
            <img src="./assets/img/star.svg" alt="" />
            <img src="./assets/img/star.svg" alt="" />
            <img src="./assets/img/star.svg" alt="" />
            <img src="./assets/img/star.svg" alt="" />
            <img src="./assets/img/star.svg" alt="" />
            <p class="ml-2">Rated 4.8/5 (248 reviews)</p>
          </div>

          <h2 class="text-5xl font-extrabold">
            Create Your portoflio in minutes
          </h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis
            illum deserunt labore aut molestiae explicabo deleniti porro
            doloribus autem rem.
          </p>

          <div
            class="flex flex-col items-stretch font-extrabold sm:flex-row sm:items-center"
          >
            <button
              class="mr-2 rounded-md bg-theblue px-3 py-1 text-white hover:opacity-70"
            >
              Start free trial
            </button>
            <button
              class="mr-2 rounded-md bg-transparent px-3 py-1 text-theblue hover:opacity-70"
            >
              view examples
            </button>
          </div>

          <div class="flex flex-col gap-4 sm:flex-row">
            <div class="flex gap-2">
              <img src="./assets/img/Checkmark.svg" alt="" />
              <p>No Credit card Required</p>
            </div>
            <div class="flex gap-2">
              <img src="./assets/img/Checkmark.svg" alt="" />
              <p>free templates</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- why fiber -->
    <div class="my-10 bg-white">
      <div class="container">
        <p class="my-4 font-bold text-theblue">Why Fiber ?</p>
        <p class="text-2xl font-bold">
          A good portfolio means good employability.
        </p>
        <div class="mt-12 flex flex-col gap-8 sm:flex-row">
          <div>
            <img src="./assets/img/time.svg" alt="" />
            <h3 class="my-2 font-bold">Build in minutes</h3>
            <p>
              With a selection of premade templates, you can build out of
              portfolio in less than 10 minutes.
            </p>
          </div>
          <div class="">
            <img src="./assets/img/code.svg" alt="" />
            <h3 class="my-2 font-bold">Add custom CSS</h3>
            <p>
              Customize your personal portfolio even more with the ability to
              add your own custom CSS styles.
            </p>
          </div>
          <div>
            <img src="./assets/img/allSizes.svg" alt="" />
            <h3 class="my-2 flex font-bold">Responsive</h3>
            <p>
              All Fiber templates are fully responsive to ensure the experience
              is seemless across all devices.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- free trial -->
    <div class="my-10 bg-white">
      <div
        class="container grid items-center gap-4 rounded-xl bg-blue-800 px-4 pb-0 pt-4 sm:grid-cols-12"
      >
        <div class="col-span-5 text-white">
          <h3 class="text-4xl font-bold">Diversify your portfolio.</h3>
          <p class="my-2">
            Create an even more impressive portfolio by creating case studies
            for your projects. Simply follow our step-by-step guide.
          </p>
          <button
            class="my-1 rounded-md bg-white px-4 py-2 text-theblue hover:opacity-90"
          >
            Start Free Trial
          </button>
        </div>
        <div class="col-span-7">
          <img src="./assets/img/PageImage.png" alt="" />
        </div>
      </div>
    </div>

    <!-- reviews -->
    <div class="my-10 bg-white">
      <div class="container flex flex-col gap-2 sm:flex-row">
        <div class="card">
          <div class="flex gap-2">
            <img class="" src="./assets/img/UserAvatar.svg" alt="" />
            <div class="">
              <p class="font-semibold text-theblue">sarah</p>
              <p>$100k in revenue</p>
            </div>
          </div>
          <p>
            Setting up my portfolio with Fiber took no more thna 10 minutes.
            Since then, my portfolio has attracted a lot of clients and made me
            more than $100k.
          </p>
          <div
            class="rounded-md border border-[#ddd] p-2 text-center text-theblue"
          >
            view sarah portfolio
          </div>
        </div>
        <div class="card">
          <div class="flex gap-2">
            <img class="" src="./assets/img/Usermatt.svg" alt="" />
            <div class="">
              <p class="font-semibold text-theblue">Mathew Higgins</p>
              <p>$20k in revenue</p>
            </div>
          </div>
          <p>
            I have been getting A LOT of leads ever since I used Fiber's premade
            templates, now I just need to work on my case studies and I'll be
            ready to go!
          </p>
          <div
            class="rounded-md border border-[#ddd] p-2 text-center text-theblue"
          >
            view Mathew's portfolio
          </div>
        </div>
        <div class="card">
          <div class="flex gap-2">
            <img class="" src="./assets/img/userjann.svg" alt="" />
            <div class="">
              <p class="font-semibold text-theblue">Janice Dave</p>
              <p>$30k in revenue</p>
            </div>
          </div>
          <p>
            I only just started freelancing this yet have already made more than
            I ever did in my full-time job. The templates are so amazing.
          </p>
          <div
            class="rounded-md border border-[#ddd] p-2 text-center text-theblue"
          >
            view Janice's portfolio
          </div>
        </div>
      </div>
    </div>

    <footer class="bg-first py-10">
      <div class="container flex flex-col gap-6 sm:flex-row sm:gap-10">
        <ul class="flex flex-col gap-2">
          <li class="text-lg font-semibold">Fiber</li>
          <li>
            With Fiber, you can setup your own personal portfolio in minutes
            with dozens of premade, beautiful templates.
          </li>
          <li>Made with ♥ in Venezuela</li>
        </ul>
        <ul class="flex flex-col gap-2">
          <li class="text-lg font-semibold">informations</li>
          <li class="hover:effect">Pricing</li>
          <li class="hover:effect">Testimonials</li>
          <li class="hover:effect">Features</li>
        </ul>
        <ul class="flex flex-col gap-2">
          <li class="text-lg font-semibold">Resources</li>
          <li class="hover:effect">Support</li>
          <li class="hover:effect">Conatct</li>
          <li class="hover:effect">Faq</li>
        </ul>
        <ul class="flex flex-col gap-2">
          <li class="text-lg font-semibold">Company</li>
          <li class="hover:effect">About</li>
          <li class="hover:effect">Customers</li>
          <li class="hover:effect">Blog</li>
        </ul>
        <ul class="flex flex-col gap-2">
          <li class="text-lg font-semibold">Portfolios</li>
          <li class="hover:effect">Pricing</li>
          <li class="hover:effect">Testimonials</li>
          <li class="hover:effect">Features</li>
        </ul>
      </div>
    </footer>
  </div>
</template>

<script></script>

<style></style>
