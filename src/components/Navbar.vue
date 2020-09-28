<template>
  <div>
    <nav class="flex items-center justify-between flex-wrap p-6" id="myNav">
      <div class="flex items-center flex-shrink-0 text-white mr-6 logo">
        <img src="../assets/images/logo.png" alt="logo" />
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
        <div class="nav-text text-16 lg:flex-grow">
          <a href="#home" class="block mt-4 lg:inline-block lg:mt-0"> Home </a>
          <a href="#feature" class="block mt-4 lg:inline-block lg:mt-0">
            Feature
          </a>
          <a
            href="#responsive-header"
            class="block mt-4 lg:inline-block lg:mt-0"
          >
            About Us
          </a>
        </div>
        <div>
          <button
            href="#"
            class="btn-contact text-white py-2 px-4 rounded-full"
          >
            Contact Us
          </button>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
