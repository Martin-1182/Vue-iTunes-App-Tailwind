<template>
  <div>
    <nav class="flex items-center justify-between flex-wrap p-6">
      <div class="flex items-center flex-shrink-0 text-white mr-6">
        <svg
          class="fill-current h-8 w-8 mr-2"
          width="54"
          height="54"
          viewBox="0 0 54 54"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"
          />
        </svg>
        <span class="font-semibold text-xl tracking-tight"
          >iTunes Aplication</span
        >
      </div>
      <div class="block lg:hidden">
        <button
          class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white"
        >
          <svg
            class="fill-current h-3 w-3"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
            to="/"
            >Home</router-link
          >
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
            to="/about"
            >About</router-link
          >
          <router-link
            class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4"
            to="/tunes"
            >Tunes</router-link
          >
        </div>
      </div>
      <div class="flex flex-col md:flex-row items-center">
        <div class="relative mt-3 md:mt-0">
          <input
            type="text"
            class="bg-gray-800 text-sm rounded-full w-64 px-4 pl-8 py-1 focus:outline-none focus:shadow-outline"
            placeholder="Vyhľadávanie"
          />

          <div class="absolute top-0">
            <svg
              class="fill-current w-4 text-gray-500 mt-2 ml-2"
              viewBox="0 0 24 24"
            >
              <path
                class="heroicon-ui"
                d="M16.32 14.9l5.39 5.4a1 1 0 01-1.42 1.4l-5.38-5.38a8 8 0 111.41-1.41zM10 16a6 6 0 100-12 6 6 0 000 12z"
              />
            </svg>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
