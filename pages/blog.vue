<template>
  <div class="">
    <div class="tw-relative tw-w-full">
      <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover" src="../assets/header.png"
        alt="Image">
      <div
        class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-center tw-items-center tw-bg-black tw-bg-opacity-60 tw-p-8 tw-mb-4">
        <div class="tw-px-8 lg:tw-px-32 tw-items-center tw-justify-center tw-h-full">
          <div class="tw-flex tw-flex-col tw-items-center tw-text-center tw-p-8">
            <nuxt-link to="/">
              <img class="tw-text-center" src="../assets/logo2.png" height="100px"
              >
            </nuxt-link>
          </div>

        </div>
      </div>
    </div>

    <div class="tw-flex tw-items-center tw-space-x-2 tw-px-8">
    <v-breadcrumbs
      :items="breadcrumbItems"
      divider="/"
      class="tw-text-lg tw-font-extrabold"
    ></v-breadcrumbs>
  </div>
    
  <div class="tw-relative tw-min-h-screen">

    <div class="tw-relative tw-w-full tw-h-96">
    <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover tw-min-h-screen" src="https://img.freepik.com/free-photo/serious-dark-skinned-woman-with-curly-hair-has-confident-gaze-recommends-you-something_273609-45538.jpg?w=740&t=st=1684172197~exp=1684172797~hmac=0db2cfa96269fde13b38db34988eb1e9865a940c42ba7faa35532479383dc61a" alt="Banner Image">
    <div class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-row tw-justify-end tw-items-center tw-bg-black tw-bg-opacity-50 tw-min-h-screen">
      <div class="tw-mr-16" data-aos="fade-up" data-aos-duration="3000">
        <h1 class="lg:tw-text-6xl tw-text-4xl tw-font-bold tw-text-white tw-text-right">
        Coming Soon
      </h1>
      <p class="tw-text-white tw-mt-3 tw-text-md tw-text-right" data-aos="fade-up" data-aos-duration="3000">We are working on something awesome. Stay tuned!</p>

      </div>
    </div>
  </div>
    
  </div>
  </div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
export default {
  head() {
      return {
        title: 'Blog Page'

      }
    },
    setup() {
      if (process.client) {
     new AOS.init({once: true, duration: 2000});
  }
    },
  computed: {
    breadcrumbItems() {
      const items = [
        {
          text: 'Home',
          href: '/',
        },
        {
          text: 'Blog',
          
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

<style scoped>
.tw-min-h-screen {
  min-height: 100vh;
}

.bg-color {
    background-color: #0097b2;
  }

</style>
