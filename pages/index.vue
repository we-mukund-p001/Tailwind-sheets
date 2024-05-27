<template>
  <!--navbar-->
  <nav class="border-gray-200  dark:bg-gray-800 dark:border-gray-700 ">
    <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
      <!--        headings-->
      <a href="#" class="flex items-center space-x-2 rtl:space-x-reverse">
        <img src="https://flowbite.com/docs/images/logo.svg" class="h-8" alt="Flowbite Logo"/>
        <span class="self-center text-xl font-semibold whitespace-nowrap hover:text-blue-600">Flowbite</span>
        <ul class="md:flex hidden items-center">
          <li class=" mx-[20px] cursor-pointer hover:text-blue-500 ">Company</li>
          <li class=" mx-[20px] cursor-pointer hover:text-blue-500">Marketplace</li>
          <li class=" mx-[20px] cursor-pointer hover:text-blue-500">Features</li>
          <li class=" mx-[20px] cursor-pointer hover:text-blue-500">Team</li>
          <li class=" mx-[20px] cursor-pointer hover:text-blue-500">Contact</li>
        </ul>
      </a>

<!--      burger-->
      <button data-collapse-toggle="navbar-hamburger" type="button"
              class="inline-flex items-center justify-center p-2 w-10 h-10 text-sm text-gray-500 rounded-lg hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600 md:hidden"
              aria-controls="navbar-hamburger" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
      </button>
      <div class="hidden w-full" id="navbar-hamburger">
        <ul class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
          <li>
            <a href="#" class="block py-2 px-3 text-white bg-blue-700 rounded dark:bg-blue-600"
               aria-current="page">Home</a>
          </li>
          <li>
            <a href="#"
               class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Services</a>
          </li>
          <li>
            <a href="#"
               class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white">Pricing</a>
          </li>
          <li>
            <a href="#"
               class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Contact</a>
          </li>
        </ul>
      </div>
<!--      side buttons-->
      <div class="flex items-center hidden lg:flex ">
        <p class="mx-[10px] cursor-pointer hover:text-blue-500 ">Log In</p>
        <button class=" text-white rounded-lg bg-blue-600 hover:bg-blue-700 p-2 px-4  ">Get started</button>
      </div>

    </div>


  </nav>


  <!--home-->
  <div class=" flex flex-col max-w-screen-xl flex-wrap items-center justify-between mx-auto ">

    <div class="px-4 md:px-0 flex flex-col md:items-center space-y-2 lg:flex-row pt-12">
      <div class="px-4 max-w-screen-xl lg:w-[55%]">
        <!-- inside button-->
        <div class="flex items-center">
          <div class="border-1 p-1 bg-stone-100 rounded-full flex">
            <button class=" text-white rounded-full bg-blue-600 text-xs px-2 hover:bg-blue-800 ">New</button>
            <div class="flex flex-row items-center hover:text-gray-700 text-gray-500 pr-2 cursor-pointer">
              <p class="mx-[10px] text-sm md:text-md   ">Flowbite v2 is out! See what's new </p>
              <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
                <g fill="none" fill-rule="evenodd">
                  <path
                      d="M24 0v24H0V0zM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035c-.01-.004-.019-.001-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427c-.002-.01-.009-.017-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093c.012.004.023 0 .029-.008l.004-.014l-.034-.614c-.003-.012-.01-.02-.02-.022m-.715.002a.023.023 0 0 0-.027.006l-.006.014l-.034.614c0 .012.007.02.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"/>
                  <path fill="currentColor"
                        d="M16.06 10.94a1.5 1.5 0 0 1 0 2.12l-5.656 5.658a1.5 1.5 0 1 1-2.121-2.122L12.879 12L8.283 7.404a1.5 1.5 0 0 1 2.12-2.122l5.658 5.657Z"/>
                </g>
              </svg>
            </div>
          </div>
        </div>

<!-- info-->
        <p class="font-bold text-4xl  md:text-6xl mt-4 lg:w-5/6 w-full">We invest in the world’s potential </p>
        <p class="md:text-xl text-slate-500 w-full mt-6 md:line-clamp-2"> Here at flowbite we focus on markets where technology
          innovation,
          and capital can unlock long-term value.</p>

        <div class="relative mb-6">
          <div class="absolute inset-y-0 start-0 flex items-center ps-3.5 pointer-events-none text-gray-500">
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 48 48"><path fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="4" d="M24 20a7 7 0 1 0 0-14a7 7 0 0 0 0 14M6 40.8V42h36v-1.2c0-4.48 0-6.72-.872-8.432a8 8 0 0 0-3.496-3.496C35.92 28 33.68 28 29.2 28H18.8c-4.48 0-6.72 0-8.432.872a8 8 0 0 0-3.496 3.496C6 34.08 6 36.32 6 40.8"/></svg>
          </div>
          <input type="text" id="input-group-1" class="bg-gray-50 mt-6 border border-gray-300 text-gray-900 text-sm rounded-md focus:ring-blue-500 focus:border-blue-500 block w-full md:w-8/12  ps-10 p-4 " placeholder="Enter email here">
        </div>


      </div>

<!--img-->
      <div class="flex flex-col  flex-wrap justify-end max-w-screen-xl lg:w-[44%]">

        <NuxtImg src="21.webp" loading="lazy" width="718" height="522.5"  fetchpriority="high"/>
      </div>

    </div>

<!--    info points-->
    <div class="flex flex-col md:flex-row py-20 px-4 space-y-8 md:space-y-0 ">
      <div class="space-y-2 w-full h-auto flex flex-wrap flex-col items-start">
        <div class="flex flex-row items-start space-x-3">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0"  class="text-blue-700 text-xl mt-1" width="1em" height="1em" viewBox="0 0 24 24"><g fill="currentColor"><path fill-rule="evenodd" d="M2.25 4.125c0-1.036.84-1.875 1.875-1.875h5.25c1.036 0 1.875.84 1.875 1.875V17.25a4.5 4.5 0 1 1-9 0zm4.5 14.25a1.125 1.125 0 1 0 0-2.25a1.125 1.125 0 0 0 0 2.25" clip-rule="evenodd"/><path d="M10.719 21.75h9.156c1.036 0 1.875-.84 1.875-1.875v-5.25c0-1.036-.84-1.875-1.875-1.875h-.14l-8.742 8.743q-.134.134-.274.257m2.019-4.124l6.474-6.475a1.875 1.875 0 0 0 0-2.651L15.5 4.787a1.875 1.875 0 0 0-2.651 0l-.1.099V17.25q0 .189-.01.375"/></g></svg>
          <p class="font-bold text-xl lg:text-xl">Customizable Categories </p>
        </div>
        <p class="text-slate-500 w-11/12 pl-9">Host code that you don't want to share with the
          world in private.</p>
      </div>
      <div class="space-y-2 w-full h-auto flex flex-wrap flex-col items-start">
        <div class="flex flex-row items-start space-x-3">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0" width="1em" height="1em" class="text-blue-700 mt-1 text-xl"
               viewBox="0 0 24 24">
            <path fill="currentColor"
                  d="M6 22q-.825 0-1.412-.587T4 20V10q0-.825.588-1.412T6 8h1V6q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6v2h1q.825 0 1.413.588T20 10v10q0 .825-.587 1.413T18 22zm6-5q.825 0 1.413-.587T14 15t-.587-1.412T12 13t-1.412.588T10 15t.588 1.413T12 17M9 8h6V6q0-1.25-.875-2.125T12 3t-2.125.875T9 6z"/>
          </svg>
          <p class="text-center font-bold text-xl lg:text-xl "> Private repos</p>
        </div>
        <p class="text-slate-500 w-11/12 pl-9"> Host code that you don't want to share with the
          world in private.</p>
      </div>
      <div class="space-y-2 w-full h-auto flex flex-wrap flex-col items-start">
        <div class="flex flex-row items-start space-x-3">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0" width="1em" height="1em" class="text-blue-700 mt-1 text-xl"
               viewBox="0 0 20 20">
            <path fill="currentColor" d="M3 3H1v16h18v-2H3z"/>
            <path fill="currentColor" d="M11 11L8 9l-4 4v3h14V5z"/>
          </svg>
          <p class="text-center font-bold text-xl lg:text-xl">Tracking Saving Rate</p>
        </div>
        <p class="text-slate-500 w-11/12 pl-9">Host code that you don't want to share with the
          world in private.</p>
      </div>
    </div>

  </div>


  <!--move beyond-->
  <div class="bg-gray-50">
    <div class="flex-col  max-w-screen-xl flex flex-wrap items-center justify-between mx-auto  ">
      <div class=" px-4 lg:px-0 flex flex-col space-y-12 lg:space-y-0 lg:flex-row  items-center my-20  ">
<!--info-->
        <div class=" lg:pl-4 lg:pr-16   lg:w-[55%]">

          <p class="font-bold text-3xl md:text-5xl w-4/6 ">Move beyond</p>
          <p class="md:text-lg  text-slate-500 w-full mt-6 md:line-clamp-3">We are strategists, designers and developers. Innovators and
            problem
            solvers. Small enough to be simple and quick, but big enough to deliver
            the scope you want at the pace you need.</p>
          <p class="md:text-lg  text-slate-500  mt-6 md:line-clamp-2">We are strategists, designers and developers. Innovators and .
            problem
            solvers. Small enough to be simple and quick.</p>

          <button
              class=" flex flex-row items-center space-x-2 border border-slate-300  p-2 px-4 bg-white rounded-xl mt-4 hover:text-white hover:bg-blue-700">
            <p>Try our dashboard </p>
            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 1024 1024"><path fill="currentColor" d="M754.752 480H160a32 32 0 1 0 0 64h594.752L521.344 777.344a32 32 0 0 0 45.312 45.312l288-288a32 32 0 0 0 0-45.312l-288-288a32 32 0 1 0-45.312 45.312z"/></svg>
          </button>
        </div>
<!--img-->
        <div class=" lg:px-1 lg:w-[44%]">
            <NuxtImg class=" border shadow-md rounded-lg"
                 src="moveBeond.webp" loading="lazy" width="643" height="490" fetchpriority="high"/>
        </div>


      </div>
    </div>
  </div>


  <!--design for business-->
  <div class="flex flex-col max-w-screen-xl flex-wrap mx-auto px-4 py-20">
<!--    heading-->
    <div class="mb-10">
      <p class="font-bold text-4xl">Designed for business teams like yours</p>
      <br>
      <p class="text-xl text-slate-600 md:w-4/6 md:line-clamp-2">Here we focus on markets where technology, innovation, and capital
        can unlock
        long-term value and drive economic growth.</p>
      <br>
    </div>
<!--    info list-->
    <div class="flex flex-col space-y-12 md:space-y-0  md:flex-row md:space-x-20  lg:space-x-44	">
      <div class="text-slate-500 lg:font-medium space-y-5">
        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em"
             class="h-14 w-14 border text-blue-600 rounded-md bg-blue-200 mb-6" viewBox="0 0 24 24">
          <path fill="currentColor"
                d="M12 3C7.58 3 4 4.79 4 7s3.58 4 8 4s8-1.79 8-4s-3.58-4-8-4M4 9v3c0 2.21 3.58 4 8 4s8-1.79 8-4V9c0 2.21-3.58 4-8 4s-8-1.79-8-4m0 5v3c0 2.21 3.58 4 8 4s8-1.79 8-4v-3c0 2.21-3.58 4-8 4s-8-1.79-8-4"/>
        </svg>
        <p class="font-bold lg:text-xl text-black "> Project Management </p>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-blue-200 rounded-full h-4 w-4 text-blue-600  mt-1 bg-blue-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>
          <p >Unified Contribution Graph</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg"  style="flex-shrink: 0"
               class=" border-2 border-blue-200 rounded-full h-4 w-4 text-blue-600  bg-blue-200 mt-1" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>
          <p >Org activity graph</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg"  style="flex-shrink: 0"
               class=" border-2 border-blue-200 rounded-full h-4 w-4 text-blue-600  mt-1 bg-blue-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>
          <p >Org dependency insights</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-blue-200 rounded-full h-4 w-4 text-blue-600  mt-1 bg-blue-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >Milestones</p></div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg"  style="flex-shrink: 0"
               class=" border-2 border-blue-200 rounded-full h-4 w-4 text-blue-600  mt-1 bg-blue-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >Repo insights</p>
        </div>
      </div>
      <div class="text-slate-500  md:mt-0 lg:font-medium space-y-5">
        <svg xmlns="http://www.w3.org/2000/svg" class=" mb-6 h-14 w-14 px-2 border rounded-md text-purple-600 bg-purple-100"
             width="1em" height="1em" viewBox="0 0 256 256">
          <path fill="currentColor"
                d="M71.68 97.22L34.74 128l36.94 30.78a12 12 0 1 1-15.36 18.44l-48-40a12 12 0 0 1 0-18.44l48-40a12 12 0 0 1 15.36 18.44m176 21.56l-48-40a12 12 0 1 0-15.36 18.44L221.26 128l-36.94 30.78a12 12 0 1 0 15.36 18.44l48-40a12 12 0 0 0 0-18.44M164.1 28.72a12 12 0 0 0-15.38 7.18l-64 176a12 12 0 0 0 7.18 15.37a11.79 11.79 0 0 0 4.1.73a12 12 0 0 0 11.28-7.9l64-176a12 12 0 0 0-7.18-15.38"/>
        </svg>
        <p class="font-bold lg:text-xl text-black ">Collaborative Coding</p>
        <div class="flex flex-row items-start max-w-[300px] space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-purple-100 rounded-full h-4 w-4 text-purple-600  bg-purple-100 mt-1" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>Code review assignments </p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-purple-100 rounded-full h-4 w-4 text-purple-600  mt-1 bg-purple-100" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>Dynamic reports and dashboards </p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-purple-100 rounded-full h-4 w-4 text-purple-600  mt-1 bg-purple-100" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>Team discussions</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-purple-100 rounded-full h-4 w-4 text-purple-600  mt-1 bg-purple-100" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>Protected branches</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg"  style="flex-shrink: 0"
               class=" border-2 border-purple-100 rounded-full h-4 w-4 text-purple-600  mt-1 bg-purple-100" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>Draft pull requests</p>
        </div>
      </div>
      <div class="text-slate-500   md:mt-0 lg:font-medium space-y-5">
        <svg xmlns="http://www.w3.org/2000/svg" width="1em"
             class=" mb-6 h-14 w-14 border rounded-md text-green-600 bg-green-200" height="1em" viewBox="0 0 24 24">
          <path fill="currentColor"
                d="M17 13v1c0 2.77-.664 5.445-1.915 7.846l-.227.42l-1.746-.974a14.89 14.89 0 0 0 1.881-6.836L15 14v-1zm-6-3h2v4l-.005.379a12.94 12.94 0 0 1-2.691 7.549l-.231.29l-1.549-1.264a10.944 10.944 0 0 0 2.47-6.588L11 14zm1-4a5 5 0 0 1 5 5h-2a3 3 0 0 0-6 0v3c0 2.235-.82 4.344-2.27 5.977l-.212.23l-1.448-1.38a6.97 6.97 0 0 0 1.924-4.524L7 14v-3a5 5 0 0 1 5-5m0-4a9 9 0 0 1 9 9v3c0 1.698-.201 3.37-.596 4.99l-.14.539l-1.93-.526c.392-1.437.614-2.922.658-4.435L19 14v-3A7 7 0 0 0 7.808 5.394L6.383 3.968A8.962 8.962 0 0 1 12 2M4.968 5.383l1.426 1.425a6.966 6.966 0 0 0-1.39 3.951L5 11l.004 2c0 1.12-.264 2.203-.761 3.177l-.157.29l-1.736-.992c.379-.665.6-1.407.645-2.183L3.004 13v-2a8.94 8.94 0 0 1 1.964-5.617"/>
        </svg>
        <p class="font-bold lg:text-xl text-black">Enterprise Security</p>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-green-200 rounded-full h-4 w-4 text-green-600  mt-1 bg-green-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >Required reviews</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-green-200 rounded-full h-4 w-4 text-green-600  mt-1 bg-green-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >Dependabot security and</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-green-200 rounded-full h-4 w-4 text-green-600  mt-1  bg-green-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >Dependency graph</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-green-200 rounded-full h-4 w-4 text-green-600  mt-1 bg-green-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p >GitHub Advisory Database</p>
        </div>
        <div class="flex flex-row items-start max-w-[300px]  space-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" style="flex-shrink: 0"
               class=" border-2 border-green-200 rounded-full h-4 w-4 text-green-600  mt-1 bg-green-200" width="1em"
               height="1em" viewBox="0 0 16 16">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
                  d="m2.75 8.75l3.5 3.5l7-7.5"/>
          </svg>

          <p>GPG commit signing verification</p>
        </div>

      </div>

    </div>
  </div>


  <!--grid-->
  <div class="bg-gray-50 ">
<!--    heading-->
    <section class="pt-20">
      <div class="pb-8 px-4 mx-auto max-w-screen-xl text-center lg:by-16">
        <h1 class="mb-4 text-4xl font-bold tracking-tight leading-none text-gray-900 md:text-4xl lg:text-4xl dark:text-white  md:line-clamp-1">
          What you can do with Flowbite</h1>
        <p class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-60 dark:text-gray-400 md:line-clamp-2">Here at
          flowbite we focus on markets where technology, innovation, and capital

          can unlock long-term value and drive economic growth.</p>
      </div>
    </section>
<!--     grid-->
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 max-w-screen-xl mx-auto px-4 pb-20	">
      <div class="flex justify-center ">
        <div
            class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
          <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" viewBox="0 0 14 14"><path fill="currentColor" fill-rule="evenodd" d="M3.658.162a.75.75 0 0 1 .918.53l.449 1.673a.75.75 0 1 1-1.45.389L3.129 1.08a.75.75 0 0 1 .53-.919ZM.072 3.755a.75.75 0 0 0 .53.918l1.673.448a.75.75 0 1 0 .388-1.448L.99 3.224a.75.75 0 0 0-.918.53Zm4.4 1.965a1 1 0 0 1 1.264-1.265l7.12 2.375c.92.307.908 1.612-.018 1.902l-2.026.637l2.7 2.7a1 1 0 0 1-1.415 1.414l-2.706-2.707l-.642 2.046c-.29.925-1.596.937-1.903.017l-2.375-7.12ZM2.066 8.755a.75.75 0 1 1-1.061-1.06L2.231 6.47a.75.75 0 0 1 1.06 1.06L2.067 8.755Zm6.46-6.591a.75.75 0 0 0-1.06-1.061L6.24 2.328a.75.75 0 0 0 1.061 1.06z" clip-rule="evenodd"/></svg>          <a href="#">
            <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Platform</h5>
          </a>
          <p class="mb-3 font-normal text-gray-500 dark:text-gray-400  ">We keep Flowbite, secure, and
            free of spam and abuse so that
            this can be the platform where
            developers come together to
            create.</p>

        </div>
      </div>
      <div class="flex justify-center ">
        <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 256 256"><path fill="currentColor" d="M71.68 97.22L34.74 128l36.94 30.78a12 12 0 1 1-15.36 18.44l-48-40a12 12 0 0 1 0-18.44l48-40a12 12 0 0 1 15.36 18.44m176 21.56l-48-40a12 12 0 1 0-15.36 18.44L221.26 128l-36.94 30.78a12 12 0 1 0 15.36 18.44l48-40a12 12 0 0 0 0-18.44M164.1 28.72a12 12 0 0 0-15.38 7.18l-64 176a12 12 0 0 0 7.18 15.37a11.79 11.79 0 0 0 4.1.73a12 12 0 0 0 11.28-7.9l64-176a12 12 0 0 0-7.18-15.38"/></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Open source</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">Our Flowbite Security Lab is a
          world-class security R&D team.
          We inspire and enable the
          community to secure open
          source.</p>
        </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 20 20"><path fill="currentColor" d="M11 3a1 1 0 1 0-2 0v1a1 1 0 1 0 2 0zm4.657 2.757a1 1 0 0 0-1.414-1.414l-.707.707a1 1 0 0 0 1.414 1.414zM18 10a1 1 0 0 1-1 1h-1a1 1 0 1 1 0-2h1a1 1 0 0 1 1 1M5.05 6.464A1 1 0 1 0 6.464 5.05l-.707-.707a1 1 0 0 0-1.414 1.414zM5 10a1 1 0 0 1-1 1H3a1 1 0 1 1 0-2h1a1 1 0 0 1 1 1m3 6v-1h4v1a2 2 0 1 1-4 0m4-2c.015-.34.208-.646.477-.859a4 4 0 1 0-4.954 0c.27.213.462.519.476.859z"/></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Premium products</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">We embody the shift toward
          investments in safe and secure
          software design practices with
          our world-class front-end
          products.</p>

      </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 20 20"><path fill="currentColor" fill-rule="evenodd" d="M3.5 2A1.5 1.5 0 0 0 2 3.5V15a3 3 0 1 0 6 0V3.5A1.5 1.5 0 0 0 6.5 2zm11.753 6.99L9.5 14.743V6.257l1.51-1.51a1.5 1.5 0 0 1 2.122 0l2.121 2.121a1.5 1.5 0 0 1 0 2.122M8.364 18H16.5a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5h-2.136zM5 16a1 1 0 1 0 0-2a1 1 0 0 0 0 2" clip-rule="evenodd"/></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Customization</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">It's easy to customize and style
          Flowbite. Tweak the look and
          feel of your UI with CSS/Less,
          and add major features with
          HTML.</p>

      </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 16 16"><path fill="currentColor" d="M8 16c3.314 0 6-2 6-5.5c0-1.5-.5-4-2.5-6c.25 1.5-1.25 2-1.25 2C11 4 9 .5 6 0c.357 2 .5 4-2 6c-1.25 1-2 2.729-2 4.5C2 14 4.686 16 8 16m0-1c-1.657 0-3-1-3-2.75c0-.75.25-2 1.25-3C6.125 10 7 10.5 7 10.5c-.375-1.25.5-3.25 2-3.5c-.179 1-.25 2 1 3c.625.5 1 1.364 1 2.25C11 14 9.657 15 8 15"/></svg>        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Features</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">Start with thousands of actions
          and applications from our
          community to help you build,
          improve, and accelerate your
          automated workflows.</p>

      </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 24 24"><path fill="currentColor" d="M17.81 4.47c-.08 0-.16-.02-.23-.06C15.66 3.42 14 3 12.01 3c-1.98 0-3.86.47-5.57 1.41c-.24.13-.54.04-.68-.2a.506.506 0 0 1 .2-.68C7.82 2.52 9.86 2 12.01 2c2.13 0 3.99.47 6.03 1.52c.25.13.34.43.21.67a.49.49 0 0 1-.44.28M3.5 9.72a.499.499 0 0 1-.41-.79c.99-1.4 2.25-2.5 3.75-3.27C9.98 4.04 14 4.03 17.15 5.65c1.5.77 2.76 1.86 3.75 3.25a.5.5 0 0 1-.12.7c-.23.16-.54.11-.7-.12a9.388 9.388 0 0 0-3.39-2.94c-2.87-1.47-6.54-1.47-9.4.01c-1.36.7-2.5 1.7-3.4 2.96c-.08.14-.23.21-.39.21m6.25 12.07a.47.47 0 0 1-.35-.15c-.87-.87-1.34-1.43-2.01-2.64c-.69-1.23-1.05-2.73-1.05-4.34c0-2.97 2.54-5.39 5.66-5.39s5.66 2.42 5.66 5.39c0 .28-.22.5-.5.5s-.5-.22-.5-.5c0-2.42-2.09-4.39-4.66-4.39s-4.66 1.97-4.66 4.39c0 1.44.32 2.77.93 3.85c.64 1.15 1.08 1.64 1.85 2.42c.19.2.19.51 0 .71c-.11.1-.24.15-.37.15m7.17-1.85c-1.19 0-2.24-.3-3.1-.89c-1.49-1.01-2.38-2.65-2.38-4.39c0-.28.22-.5.5-.5s.5.22.5.5c0 1.41.72 2.74 1.94 3.56c.71.48 1.54.71 2.54.71c.24 0 .64-.03 1.04-.1c.27-.05.53.13.58.41c.05.27-.13.53-.41.58c-.57.11-1.07.12-1.21.12M14.91 22c-.04 0-.09-.01-.13-.02c-1.59-.44-2.63-1.03-3.72-2.1a7.297 7.297 0 0 1-2.17-5.22c0-1.62 1.38-2.94 3.08-2.94s3.08 1.32 3.08 2.94c0 1.07.93 1.94 2.08 1.94s2.08-.87 2.08-1.94c0-3.77-3.25-6.83-7.25-6.83c-2.84 0-5.44 1.58-6.61 4.03c-.39.81-.59 1.76-.59 2.8c0 .78.07 2.01.67 3.61c.1.26-.03.55-.29.64c-.26.1-.55-.04-.64-.29a11.14 11.14 0 0 1-.73-3.96c0-1.2.23-2.29.68-3.24c1.33-2.79 4.28-4.6 7.51-4.6c4.55 0 8.25 3.51 8.25 7.83c0 1.62-1.38 2.94-3.08 2.94s-3.08-1.32-3.08-2.94c0-1.07-.93-1.94-2.08-1.94s-2.08.87-2.08 1.94c0 1.71.66 3.31 1.87 4.51c.95.94 1.86 1.46 3.27 1.85c.27.07.42.35.35.61c-.05.23-.26.38-.47.38"/></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Data privacy</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">Flowbite is committed to
          developer privacy and provides
          a high standard of privacy
          protection to all our customers
          and team.</p>

      </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 20 20"><path fill="currentColor" fill-rule="evenodd" d="M18 10a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-2 0c0 .993-.241 1.929-.668 2.754l-1.524-1.525a3.997 3.997 0 0 0 .078-2.183l1.562-1.562C15.802 8.249 16 9.1 16 10m-5.165 3.913l1.58 1.58A5.98 5.98 0 0 1 10 16a5.976 5.976 0 0 1-2.516-.552l1.562-1.562a4.006 4.006 0 0 0 1.789.027m-4.677-2.796a4.002 4.002 0 0 1-.041-2.08l-.08.08l-1.53-1.533A5.98 5.98 0 0 0 4 10c0 .954.223 1.856.619 2.657zm1.088-6.45A5.974 5.974 0 0 1 10 4c.954 0 1.856.223 2.657.619l-1.54 1.54a4.002 4.002 0 0 0-2.346.033zM12 10a2 2 0 1 1-4 0a2 2 0 0 1 4 0" clip-rule="evenodd"/></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">Support 24/7</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">We provide high-quality
          services all around the world
          with personal assistance
          through our 24/7 premium
          service.</p>

      </div>
      </div>
      <div class="flex justify-center ">

      <div class="max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-blue-500 mb-3 bg-blue-100 rounded-lg px-2" width="1em" height="1em" viewBox="0 0 24 24"><g fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"/><path fill="currentColor" d="M8 6V4c2.5-1.167 8.4-2 12 4h-1a2 2 0 0 0-2 2a2 2 0 1 1-4 0a2 2 0 0 0-2-2h-1a2 2 0 0 1-2-2m9 10h3c-1.2 1.6-3.833 3.333-5 4v-2a2 2 0 0 1 2-2m-6 2v2c-6.4-.4-8-5.5-8-8h2a2 2 0 0 1 2 2a2 2 0 0 0 2 2a2 2 0 0 1 2 2"/><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 6V4c2.5-1.167 8.4-2 12 4h-1a2 2 0 0 0-2 2a2 2 0 1 1-4 0a2 2 0 0 0-2-2h-1a2 2 0 0 1-2-2m9 10h3c-1.2 1.6-3.833 3.333-5 4v-2a2 2 0 0 1 2-2m-6 2v2c-6.4-.4-8-5.5-8-8h2a2 2 0 0 1 2 2a2 2 0 0 0 2 2a2 2 0 0 1 2 2"/></g></svg>
        <a href="#">
          <h5 class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white md:line-clamp-1">GDPR</h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400 ">Our project is full GDPR
          compliant. GDPR compliance is
          shown through our strong and
          transparent actions, not through
          certifications.</p>

      </div>
      </div>


    </div>
  </div>


  <!-- it was a great experience -->
  <div class="flex flex-col space-y-6  md:space-y-0 md:flex-row max-w-screen-xl items-center px-4 mx-auto mt-20 mb-20 ">
<!-- people-->
    <div class="w-full md:w-4/12 flex flex-col justify-start  ">

      <div
          class="flex flex-col cursor-pointer gap-1 py-2.5 px-5 me-2 mb-2  text-gray-900 focus:outline-none bg-white rounded-lg  hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-100 ">
        <div class=" flex flex-row space-x-3 items-center">
        <NuxtImg height="32" width="32" class="w-8 h-8 rounded-full object-cover"
             src="23.webp" alt=""/>
        <div class="font-semibold text-lg">
          <div class=" md:line-clamp-1 w-[170px]">Micheal Cough</div>
        </div>
        </div>
        <div class="text-sm text-gray-500 md:line-clamp-1 w-[170px] ">Web Developer at Google</div>

      </div>
      <div
          class="flex flex-col cursor-pointer gap-1 py-2.5 px-5 me-2 mb-2  text-gray-900 focus:outline-none bg-white rounded-lg  hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-100 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">
        <div class=" flex flex-row space-x-3 items-center">
        <NuxtImg height="32" width="32" class="w-8 h-8 rounded-full object-cover"
             src="24.webp" alt=""/>
        <div class="font-semibold text-lg">
          <div class=" md:line-clamp-1 w-[170px]">Bonnie Green</div>
        </div>
        </div>
          <div class="text-sm text-gray-500 md:line-clamp-1 w-[170px] ">CEO at Facebook</div>
      </div>
      <div
          class="flex flex-col cursor-pointer gap-1 py-2.5 lg:mb-8 px-5 me-2 mb-2  text-gray-900 focus:outline-none bg-white rounded-lg  hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-100 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">
        <div class=" flex flex-row space-x-3 items-center">
        <NuxtImg height="32" width="32" class="w-8 h-8 rounded-full object-cover"
             src="25.webp" alt=""/>
        <div class="font-semibold text-lg">
          <div class=" md:line-clamp-1 w-[170px]">Lana Byrd</div>
        </div>
        </div>
          <div class="text-sm text-gray-500  md:line-clamp-1 w-[170px]">CTO at Microsoft</div>
      </div>

      <div class="flex flex-row items-center space-x-2 text-blue-700  hover:underline px-5 text-sm cursor-pointer" ><p cl>View other 20 testimonials</p>
        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 1024 1024"><path fill="currentColor" d="M754.752 480H160a32 32 0 1 0 0 64h594.752L521.344 777.344a32 32 0 0 0 45.312 45.312l288-288a32 32 0 0 0 0-45.312l-288-288a32 32 0 1 0-45.312 45.312z"/></svg>
      </div>
    </div>
<!--info-->
    <div class="w-full md:w-8/12 flex flex-col space-y-2 lg:pl-20">
      <svg class="w-8 h-8 text-gray-400	" viewBox="0 0 24 27" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
            d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z"
            fill="currentColor"></path>
      </svg>

      <h1 class="font-bold text-2xl">It was a great experience!</h1>

      <p class=" text-gray-500 sm:text-justify lg:text-lg md:line-clamp-3">Flowbite is just awesome. It contains tons of predesigned
        components and pages starting
        from login screen to complex dashboard. Perfect choice for your next SaaS application.
      </p>

      <p class=" text-gray-500 sm:text-justify lg:text-lg md:line-clamp-4 "> There is absolutely no doubt in my mind that without
        Flowbite, I would not have been able to
        make the jump to Ueno, a digital agency I started in 2014. The work I got through Flowbite
        made it possible for me to have something to build on. We now have about 45 people on our
        team, a lot of whom we found and recruited through Flowbite.</p>
    </div>

  </div>


  <!--pricing built-->
  <div class="bg-gray-50">
  <div class="max-w-screen-xl mx-auto px-4 py-20">
    <div class="flex flex-col md:flex-row bg-white border shadow-md rounded-md overflow-hidden ">
<!--info-->
      <div class="flex flex-col bg-white md:w-9/12 mb-10  px-8 py-5">
<!--        heading-->
        <div class=" my-6   space-y-1">
          <p class="font-bold text-3xl lg:text-4xl">Pricing built for all businesses.</p>

          <p class=" lg:text-xl text-slate-600 md:w-1/2 md:line-clamp-1">Always know what you ll pay.</p>
          <br>
        </div>
<!--info list-->
        <div class="flex flex-col space-y-10 md:space-y-0 md:flex-row justify-between ">

          <div class="lg:space-y-4 space-y-2 font-semibold text-xs md:text-sm lg:text-base">
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[200px]">A/B Testing</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">24/7 Email & Chat Support</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[200px]">Custom Branding</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[200px]">Behavioral Targeting</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[200px]">Website Builder</p>
            </div>

          </div>
          <div class="lg:space-y-4 space-y-2 font-semibold text-xs md:text-sm lg:text-base">
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Advanced Segmentation</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Multivariate Testing</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Comparative Reporting</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Forms & Landing Pages</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Phone Support</p>
            </div>
          </div>
          <div class="lg:space-y-4 space-y-2 font-semibold text-xs md:text-sm lg:text-base">
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Customer Journey Builder</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Marketing CRM</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Custom Templates</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Creative Assistant</p>
            </div>
            <div class="flex flex-row space-x-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24">
                <path fill="#4CAF50" d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
              </svg>
              <p class="max-w-[210px]">Multivariate Testing</p>
            </div>
          </div>

        </div>
      </div>
<!--  price card-->
      <div class="w-full md:w-3/12 bg-gray-50 flex items-center justify-center">

        <section class="dark:bg-gray-900">
          <div class="py-8 md:py-0 mx-auto text-center">
            <h1 class=" text-4xl font-extrabold tracking-tight leading-none text-gray-900 md:text-4xl lg:text-5xl ">
              $99</h1>
            <p class="mb-2 text-md font-normal text-gray-500 lg:text-xl sm:px-16 lg:px-20 dark:text-gray-400">per
              month</p>
            <div class="flex flex-col space-y-4 px-4 justify-center md:space-y-0">
              <a href="#"
                 class="inline-flex justify-center items-center py-2 text-base  text-center text-white rounded-lg bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
                Buy now
              </a>

            </div>
            <div class=" flex flex-row items-center justify-center space-x-2 text-sm mt-2 text-gray-600 hover:text-blue-500 cursor-pointer"><p>Free for 30 days </p>
              <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 1024 1024"><path fill="currentColor" d="M754.752 480H160a32 32 0 1 0 0 64h594.752L521.344 777.344a32 32 0 0 0 45.312 45.312l288-288a32 32 0 0 0 0-45.312l-288-288a32 32 0 1 0-45.312 45.312z"/></svg>

            </div>
          </div>
        </section>

      </div>

    </div>

  </div>
  </div>


  <!--accordian-->
  <div>

<!--heading-->
    <section class="bg-white ">
      <div class="py-8 px-4 mx-auto max-w-screen-md  text-center lg:py-16">
        <h1 class="mb-4 text-3xl font-bold tracking-tight leading-none text-gray-900 md:text-3xl lg:text-4xl dark:text-white">
          Frequently asked questions</h1>
      </div>
    </section>

    <div class="max-w-screen-md mx-auto mb-20 px-4 ">
      <div id="accordion-flush" data-accordion="collapse"
           data-active-classes="bg-white dark:bg-gray-900 text-gray-900 dark:text-white"
           data-inactive-classes="text-gray-500 dark:text-gray-400">
        <h2 id="accordion-flush-heading-1">
          <button type="button"
                  class="flex items-center justify-between w-full py-5 font-medium rtl:text-right text-gray-500 border-b border-gray-200 dark:border-gray-700 dark:text-gray-400 gap-3"
                  data-accordion-target="#accordion-flush-body-1" aria-expanded="true"
                  aria-controls="accordion-flush-body-1">
            <span class="text-lg"> Can I use FlowBite in open source projects?</span>
            <svg data-accordion-icon class="w-3 h-3 rotate-180 shrink-0" aria-hidden="true"
                 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M9 5 5 1 1 5"/>
            </svg>
          </button>
        </h2>
        <div id="accordion-flush-body-1" class="hidden" aria-labelledby="accordion-flush-heading-1">
          <div class="py-5 border-b border-gray-200">
            <p class="mb-2 text-gray-500 ">Generally, it is accepted to use FlowBite in open-source projects, as long as it is not a
              UI library, a theme, a template, a page-builder that would be considered as an
              alternative to FlowBite itself. </p> <p class=" text-gray-500 ">With that being said, feel free to use this design kit for your open-source projects.
            </p> <p class="  mb-2 text-gray-500 ">
              Find out more information by  <a
                  href="/docs/getting-started/introduction/" class=" font-medium text-blue-600  hover:underline">reading the license</a></p>
          </div>
        </div>
        <h2 id="accordion-flush-heading-4">
          <button type="button"
                  class="flex items-center justify-between w-full py-5 font-medium rtl:text-right text-gray-500 border-b border-gray-200 gap-3"
                  data-accordion-target="#accordion-flush-body-1" aria-expanded="true"
                  aria-controls="accordion-flush-body-1">
            <span class="text-lg">Where can I access my download files?</span>
            <svg data-accordion-icon class="w-3 h-3 rotate-180 shrink-0" aria-hidden="true"
                 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M9 5 5 1 1 5"/>
            </svg>
          </button>
        </h2>
        <div id="accordion-flush-body-4" class="hidden" aria-labelledby="accordion-flush-heading-1">
          <div class="py-5 border-b border-gray-200">
            <p class="mb-2 text-gray-500 dark:text-gray-400">Flowbite is an open-source library of interactive
              components built on top of Tailwind CSS including buttons, dropdowns, modals, navbars, and more.</p>
            <p class="text-gray-500 dark:text-gray-400">Check out this guide to learn how to <a
                href="/docs/getting-started/introduction/" class="text-blue-600  hover:underline">get
              started</a> and start developing websites even faster with components on top of Tailwind CSS.</p>
          </div>
        </div>
        <h2 id="accordion-flush-heading-2">
          <button type="button"
                  class="flex items-center justify-between w-full py-5 font-medium rtl:text-right text-gray-500 border-b border-gray-200 gap-3"
                  data-accordion-target="#accordion-flush-body-2" aria-expanded="false"
                  aria-controls="accordion-flush-body-2">
            <span class="text-lg">Can I use FlowBite for commercial purposes?</span>
            <svg data-accordion-icon class="w-3 h-3 rotate-180 shrink-0" aria-hidden="true"
                 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M9 5 5 1 1 5"/>
            </svg>
          </button>
        </h2>
        <div id="accordion-flush-body-2" class="hidden" aria-labelledby="accordion-flush-heading-2">
          <div class="py-5 border-b border-gray-200 dark:border-gray-700">
            <p class="mb-2 text-gray-500 dark:text-gray-400">Flowbite is first conceptualized and designed using the
              Figma software so everything you see in the library has a design equivalent in our Figma file.</p>
            <p class="text-gray-500 dark:text-gray-400">Check out the <a href="https://flowbite.com/figma/"
                                                                         class="text-blue-600 dark:text-blue-500 hover:underline">Figma
              design system</a> based on the utility classes from Tailwind CSS and components from Flowbite.</p>
          </div>
        </div>
        <h2 id="accordion-flush-heading-3">
          <button type="button"
                  class="flex items-center justify-between w-full py-5 font-medium rtl:text-right text-gray-500 border-b border-gray-200 dark:border-gray-700 dark:text-gray-400 gap-3"
                  data-accordion-target="#accordion-flush-body-3" aria-expanded="false"
                  aria-controls="accordion-flush-body-3">
            <span class="text-lg">What about browser support?</span>
            <svg data-accordion-icon class="w-3 h-3 rotate-180 shrink-0" aria-hidden="true"
                 xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 10 6">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M9 5 5 1 1 5"/>
            </svg>
          </button>
        </h2>
        <div id="accordion-flush-body-3" class="hidden" aria-labelledby="accordion-flush-heading-3">
          <div class="py-5 border-b border-gray-200 dark:border-gray-700">
            <p class="mb-2 text-gray-500 dark:text-gray-400">The main difference is that the core components from
              Flowbite are open source under the MIT license, whereas Tailwind UI is a paid product. Another difference
              is that Flowbite relies on smaller and standalone components, whereas Tailwind UI offers sections of
              pages.</p>
            <p class="mb-2 text-gray-500 dark:text-gray-400">However, we actually recommend using both Flowbite,
              Flowbite Pro, and even Tailwind UI as there is no technical reason stopping you from using the best of two
              worlds.</p>
            <p class="mb-2 text-gray-500 dark:text-gray-400">Learn more about these technologies:</p>
            <ul class="ps-5 text-gray-500 list-disc dark:text-gray-400">
              <li><a href="https://flowbite.com/pro/" class="text-blue-600 dark:text-blue-500 hover:underline">Flowbite
                Pro</a></li>
              <li><a href="https://tailwindui.com/" rel="nofollow"
                     class="text-blue-600 dark:text-blue-500 hover:underline">Tailwind UI</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

  </div>


  <!--get started input-->
  <div class="bg-gray-50 ">
    <div class="py-8 px-4 mx-auto max-w-screen-xl  text-center lg:py-16 z-10 relative">
      <h1 class="mb-4 text-2xl font-bold tracking-tight leading-none text-gray-900 md:text-3xl lg:text-4xl dark:text-white">
        Get started with Flowbite today</h1>
      <p class="mb-8 text-base font-normal text-gray-500  lg:text-xl sm:px-16 lg:px-60 dark:text-gray-200 line-clamp-3">Connecting
        with your audience has never been easier with Flowbite straightforward email marketing and automation tools.</p>
<!--      input-->
      <div class="flex flex-col items-center">
        <form class="flex flex-col space-y-2 items-start md:flex-row md:space-x-4 space-x-0 max-w-lg mx-auto ">
          <label for="simple-search" class="sr-only">Search</label>
         <div class="flex flex-col	">
          <div class="relative w-full">
            <div class="absolute inset-y-0 start-0 flex items-center ps-3 pointer-events-none">
              <svg class="w-4 h-4 text-gray-500 dark:text-gray-400 " aria-hidden="true"
                   xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 16">
                <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
                <path
                    d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
              </svg>
            </div>
            <input type="text" id="simple-search"
                   class="bg-white border border-gray-300 text-gray-900 w-60 md:w-80 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block  ps-10 p-4"
                   placeholder="Enter your email" required/>
            </div>
          <div class="flex flex-col items-start mb-2 md:mb-0 mt-0">
            <p class="text-gray-500 text-xs mt-2 md:text-sm">Instant signup. No credit card required.</p>
          </div>
         </div>
          <button type="submit"
                  class=" w-full md:w-6/12 p-4 ms-2 text-sm font-medium text-white bg-blue-700  rounded-lg border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
            Try for 30 days
          </button>
        </form>

      </div>
    </div>
  </div>


  <!--contact Info-->
  <div>
    <div class="flex flex-col p-2 space-y-10 md:space-y-0  md:text-sm lg:text-base pl-2 md:flex-row justify-between  max-w-screen-xl mx-auto mt-4 ">
      <div class="md:space-y-4 text-gray-500  ml-2">
        <p class="text-black  font-semibold">New York</p>
        <div class="hover:underline cursor-pointer">
        <p class="max-w-[20px] ">Huntersville,</p>
        <p class="max-w-[300px]">957 Hill Hills Suite 491, United States</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class="mt-1 text-gray-500" xmlns="http://www.w3.org/2000/svg" width="0.63em" height="1em"
               viewBox="0 0 320 512">
            <path fill="currentColor"
                  d="M272 0H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h224c26.5 0 48-21.5 48-48V48c0-26.5-21.5-48-48-48M160 480c-17.7 0-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32s-14.3 32-32 32"/>
          </svg>
          <p class="max-w-[300px]">Office: +12(3) 456 7890 1234</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class="w-4 h-4 mt-1 text-gray-500 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
               fill="currentColor" viewBox="0 0 20 16">
            <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
            <path
                d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
          </svg>
          <p class="max-w-[300px]">Support: company@name.com</p>
        </div>
      </div>

      <div class="md:space-y-4 text-gray-500 ml-2">
        <p class="text-black font-semibold">Rome</p>
        <div class="hover:underline cursor-pointer">
        <p class="max-w-[300px]">Lungomare,</p>
        <p class="max-w-[300px]">7857 Lombardia 491, Italy</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class=" mt-1 text-gray-500" xmlns="http://www.w3.org/2000/svg" width="0.63em" height="1em"
               viewBox="0 0 320 512">
            <path fill="currentColor"
                  d="M272 0H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h224c26.5 0 48-21.5 48-48V48c0-26.5-21.5-48-48-48M160 480c-17.7 0-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32s-14.3 32-32 32"/>
          </svg>
          <p class="max-w-[300px]">Office: +12(3) 456 7890 1234</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class="mt-1 w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
               fill="currentColor" viewBox="0 0 20 16">
            <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
            <path
                d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
          </svg>

          <p class="max-w-[300px]">Support: company@name.com</p>
        </div>
      </div>

      <div class="md:space-y-4 text-gray-500 ml-2">
        <p class="text-black font-semibold">London</p>
        <div class=" hover:underline cursor-pointer">
        <p class="max-w-[300px]">6 Sunbeam St,</p>
        <p class="max-w-[400px]"> 131 South Lincoln Ave, 1214948, United Kingdom</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class="mt-1 text-gray-500" xmlns="http://www.w3.org/2000/svg" width="0.63em" height="1em"
               viewBox="0 0 320 512">
            <path fill="currentColor"
                  d="M272 0H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h224c26.5 0 48-21.5 48-48V48c0-26.5-21.5-48-48-48M160 480c-17.7 0-32-14.3-32-32s14.3-32 32-32s32 14.3 32 32s-14.3 32-32 32"/>
          </svg>
          <p class="max-w-[300px]">Office: +12(3) 456 7890 1234</p>
        </div>
        <div class="flex flex-row items-start space-x-2 hover:underline cursor-pointer">
          <svg class="mt-1 w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
               fill="currentColor" viewBox="0 0 20 16">
            <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
            <path
                d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
          </svg>

          <p class="max-w-[300px]">Support: company@name.com</p>
        </div>
      </div>
    </div>
  </div>


  <!-- footer input -->
  <div class="max-w-screen-xl mx-auto lg:flex  sm:flex justify-between bg-gray-50 p-3  my-10  rounded items-center lg:w-[55%] m-auto">
<!--    title-->
    <div class="text-center text-base mb-3 sm:mb-0 lg:mb-0 font-semibold text-gray-500">
      <p>Sign up to our newsletter</p>
    </div>
<!--    input-->
    <div class="lg:flex sm:flex ">
      <form class="max-w-sm mx-auto mb-3 sm:mb-0 lg:mb-0 flex ">
        <div class="relative">
          <div class="absolute inset-y-0 start-0 flex items-center ps-3.5 pointer-events-none">
            <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                 fill="currentColor" viewBox="0 0 20 16">
              <path d="m10.036 8.278 9.258-7.79A1.979 1.979 0 0 0 18 0H2A1.987 1.987 0 0 0 .641.541l9.395 7.737Z"/>
              <path
                  d="M11.241 9.817c-.36.275-.801.425-1.255.427-.428 0-.845-.138-1.187-.395L0 2.6V14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V2.5l-8.759 7.317Z"/>
            </svg>
          </div>
          <input type="text" id="email-address-icon"
                 class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-l-lg focus:ring-blue-500 focus:border-blue-500 block w-full ps-10 p-2.5   "
                 placeholder="Enter Your Email">
        </div>
        <div class="text-center">
          <button
              class="text-white  bg-blue-700 border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300  rounded-r-lg   text-sm px-5  py-2.5 me-2   focus:outline-none ">
            Subscribe
          </button>
        </div>
      </form>
    </div>
  </div>


  <!--footer-->
  <footer class="bg-white rounded-lg dark:bg-gray-900 m-4">
    <div class="w-full max-w-screen-xl mx-auto p-4 md:py-8 text-center ">
      <div class="sm:flex sm:items-center space-y-4 md:space-y-0 sm:justify-between">
        <a href="https://flowbite.com/" class="lg:flex lg:items-center mb-4 sm:mb-0 space-x-3 rtl:space-x-reverse ">
          <img src="https://flowbite.com/docs/images/logo.svg" class="h-8 m-auto inline-block" alt="Flowbite Logo"/>
          <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Flowbite</span>
        </a>
        <span class="block text-sm text-gray-500 sm:text-center dark:text-gray-400">© 2023 <a
            href="https://flowbite.com/" class="hover:underline">Flowbite™</a>. All Rights Reserved.</span>
        <div class="flex flex-row justify-center items-center space-x-2 ">
          <svg class="" xmlns="http://www.w3.org/2000/svg" width="1.89em" height="1em" viewBox="0 0 300 159">
            <rect width="300" height="159" fill="none"/>
            <g fill="none">
              <path fill="#fff" d="M0 .552h300v157.895H0z"/>
              <path fill="#b22234"
                    d="M0 .552h300v12.146H0zm0 24.292h300V36.99H0zm0 24.291h300v12.146H0zm0 24.292h300v12.146H0zm0 24.291h300v12.146H0zm0 24.292h300v12.146H0zm0 24.291h300v12.146H0z"/>
              <path fill="#3c3b6e" d="M0 .552h120v85.02H0z"/>
              <path fill="#fff"
                    d="m5.638 7.454l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.859 2.077l-1.092-3.361l2.858-2.077H31.25l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.534l-1.091-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm-89.527 8.527l2.859 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.36l2.859-2.077h-3.534l-1.091-3.361l-1.092 3.361zm19.895 0l2.859 2.077l-1.092 3.36l2.858-2.077l2.859 2.077l-1.092-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.859 2.077l-1.092 3.36L60 19.341l2.859 2.077l-1.092-3.36l2.858-2.077h-3.533L60 12.62l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.36l2.859-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.894 0l2.859 2.077l-1.092 3.36l2.858-2.077l2.859 2.077l-1.092-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.091 3.361zM5.638 24.507l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.859 2.077l-1.092-3.361l2.858-2.077H31.25l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.534l-1.091-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm-89.281 8.555l2.858 2.077l-1.091 3.36l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.076h-3.534l-1.091-3.361l-1.092 3.361zm19.894 0l2.859 2.077l-1.092 3.36l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.076h-3.533l-1.092-3.361l-1.092 3.361zM5.94 41.517l2.859 2.076l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.076l-1.092 3.361l2.859-2.077l2.858 2.077l-1.091-3.361l2.858-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.076l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.894 0l2.859 2.076l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.859-2.076h-3.534l-1.092-3.361l-1.091 3.361zm19.895 0l2.858 2.076l-1.091 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.076h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.076l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.076h-3.533l-1.092-3.361l-1.092 3.361zM6.127 58.299l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.091 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.091-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.859-2.077h-3.534l-1.092-3.36l-1.091 3.36zm19.895 0l2.858 2.077l-1.091 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zM5.884 75.279l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077H11.6l-1.091-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.091 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077H51.39l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.091-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.859-2.077h-3.534l-1.092-3.36l-1.091 3.36zm19.895 0l2.858 2.077l-1.091 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zM15.89 49.824l2.858 2.077l-1.091 3.36l2.858-2.077l2.859 2.077l-1.092-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.091-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.092-3.36l2.859-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.894 0l2.859 2.077l-1.092 3.36l2.858-2.077l2.859 2.077l-1.092-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.092 3.361zm19.895 0l2.858 2.077l-1.092 3.36l2.859-2.077l2.858 2.077l-1.091-3.36l2.858-2.077h-3.533l-1.092-3.361l-1.092 3.361zM15.831 66.777l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.092-3.361l2.859-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.894 0l2.859 2.077l-1.092 3.361l2.858-2.077l2.859 2.077l-1.092-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36zm19.895 0l2.858 2.077l-1.092 3.361l2.859-2.077l2.858 2.077l-1.091-3.361l2.858-2.077h-3.533l-1.092-3.36l-1.092 3.36z"/>
            </g>
          </svg>
          <p class="text-gray-500 text-sm">English (US) </p>
          <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" class="text-gray-500" viewBox="0 0 48 48">
            <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="4"
                  d="M36 18L24 30L12 18"/>
          </svg>
        </div>
      </div>

    </div>
  </footer>


</template>

<script setup>
</script>