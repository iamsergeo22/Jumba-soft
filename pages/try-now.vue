<template>
  <div class="tw-bg-white tw-text-black">

    <div class="tw-relative tw-w-full tw-h-72">
      <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover" src="https://dotterra.netlify.app/static/media/soil.535488db91bb4bf12239.jpg"
        alt="Image">
        <div
        class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-center tw-items-center tw-bg-gray-900 tw-bg-opacity-60">
        <h1 class="lg:tw-text-4xl tw-text-2xl tw-font-bold tw-text-white" data-aos="fade-up">Try Now</h1>
      </div>
    </div>

    <div class="tw-flex tw-items-center tw-bg-white tw-text-black tw-space-x-2 tw-px-8">
      <v-breadcrumbs :items="breadcrumbItems" divider="/" class="tw-text-lg tw-font-extrabold"></v-breadcrumbs>
    </div>


    <h1 class="lg:tw-text-4xl tw-p-4 tw-text-center  tw-text-6xl text-color tw-font-extrabold"
        data-aos="fade-up">
        DotTerra Crop Recommendation System
      </h1>

      <p class="tw-mb-2 tw-text-xl tw-text-center tw-p-4">Find out the most suitable crop(s) to grow on your soil.</p>


    <div class="tw-shadow-2xl lg:-md lg:tw-mx-8 tw-transform tw--translate-y-58 tw-bottom-0 tw-left-0 tw-px-8 tw-py-12">
      <div class="lg:tw-flex lg:tw-flex-row sm:tw-flex sm:tw-flex-col lg:tw-justify-betwen lg:tw-gap-8">


    
        <div class="tw-text-md sm:tw-text-lg lg:tw-w-3/4">


          <form class="" v-on:submit.prevent="sendMessage">

            <div class="tw-w-full tw-md:w-1/2">
              <label class="tw-block tw-font-extrabold tw-mb-1" for="name">
                Soil pH (0-14)
              </label>

              <input type="name" name="name" id="email" placeholder="Enter the pH input" v-model="contact.name"
                class="tw-rounded-lg tw-block tw-w-full tw-bg-white tw-border tw-text-black tw-border-border-color-primary tw-shadow  tw-outline-none focus:tw-border-green-700 tw-mb-1 tw-p-3"
                required>
            </div>

            <div class="tw-w-full tw-md:w-1/2">
              <label class="tw-block tw-font-extrabold tw-mb-1" for="email">
                Soil Nitrogen (in ppm)
              </label>

              <input type="email" name="email" id="email" placeholder="Enter the Nitrogen input" v-model="contact.email"
                class="tw-rounded-lg tw-block tw-w-full tw-bg-white tw-text-black tw-border tw-border-border-color-primary tw-shadow  tw-outline-none focus:tw-border-green-700 tw-mb-1 tw-p-3"
                required>
            </div>


            <div class="tw-w-full tw-md:w-1/2">
              <label class="tw-block tw-font-extrabold tw-mb-1" for="text">
                Soil Phosphorus (in ppm)
              </label>

              <input type="text" name="text" id="text" placeholder="Enter the Phosphorus input" v-model="contact.position"
                class="tw-rounded-lg tw-block tw-w-full tw-bg-white tw-text-black tw-border tw-border-border-color-primary tw-shadow  tw-outline-none focus:tw-border-green-700 tw-mb-1 tw-p-3"
                required>
            </div>

            <div class="tw-w-full tw-md:w-1/2">
              <label class="tw-block tw-font-extrabold tw-mb-1" for="text">
                Soil Potassium (in ppm)
              </label>

              <input type="text" name="text" id="text" placeholder="Enter the Potassium input"
                v-model="contact.profile"
                class="tw-rounded-lg tw-block tw-w-full tw-bg-white tw-text-black tw-border tw-border-border-color-primary tw-shadow  tw-outline-none focus:tw-border-green-700 tw-mb-1 tw-p-3"
                required>
            </div>

          

            <button
              class="tw-group bg-color tw-relative tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-green-600 tw-border hover:tw-shadow-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-text-lg tw-shadow-2xl">
              <div
                class="tw-absolute tw-inset-0 tw-w-full bg-color tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
              </div>
              <span class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-white group-hover:tw-text-white">
                Recommend

              </span>
            </button>
          </form>
        </div>

        <div class="lg:tw-w-1/3 tw-text-black" data-aos="fade-up">
          <v-img class="tw-rounded-lg tw-shadow-2xl tw-mt-4"
            src="https://dotterra.netlify.app/static/media/soil.535488db91bb4bf12239.jpg"
            width="700px"></v-img>
        </div>



      </div> <!-- end hero -->

    </div>

   

  </div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
const swal = require('sweetalert2')

export default {
  data() {
    return {
      title: 'Contact Us Page',
      contact: {
        name: "",
        phone: "",
        email: "",
        position: "",
        profile: "",
        friend: "",
        google: "",
        linkedin: "",
        other: "",
        message: "",
      },

    }
  },
  setup() {
    if (process.client) {
      new AOS.init({ once: true, duration: 2000 });
    }
  },
  head() {
    return {
      title: 'Contact Us Page',

    }
  },

  mounted() {

  },
  computed: {
    breadcrumbItems() {
      const items = [{
        text: 'Home',
        href: '/',
      },
      {
        text: 'Try Now',

      },

      ];

      return items.map((item) => ({
        ...item,
        disabled: !item.href,
      }));
    },
  },

  methods: {


    async sendMessage(contact) {
      try {
        const response = await fetch('https://celebrated-hummingbird-8a34d4.netlify.app/.netlify/functions/send-email', {
          method: 'POST',
          body: JSON.stringify({
            contact: {
              name: this.contact.name,
              phone: this.contact.phone,
              email: this.contact.email,
              position: this.contact.position,
              profile: this.contact.profile,
              friend: this.contact.friend,
              google: this.contact.google,
              linkedin: this.contact.linkedin,
              other: this.contact.other,
              message: this.contact.message,
            }
          }),
          headers: {
            'Content-Type': 'application/json'
          }
        });
        const data = await response.json();
        if (response.ok) {
          new swal({
            title: 'Message Sent!',
            text: 'Your message has been sent successfully.',
            icon: 'success',
            button: 'Close',
          });
        }
        return data;
      } catch (error) {
        console.error('Error sending message:', error);
        new swal({
          title: 'Error!',
          text: 'An error has occurred while sending your message.',
          icon: 'error',
          button: 'Close',
        });
      }
    }



  },
}

</script>

<style scoped>
.bg-image {
  background-image: url(https://img.freepik.com/premium-photo/african-american-practitioner-assistant-with-protective-face-mask-against-coroanvirus_482257-26733.jpg?w=740);
  background-size: cover;
  height: 100%;
  width: 100%;
}

.text-color {
    color: green;
  }

.bg-color {
  background-color: green;
}

button {
  color: black
}

input,
textarea {
  border: 0.5px solid black;
  color: black;
}
</style>
