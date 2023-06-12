<template>
    <div
      class="lg:tw-fixed tw-inset-0 tw-hidden tw-bg-black tw-bg-opacity-70 tw-z-50 tw-p-8 tw-flex tw-items-center tw-justify-center"
      v-show="showDialog"
      @click.self="closeDialog"
    >
    
      <div class="tw-bg-white tw-rounded-lg tw-shadow-2xl tw-flex lg:tw-flex-row tw-flex-col tw-gap-8">

        <v-img class="tw-rounded-l-lg tw-shadow-2xl"
            src="https://images.pexels.com/photos/4498089/pexels-photo-4498089.jpeg?auto=compress&cs=tinysrgb&w=600"
            width="500px" height="500px"></v-img>
      
        <div class="tw-items-center lg:tw-pt-40 lg:tw-mr-8">
            
            <p class="lg:tw-text-3xl text-color tw-font-extrabold tw-mb-4">
            Subscribe to Sheba Plastic newsletter
            <br>
            to receive timely updates from us.
        </p>
        <div class="tw-w-full">
              
              <input type="email" name="email" id="email" placeholder="Please Enter Your Email here..."
                class="tw-block tw-w-full tw-bg-white tw-border tw-shadow tw-rounded focus:tw-border-black tw-mb-2 tw-p-4"
                required>
            </div>
        <div class="tw-flex tw-justify-end tw-gap-2 tw-mt-4">
            <button type="submit" 
              class="bg-color-1 hover:tw-bg-blue-600 tw-text-white tw-text-sm tw-font-semibold tw-uppercase tw-shadow tw-rounded tw-cursor-pointer tw-px-6 tw-py-3">
              Submit
            </button>
          <button class="tw-bg-red-800 tw-text-white tw-text-sm tw-font-semibold tw-uppercase tw-shadow tw-rounded tw-cursor-pointer tw-px-6 tw-py-3" @click="closeDialog">Cancel</button>
        </div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" @click="closeDialog" class="tw-cursor-pointer tw-h-6 tw-w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
</svg>

       
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      showDialog: {
        type: Boolean,
        default: false,
      },
    },
    methods: {
      closeDialog() {
        this.$emit("close");
      },
    },
  };
  </script>

  <style scoped>
  .text-color {
    color: #0097b2;
  }

  .bg-color-1 {
    background-color: #0097b2;
    color: white;
  }

  .bg-color {
    background-color: #7ed957;
  }


  input {
    border: 1px solid black;
    color: black;
  }
  </style>
  