<template>
  <header
    class="sticky top-0 z-30 w-full border-b border-transparent max-md:border-gray-100 bg-gray/50 backdrop-blur-xl md:border-gray-100"
  >
    <div
      class="mx-auto flex w-full max-w-7xl items-center justify-between p-4 md:px-8"
    >
      <a href="/"
        ><h3
          class="text-2xl md:text-3xl tracking-[-0.02em] text-gray-900 font-bold"
        >
          Sandberg
        </h3></a
      >
      <div class="hidden items-center gap-6 md:flex">
        <ul class="flex list-none items-center gap-6">
          <li>
            <a
              target="_self"
              class="text-base font-medium text-gray-600 transition-all hover:text-gray-900 active:text-gray-600"
              href="#about"
              >About</a
            >
          </li>
          <li>
            <a
              target="_self"
              class="text-base font-medium text-gray-600 transition-all hover:text-gray-900 active:text-gray-600"
              href="#work"
              >Work</a
            >
          </li>
          <li>
            <a
              target="_self"
              class="text-base font-medium text-gray-600 transition-all hover:text-gray-900 active:text-gray-600"
              href="#testimonials"
              >Testimonials</a
            >
          </li>
          <li>
            <a
              target="_self"
              class="text-base font-medium text-gray-600 transition-all hover:text-gray-900 active:text-gray-600"
              href="#contact"
              >Contact</a
            >
          </li>
        </ul>
        <div class="h-6 w-0.5 bg-gray-100"></div>
        <div class="flex items-center gap-4">
          <button
            class="relative flex justify-center items-center hover:bg-gray-100 active:bg-gray-200 rounded-lg p-1.5 transition-colors duration-200 [&amp;_svg]:stroke-gray-600 [&amp;_svg]:hover:stroke-gray-700 [&amp;_svg]:w-6 [&amp;_svg]:h-6"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="lucide lucide-moon-star"
            >
              <path d="M12 3a6 6 0 0 0 9 9 9 9 0 1 1-9-9Z"></path>
              <path d="M19 3v4"></path>
              <path d="M21 5h-4"></path>
            </svg>
          </button>
          <!-- <button
            class="inline-flex items-center justify-center rounded-xl bg-gray-900 px-4 py-1.5 font-medium text-gray-50 transition-colors duration-200 hover:bg-gray-700 active:bg-gray-800"
          >
            Download CV
          </button> -->
        </div>
      </div>
      <button
        class="relative justify-center items-center hover:bg-gray-100 active:bg-gray-200 rounded-lg p-1.5 transition-colors duration-200 [&amp;_svg]:stroke-gray-600 [&amp;_svg]:hover:stroke-gray-700 [&amp;_svg]:w-6 [&amp;_svg]:h-6 flex md:hidden"
        type="button"
        aria-haspopup="dialog"
        aria-expanded="false"
        aria-controls="radix-:R1mja:"
        data-state="closed"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="lucide lucide-menu"
        >
          <line x1="4" x2="20" y1="12" y2="12"></line>
          <line x1="4" x2="20" y1="6" y2="6"></line>
          <line x1="4" x2="20" y1="18" y2="18"></line>
        </svg>
      </button>
    </div>
  </header>
</template>
