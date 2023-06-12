<template>
    <div class="tw-bg-gray-100">
      <div class="tw-relative tw-w-full tw-h-72">
      <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
        src="../assets/high-angle-woman-holding-smartphone.jpg"
        alt="Banner Image">
      <div
        class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-center tw-items-center tw-bg-gray-900 tw-bg-opacity-60">
        <h1 class="tw-text-4xl tw-font-bold tw-text-white" data-aos="fade-up">Projects</h1>
      </div>
    </div>
    <div class="tw-flex tw-items-center tw-space-x-2 tw-px-8">
      <v-breadcrumbs :items="breadcrumbItems" divider="/" class="tw-text-lg tw-font-extrabold"></v-breadcrumbs>
    </div>
      <div class="tw-max-w-7xl tw-mx-auto tw-py-16 tw-px-4 tw-sm:px-6 tw-lg:px-8">
        <h1 class="tw-text-4xl tw-font-bold tw-mb-8 tw-text-orange-400 tw-text-center">Our Portfolio</h1>
        <div class="tw-grid tw-grid-cols-1 md:tw-grid-cols-2 lg:tw-grid-cols-3 tw-gap-8">
          <div class="tw-bg-white tw-shadow-lg tw-rounded-lg tw-overflow-hidden">
            <img src="../assets/high-angle-woman-holding-smartphone.jpg" alt="" class="tw-w-full tw-h-48 tw-object-cover">
            <div class="tw-p-6">
              <h2 class="tw-text-lg tw-font-bold tw-mb-4">Project 1</h2>
              <p class="tw-text-gray-700 tw-leading-relaxed tw-mb-4">Description of project 1</p>
              <p class="tw-text-gray-600">Technologies used: Tailwind CSS, Nuxt.js</p>
              <a href="https://project1url.com" class="tw-block tw-mt-4 tw-text-orange-400 tw-hover:text-orange-600 tw-font-bold">View project</a>
            </div>
          </div>
          <div class="tw-bg-white tw-shadow-lg tw-rounded-lg tw-overflow-hidden">
            <img src="../assets/high-angle-woman-holding-smartphone.jpg" alt="" class="tw-w-full tw-h-48 tw-object-cover">
            <div class="tw-p-6">
              <h2 class="tw-text-lg tw-font-bold tw-mb-4">Project 2</h2>
              <p class="tw-text-gray-700 tw-leading-relaxed tw-mb-4">Description of project 2</p>
              <p class="tw-text-gray-600">Technologies used: Tailwind CSS, Nuxt.js</p>
              <a href="https://project2url.com" class="tw-block tw-mt-4 tw-text-orange-400 tw-hover:text-orange-600 tw-font-bold">View project</a>
            </div>
          </div>
          <div class="tw-bg-white tw-shadow-lg tw-rounded-lg tw-overflow-hidden">
            <img src="../assets/high-angle-woman-holding-smartphone.jpg" alt="" class="tw-w-full tw-h-48 tw-object-cover">
            <div class="tw-p-6">
              <h2 class="tw-text-lg tw-font-bold tw-mb-4">Project 3</h2>
              <p class="tw-text-gray-700 tw-leading-relaxed tw-mb-4">Description of project 3</p>
              <p class="tw-text-gray-600">Technologies used: Tailwind CSS, Nuxt.js</p>
              <a href="https://project3url.com" class="tw-block tw-mt-4 tw-text-orange-400 tw-hover:text-orange-600 tw-font-bold">View project</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>

  <script>
  export default {
    setup() {
      
    },
    computed: {
      breadcrumbItems() {
        const items = [{
            text: 'Home',
            href: '/',
          },
          {
            text: 'Projects',

          },

        ];

        return items.map((item) => ({
          ...item,
          disabled: !item.href,
        }));
      },
    },
  }
  </script>
  