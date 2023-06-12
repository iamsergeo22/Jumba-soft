<template>
  <div>

    <v-carousel class="" v-model="model" cycle :show-arrows="false" hide-delimiter-background height="500">
      <v-carousel-item class="tw-bg-to bg-color-banner tw-opacity-90" v-for="(item, i) in items" :key="i" :src="item.src"
        cover>
        <!--       <div class="tw-flex tw-flex-col tw-justify-center tw-items-center tw-p-12 tw-mt-24 tw-mx-8 tw-rounded-lg tw-shadow-lg bg-color-banner">
    <h1 class="tw-text-white lg:tw-text-5xl sm:tw-text-4xl tw-font-extrabold tw-text-center tw-uppercase">Welcome to JumbaSoft</h1>
    <p class="text-color lg:tw-text-2xl tw-sm:text-xl tw-italic tw-font-bold tw-text-center">We offer a wide variety of marketing services</p>
  </div> -->
      </v-carousel-item>
    </v-carousel>






    <section class="tw-bg-white lg:tw-p-12 tw-pb-12 tw-px-8 tw-py-8 tw-mb-4">

      <div class="tw-p-4 tw-mt-12 tw-flex lg:tw-flex-row tw-flex-col tw-gap-12 tw-justify-between">
        <div class="">
          <h1 class="lg:tw-text-6xl text-color tw-text-3xl tw-font-extrabold tw-text-black" data-aos="fade-up">
            Who we are?

          </h1>

          <p class="tw-mt-4 tw-flex lg:tw-flex-row tw-flex-col tw-gap-8 tw-justify-between" data-aos="fade-up">


            <span class=" tw-text-justify lg:tw-w-3/4">

              DotTerra is a pioneering technology company focused on empowering farmers to optimize their crop yields and
              profitability, all while prioritizing resource efficiency. Our innovative solutions are poised to make a
              significant impact in the agricultural industry and will be launching in the market very soon. </span>

          </p>

        </div>

        <div>

          <v-img class="tw-rounded-lg tw-shadow-2xl tw-shadow-orange-600 tw-cursor-pointer"
            src="https://img.freepik.com/free-photo/close-up-attractive-carefree-young-woman-sitting-floor_273609-35105.jpg?w=740&t=st=1686560978~exp=1686561578~hmac=2393967ab8379b6651770d9930e8115ce4bbb516d452395781110fc7dd3c7a0e"
            width="500px"></v-img>
        </div>

      </div>



    </section>



    <section class="tw-bg-gray-100 tw-py-12">
      <div class="tw-max-w-7xl tw-mx-auto tw-px-4 tw-sm:px-6 tw-lg:px-8">
        <div class="tw-lg:text-center">

          <p
            class="tw-mt-2 lg:tw-text-6xl tw-text-3xl tw-leading-8 tw-font-extrabold tw-tracking-tight text-color tw-sm:text-4xl">
            Our Team
          </p>
        </div>

        <div class="tw-mt-10">
          <div class="tw-mt-5 tw-grid tw-grid-cols-1 tw-gap-5 sm:tw-grid-cols-2 lg:tw-grid-cols-3">

            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/joeltassiga.jpeg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-bold tw-text-xl tw-leading-9 tw-font-medium tw-text-gray-900">
                  Massama-Joel TASSIGA
                </h3>
                <div class="tw-mt-2 tw-text-center tw-text-sm tw-leading-5 tw-text-gray-600">
                  <p>Founder</p>
                  <p class="tw-mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="tw-flex tw-justify-center tw-space-x-4">

                    <li>
                      <a href="https://twitter.com/STassiga" target="_blank"
                        class="tw-text-orange-600 tw-hover:text-orange-400">
                        <svg width="20" height="17" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M19.807 1.943a8.588 8.588 0 0 1-2.036 2.135 11.918 11.918 0 0 1-.465 3.854 12.085 12.085 0 0 1-1.452 3.177 12.426 12.426 0 0 1-2.318 2.691c-.897.78-1.978 1.402-3.243 1.867-1.265.464-2.618.697-4.06.697-2.27 0-4.348-.618-6.233-1.854.293.034.62.051.98.051 1.885 0 3.565-.588 5.04-1.764a3.915 3.915 0 0 1-2.363-.825 4.038 4.038 0 0 1-1.432-2.039c.276.043.532.064.766.064.36 0 .717-.047 1.068-.14A3.982 3.982 0 0 1 1.73 8.43c-.617-.754-.925-1.63-.925-2.627v-.051c.57.324 1.182.498 1.835.524a4.1 4.1 0.
                        0 0 1 2.57-.215 3.738-1.526a7.965 7.965 0 0 0 2.595-6.046v-.102a4.074 4.074 0 0 0-1.837-.356z" />
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a href="https://www.linkedin.com/in/stassiga/" target="_blank"
                        class="tw-text-orange-600 tw-hover:text-orange-400">
                        <svg width="20" height="20" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M18 2h-4.586c-.677 0-1.27.266-1.719.719l-.703.703c-.453.453-.719 1.046-.719 1.723v5.172c0 .677.266 1.27.719 1.723l.703.703c.453.453 1.046.719 1.723.719h4.172c.677 0 1.27-.266 1.723-.719l.703-.703c.453-.453.719-1.046.719-1.723v-5.172c0-.677-.266-1.27-.719-1.723l-.703-.703c-.453-.453-1.046-.719-1.723-.719zm-3 2c.552 0 1 .448 1 1v3h-2v-3c0-.552.448-1 1-1zm-4.891.094c-.35.012-.694.125-1.012.344s-.574.531-.625.938v4.625c.031.398.219.766.531 1.062s.637.453 1.031.469h.031c.35-.012.694-.125 1.012-.344s.574-.531.625-.938v-4.625c-.031-.398-.219-.766-.531-1.062s-.637-.453-1.031-.469h-.031zm-5.125.438c-.554 0-1 .446-1 1v4.25c0 .552.446 1 1 1h.281c.258.45.688.781 1.219.781.665 0 1.2-.535 1.219-1.188v-4.125c0-.554-.446-1-1-1h-.281c-.258-.45-.688-.781-1.219-.781zm0 0" />
                        </svg>
                      </a>
                    </li>
                  </div>
                </div>
              </div>
            </div>


            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/sergetassiga.jpg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-bold tw-text-xl tw-leading-9 tw-font-medium tw-text-gray-900">
                  Serge Anan TASSIGA
                </h3>
                <div class="tw-mt-2 tw-text-center tw-text-sm tw-leading-5 tw-text-gray-600">
                  <p>CTO</p>
                  <p class="tw-mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="tw-flex tw-justify-center tw-gap-8">

                    <li>
                      <a href="https://twitter.com/STassiga" target="_blank"
                        class="tw-text-orange-600 hover:tw-text-orange-400">
                        <svg width="20" height="17" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M19.807 1.943a8.588 8.588 0 0 1-2.036 2.135 11.918 11.918 0 0 1-.465 3.854 12.085 12.085 0 0 1-1.452 3.177 12.426 12.426 0 0 1-2.318 2.691c-.897.78-1.978 1.402-3.243 1.867-1.265.464-2.618.697-4.06.697-2.27 0-4.348-.618-6.233-1.854.293.034.62.051.98.051 1.885 0 3.565-.588 5.04-1.764a3.915 3.915 0 0 1-2.363-.825 4.038 4.038 0 0 1-1.432-2.039c.276.043.532.064.766.064.36 0 .717-.047 1.068-.14A3.982 3.982 0 0 1 1.73 8.43c-.617-.754-.925-1.63-.925-2.627v-.051c.57.324 1.182.498 1.835.524a4.1 4.1 0.
                        0 0 1 2.57-.215 3.738-1.526a7.965 7.965 0 0 0 2.595-6.046v-.102a4.074 4.074 0 0 0-1.837-.356z" />
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a href="https://www.linkedin.com/in/stassiga/" target="_blank"
                        class="tw-text-orange-600 hover:tw-text-orange-400">
                        <svg width="20" height="20" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M18 2h-4.586c-.677 0-1.27.266-1.719.719l-.703.703c-.453.453-.719 1.046-.719 1.723v5.172c0 .677.266 1.27.719 1.723l.703.703c.453.453 1.046.719 1.723.719h4.172c.677 0 1.27-.266 1.723-.719l.703-.703c.453-.453.719-1.046.719-1.723v-5.172c0-.677-.266-1.27-.719-1.723l-.703-.703c-.453-.453-1.046-.719-1.723-.719zm-3 2c.552 0 1 .448 1 1v3h-2v-3c0-.552.448-1 1-1zm-4.891.094c-.35.012-.694.125-1.012.344s-.574.531-.625.938v4.625c.031.398.219.766.531 1.062s.637.453 1.031.469h.031c.35-.012.694-.125 1.012-.344s.574-.531.625-.938v-4.625c-.031-.398-.219-.766-.531-1.062s-.637-.453-1.031-.469h-.031zm-5.125.438c-.554 0-1 .446-1 1v4.25c0 .552.446 1 1 1h.281c.258.45.688.781 1.219.781.665 0 1.2-.535 1.219-1.188v-4.125c0-.554-.446-1-1-1h-.281c-.258-.45-.688-.781-1.219-.781zm0 0" />
                        </svg>
                      </a>
                    </li>
                  </div>
                </div>
              </div>
            </div>

            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/joeltassiga.jpeg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-bold tw-text-xl tw-leading-9 tw-font-medium tw-text-gray-900">
                  Daniel AGOSSOU
                </h3>
                <div class="tw-mt-2 tw-text-center tw-text-sm tw-leading-5 tw-text-gray-600">
                  <p>UI/UX Designer</p>
                  <p class="tw-mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  <div class="tw-flex tw-justify-center tw-space-x-4">

                    <li>
                      <a href="https://twitter.com/STassiga" target="_blank"
                        class="tw-text-orange-600 tw-hover:text-orange-400">
                        <svg width="20" height="17" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M19.807 1.943a8.588 8.588 0 0 1-2.036 2.135 11.918 11.918 0 0 1-.465 3.854 12.085 12.085 0 0 1-1.452 3.177 12.426 12.426 0 0 1-2.318 2.691c-.897.78-1.978 1.402-3.243 1.867-1.265.464-2.618.697-4.06.697-2.27 0-4.348-.618-6.233-1.854.293.034.62.051.98.051 1.885 0 3.565-.588 5.04-1.764a3.915 3.915 0 0 1-2.363-.825 4.038 4.038 0 0 1-1.432-2.039c.276.043.532.064.766.064.36 0 .717-.047 1.068-.14A3.982 3.982 0 0 1 1.73 8.43c-.617-.754-.925-1.63-.925-2.627v-.051c.57.324 1.182.498 1.835.524a4.1 4.1 0.
                        0 0 1 2.57-.215 3.738-1.526a7.965 7.965 0 0 0 2.595-6.046v-.102a4.074 4.074 0 0 0-1.837-.356z" />
                        </svg>
                      </a>
                    </li>
                    <li>
                      <a href="https://www.linkedin.com/in/stassiga/" target="_blank"
                        class="tw-text-orange-600 hover:tw-text-orange-400">
                        <svg width="20" height="20" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                          <path
                            d="M18 2h-4.586c-.677 0-1.27.266-1.719.719l-.703.703c-.453.453-.719 1.046-.719 1.723v5.172c0 .677.266 1.27.719 1.723l.703.703c.453.453 1.046.719 1.723.719h4.172c.677 0 1.27-.266 1.723-.719l.703-.703c.453-.453.719-1.046.719-1.723v-5.172c0-.677-.266-1.27-.719-1.723l-.703-.703c-.453-.453-1.046-.719-1.723-.719zm-3 2c.552 0 1 .448 1 1v3h-2v-3c0-.552.448-1 1-1zm-4.891.094c-.35.012-.694.125-1.012.344s-.574.531-.625.938v4.625c.031.398.219.766.531 1.062s.637.453 1.031.469h.031c.35-.012.694-.125 1.012-.344s.574-.531.625-.938v-4.625c-.031-.398-.219-.766-.531-1.062s-.637-.453-1.031-.469h-.031zm-5.125.438c-.554 0-1 .446-1 1v4.25c0 .552.446 1 1 1h.281c.258.45.688.781 1.219.781.665 0 1.2-.535 1.219-1.188v-4.125c0-.554-.446-1-1-1h-.281c-.258-.45-.688-.781-1.219-.781zm0 0" />
                        </svg>
                      </a>
                    </li>
                  </div>
                </div>
              </div>
            </div>

            <!-- Add more team members here -->

          </div>
        </div>
      </div>
    </section>





    <section>



      <div class="tw-relative tw-h-96 tw-w-full">
        <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover tw-bg-top"
          src="https://img.freepik.com/free-photo/close-up-attractive-carefree-young-woman-sitting-floor_273609-35105.jpg?w=740&t=st=1686560978~exp=1686561578~hmac=2393967ab8379b6651770d9930e8115ce4bbb516d452395781110fc7dd3c7a0e"
          width="700px" alt="Image">
        <div
          class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-center tw-items-center tw-bg-black tw-bg-opacity-60 tw-p-8">
          <div class="tw-px-8 lg:tw-px-32 tw-items-center tw-justify-center tw-h-full">


          </div>
        </div>
      </div>

      <div
        class="tw-bg-orange-700 tw-shadow-2xl tw-rounded-md lg:tw-mx-24 tw-mx-8 tw-transform tw--translate-y-20 tw-bottom-0 tw-left-0 tw-px-8 tw-py-12">
        <h1 class="lg:tw-text-4xl tw-text-center tw-text-white tw-text-2xl tw-p-4" data-aos="fade-up">
          "Think before you toss! Unleash your creativity
          and give plastic a second life"
        </h1>
      </div>
      <!-- end hero -->
      <!-- end hero -->



    </section>


    <section class="tw-bg-white lg:tw-p-8 pt-0 tw-pb-12 tw-px-8 tw-py-8 tw-mb-4">

      <h1 class=" lg:tw-text-6xl  tw-text-3xl text-color tw-px-12 tw-font-extrabold tw-text-black" data-aos="fade-up">
        Why JumbaSoft?
      </h1>

      <div class="tw-flex lg:tw-flex-row tw-items-center tw-flex-col tw-justify-between tw-gap-12 lg:tw-p-12">
        <div class="tw-items-center">

          <div class="tw-flex tw-gap-4">
            <svg class="tw-rounded-full tw-bg-gray-200 tw-p-4" width="50" version="1.1" id="_x32_"
              xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512"
              xml:space="preserve" fill="#000000">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <g>
                  <path class="st0"
                    d="M406.195,383.984c-8.391,15.734-19.922,28.859-34.516,39.609c-14.656,10.719-32.188,18.703-52.563,23.969 c-8.906,2.25-18.234,3.813-27.703,5.094V512h-70.828v-58.156c-20.172-1.703-39.453-4.844-57.609-9.844 c-27.719-7.594-64.016-38.25-64.016-38.25c-3.109-1.813-5.172-5-5.609-8.531c-0.453-3.563,0.766-7.156,3.313-9.688l35.484-35.5 c3.828-3.781,9.766-4.5,14.359-1.688c0,0,26.563,23.063,46.688,28.563c20.125,5.469,40.094,8.219,60.016,8.219 c25.125,0,45.891-4.438,62.359-13.313c16.5-8.938,24.719-22.75,24.719-41.625c0-13.594-4.031-24.313-12.172-32.188 c-8.109-7.813-21.828-12.734-41.188-14.891l-63.563-5.469c-37.641-3.672-66.672-14.172-87.063-31.375 c-20.453-17.266-30.609-43.453-30.609-78.453c0-19.375,3.906-36.625,11.766-51.797c7.875-15.172,18.563-27.984,32.172-38.422 c13.594-10.469,29.438-18.313,47.469-23.531c7.547-2.188,15.453-3.625,23.484-4.938V0h70.828v50.094 c16.531,1.625,32.266,4.281,46.906,8.313c24.844,6.781,50.938,27.188,50.938,27.188c3.266,1.688,5.484,4.875,6.047,8.5 c0.563,3.688-0.641,7.313-3.219,9.969l-33.281,33.781c-3.547,3.594-9.031,4.531-13.563,2.188c0,0-19.703-14.031-36.734-18.469 c-17.016-4.438-34.891-6.688-53.719-6.688c-24.609,0-42.797,4.719-54.531,14.109c-11.781,9.453-17.625,21.734-17.625,36.875 c0,13.641,4.109,24.078,12.531,31.359c8.359,7.344,22.469,12.109,42.359,14.125l55.703,4.75 c41.297,3.656,72.563,14.625,93.734,32.922c21.203,18.328,31.781,45.016,31.781,80.016 C418.742,350.016,414.554,368.281,406.195,383.984z">
                  </path>
                </g>
              </g>
            </svg>
            <p class="tw-flex tw-flex-col">
              <span class="tw-text-lg tw-font-bold">Affordable</span>
              <span>Insights help farmers maximise crop yields</span>
            </p>

          </div>


          <div class="tw-mt-6 tw-flex tw-gap-4">
            <svg class="tw-rounded-full tw-bg-gray-200 tw-p-4" width="50" viewBox="0 0 48 48"
              xmlns="http://www.w3.org/2000/svg" fill="#000000">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <path d="M0 0h48v48H0z" fill="none"></path>
                <g id="Shopicon">
                  <path
                    d="M37.602,8c-5.108,0-17.423,0.821-24.812,8.21c-4.765,4.765-5.187,12.211-1.297,17.469l-5.833,5.833l2.828,2.828 l5.833-5.833c2.363,1.748,5.163,2.638,7.969,2.638c3.438,0,6.877-1.312,9.5-3.935c9.5-9.5,8.143-27.143,8.143-27.143 S39.062,8,37.602,8z M11.586,33.586l22-22l2.828,2.828l-22,22L11.586,33.586z">
                  </path>
                </g>
              </g>
            </svg>
            <p class="tw-flex tw-flex-col">
              <span class="tw-text-lg tw-font-bold">Sustainable</span>
              <span>Conducting soil optimization and treatment in advance</span>
            </p>

          </div>


          <div class="tw-mt-6 tw-flex tw-gap-4">
            <svg class="tw-rounded-full tw-bg-gray-200 tw-p-4" width="50" version="1.0" id="Layer_1"
              xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 64 64"
              enable-background="new 0 0 64 64" xml:space="preserve" fill="#000000">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <g>
                  <path fill="#231F20"
                    d="M33,1.832V16.05c3.678-0.095,7.227-0.706,10.573-1.775C40.982,9.398,37.362,5.155,33,1.832z"></path>
                  <path fill="#231F20"
                    d="M46.361,15.408c2.198,4.789,3.476,10.085,3.613,15.667h14c-0.245-7.968-3.396-15.202-8.439-20.675 C52.73,12.446,49.653,14.141,46.361,15.408z">
                  </path>
                  <path fill="#231F20"
                    d="M45.479,13.606c3.095-1.175,5.99-2.748,8.638-4.646c-5.278-5.051-12.278-8.312-20.035-8.811 C38.809,3.722,42.718,8.313,45.479,13.606z">
                  </path>
                  <path fill="#231F20"
                    d="M49.975,33.075c-0.153,6.246-1.736,12.134-4.438,17.354c3.153,1.134,6.117,2.66,8.846,4.508 c5.71-5.592,9.328-13.303,9.592-21.861H49.975z">
                  </path>
                  <path fill="#231F20"
                    d="M47.975,33.075H33v15.025c3.684,0.091,7.244,0.672,10.615,1.693C46.264,44.78,47.818,39.103,47.975,33.075z ">
                  </path>
                  <path fill="#231F20"
                    d="M31,33.075H16.025c0.156,6.027,1.711,11.705,4.359,16.719c3.371-1.021,6.932-1.603,10.615-1.693V33.075z">
                  </path>
                  <path fill="#231F20"
                    d="M33,62.318c3.844-2.929,7.113-6.569,9.609-10.731c-3.062-0.889-6.282-1.4-9.609-1.486V62.318z"></path>
                  <path fill="#231F20"
                    d="M33,31.075h14.975c-0.139-5.346-1.377-10.416-3.504-14.993C40.847,17.271,36.997,17.951,33,18.05V31.075z">
                  </path>
                  <path fill="#231F20"
                    d="M31,18.05c-3.997-0.099-7.848-0.779-11.471-1.968c-2.127,4.577-3.365,9.647-3.504,14.993H31V18.05z">
                  </path>
                  <path fill="#231F20"
                    d="M18.521,13.606c2.761-5.293,6.67-9.885,11.397-13.457c-7.757,0.499-14.757,3.76-20.035,8.812 C12.53,10.859,15.427,12.432,18.521,13.606z">
                  </path>
                  <path fill="#231F20"
                    d="M31,62.318V50.101c-3.327,0.086-6.548,0.598-9.609,1.486C23.887,55.749,27.156,59.391,31,62.318z">
                  </path>
                  <path fill="#231F20"
                    d="M44.559,52.21c-2.683,4.592-6.251,8.599-10.476,11.79c7.156-0.46,13.668-3.271,18.778-7.671 C50.293,54.639,47.512,53.244,44.559,52.21z">
                  </path>
                  <path fill="#231F20"
                    d="M19.441,52.209c-2.953,1.034-5.734,2.429-8.304,4.119c5.11,4.4,11.623,7.212,18.779,7.672 C25.692,60.809,22.124,56.802,19.441,52.209z">
                  </path>
                  <path fill="#231F20"
                    d="M14.025,33.075h-14c0.264,8.559,3.882,16.27,9.592,21.861c2.729-1.848,5.692-3.374,8.846-4.508 C15.762,45.209,14.179,39.321,14.025,33.075z">
                  </path>
                  <path fill="#231F20"
                    d="M31,1.832c-4.362,3.322-7.982,7.566-10.573,12.442c3.347,1.069,6.896,1.681,10.573,1.775V1.832z">
                  </path>
                  <path fill="#231F20"
                    d="M14.025,31.075c0.138-5.582,1.415-10.878,3.613-15.667c-3.292-1.268-6.369-2.962-9.174-5.008 c-5.043,5.473-8.194,12.707-8.439,20.675H14.025z">
                  </path>
                </g>
              </g>
            </svg>
            <p class="tw-flex tw-flex-col">
              <span class="tw-text-lg tw-font-bold">Clean</span>
              <span>Increasing crop health and quality</span>
            </p>

          </div>

        </div>

        <v-img class="tw-rounded-lg tw-shadow-2xl"
          src="https://img.freepik.com/free-photo/close-up-attractive-carefree-young-woman-sitting-floor_273609-35105.jpg?w=740&t=st=1686560978~exp=1686561578~hmac=2393967ab8379b6651770d9930e8115ce4bbb516d452395781110fc7dd3c7a0e"
          width="500px"></v-img>
      </div>

      <div class="tw-flex lg:tw-flex-row tw-flex-col tw-items-center tw-gap-4 lg:tw-p-6 tw-p-6">
        <h1 class="lg:tw-text-6xl text-color tw-text-3xl tw-font-extrabold" data-aos="fade-up">
          What We Stand For?
        </h1>


        <v-divider class="tw-my-6 tw-text-white tw-bg-gray-900"></v-divider>
      </div>

      <div
        class="tw-flex tw-flex-col lg:tw-flex-row tw-gap-6 lg:tw-gap-8 md:tw-gap-8 tw-container lg:tw-p-8 tw-p-4 lg:tw-justify-center tw-items-center tw-w-full">
        <!-- History -->
        <div
          class="tw-flex tw-shadow-2xl tw-rounded-lg tw-bg-gray-300 tw-block tw-p-6  tw-cursor-pointer tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class="tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/goal.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold tw-mb-2 tw-text-black">Our Goal</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-justify tw-text-center tw-max-w-sm">
            To become the leading provider of sustainable plastic waste management solutions in Africa, by reducing the
            number of plastic bottles sent to landfills by 50% at the of 2030.
          </p>
        </div>
        <!-- Achievement -->
        <div
          class="tw-flex tw-shadow-2xl tw-rounded-lg tw-bg-gray-300 tw-block tw-cursor-pointer tw-p-6  tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class=" tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/mission.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold tw-text-black tw-mb-2">Our Mission</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-center tw-max-w-sm tw-text-justify">
            Reduce plastic waste and promote a circular economy through partnerships, collection, recycling and
            repurposing of plastic bottles, while raising environmental awareness.
          </p>
        </div>
        <!-- Vision -->
        <div
          class="tw-flex tw-shadow-2xl tw-rounded-lg tw-bg-gray-300 tw-block tw-cursor-pointer tw-p-6 tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class=" tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/vision.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold tw-text-black tw-mb-2">Our Vision</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-center tw-max-w-sm tw-text-justify">
            Provide the best plastic waste management services to Africa and the rest of the world, to preserve the
            environment and its population. We strive to make a positive impact
          </p>
        </div>
      </div>


    </section>


    <section class="tw-w-full tw-h-full lg:tw-p-8 lg:tw-pb-12 tw-p-4">

      <h1 class=" lg:tw-text-6xl tw-text-4xl tw-font-extrabold text-color tw-px-4" data-aos="fade-up">
        Our Services
      </h1>

      <div class="tw-px-4 lg:tw-pb-12 tw-pt-8 tw-grid lg:tw-grid-cols-3 tw-gap-4 lg:tw-gap-0 tw-w-full tw-h-full">

        <div class=" tw-h-full tw-bg-white tw-block tw-cursor-pointer tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
              src="https://dotterra.netlify.app/static/media/soil.535488db91bb4bf12239.jpg" alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-4xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Technology</h1>
            </div>
          </div>

        </div>

        <div class="tw-cursor-pointer tw-bg-white tw-block tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
              src="https://img.freepik.com/premium-photo/creative-light-bulb-explodes-with-colorful-paint-splashes-black-background-think-differently-creative-idea-concept_338491-19427.jpg?w=740"
              alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-4xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Innovation</h1>
            </div>
          </div>


        </div>

        <div class="tw-cursor-pointer tw-bg-white tw-block tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-overflow-hidden tw-bg-cover tw-bg-no-repeat tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img
              class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover hover:tw-transition hover:tw-duration-300 hover:tw-ease-in-out hover:tw-scale-110"
              src="../assets/sustainability.png" alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-4xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Sustainability</h1>
            </div>
          </div>


        </div>
      </div>

    </section>





    <section class="tw-bg-white lg:tw-p-12 tw-pb-12 tw-px-8 tw-py-8 tw-mb-4">

      <h1 class="lg:tw-text-6xl tw-p-4  tw-text-6xl text-color lg:tw-mx-24 tw-font-extrabold tw-text-black"
        data-aos="fade-up">
        Careers
      </h1>

      <div class="tw-p-4 tw-mt-12 lg:tw-mx-24 lg:tw-w-3/4">
        <h1 class=" lg:tw-text-6xl tw-mb-4 tw-text-3xl tw-font-extrabold tw-text-black" data-aos="fade-up">
          Transform Your Professional Journey!

        </h1>


        <span class="tw-mt-12 tw-text-justify lg:tw-w-1/2" data-aos="fade-up">
          With the use of cutting-edge technology, we strive to save the environment. We encourage personal development
          and provide a welcoming workplace. You'll be a part of a vibrant, complementing team with a wealth of
          knowledge, including yourself! We all appreciate low hierarchies, science, and brainstorming. You will
          actively shape the direction of both our business and sustainability!



        </span>


        <h1 class="tw-mt-4 tw-text-xl tw-font-extrabold tw-text-black" data-aos="fade-up">
          We would adore having you on our team!

        </h1>

        <div class="tw-mt-4 tw-flex lg:tw-flex-row tw-flex-col tw-gap-12 tw-justify-between">

          <div>
            <span class="tw-text-justify" data-aos="fade-up">
              Learn more about our open positions or merely get in touch with us to discuss potential opportunities.
              Simply click the button below and let us know why you want to work with us.

            </span>
            <br>


            <button @click="$router.push('/contact')"
              class="tw-group tw-relative tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-orange-600 tw-border hover:tw-shadow-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-bg-white tw-text-lg tw-shadow-2xl">
              <div
                class="tw-absolute tw-inset-0 tw-w-3 tw-bg-orange-700 tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
              </div>
              <span class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-black group-hover:tw-text-white">
                Join now
                <svg class="tw-w-5 tw-h-5 tw--transition-all tw-duration-[250ms] tw-ease-out" fill="none"
                  stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3">
                  </path>
                </svg>
              </span>
            </button>



          </div>


        </div>




      </div>


    </section>



  </div>
</template>
<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
  data() {
    return {
      initialized: false,
      posts: [],
      items: [{
        src: 'https://img.freepik.com/free-photo/high-angle-woman-holding-smartphone_23-2150208257.jpg?w=740&t=st=1686560791~exp=1686561391~hmac=b64f13ad927ccb1d8ba80bdaf3a519ab2ced19a62f94d72eb02b1e2eeeeec3e5',
      },
      {
        src: 'https://img.freepik.com/free-photo/woman-checking-her-smartphone-notifications_23-2149093268.jpg?w=740&t=st=1686560845~exp=1686561445~hmac=4dfa48a46a3fd6e9cd96b7335fa5f5c2238a617eb3a92944585fdb90f6e922f1',
      },
      {
        src: 'https://img.freepik.com/premium-photo/positive-black-woman-showing-smartphone-gesturing-thumb-up-mockup_116547-28632.jpg',
      },
      {
        src: 'https://img.freepik.com/free-photo/close-up-attractive-carefree-young-woman-sitting-floor_273609-35105.jpg?w=740&t=st=1686560978~exp=1686561578~hmac=2393967ab8379b6651770d9930e8115ce4bbb516d452395781110fc7dd3c7a0e',
      },

      ],
    };
  },
  mounted() {
    this.initializeAOS();




  },


  destroyed() {
    AOS.refresh(); // Manually refresh AOS when the component is destroyed
  },

  methods: {
    initializeAOS() {
      if (!this.initialized) {
        AOS.init({
          once: true,
          duration: 2000
        });
        this.initialized = true;
      }
    },

  },
  head() {
    return {
      title: 'Welcome to Sheba Plastic Platform'
    };
  }
};

</script>



<style scoped>
button {
  border: 1px solid orangered;
  background-color: white;
}

.bg-color:hover {
  background-color: orangered;
  color: white;
}

.bg-color {
  background-color: orangered;
  color: white;
}

.bg-color-1 {
  background-color: orangered;
}

.bg-image {
  background-image: url('../assets/back.png');
  background-size: cover;
  height: 100%;
}

.bg-image-1 {
  background-image: url('../assets/omapny.png');
  background-size: cover;
  height: 100%;
}

.bg-hero {
  background-image: url("../assets/high-angle-woman-holding-smartphone.jpg");
  background-size: cover;
}

.bg-color-banner {
  background-color: #000000b0;
}



.text-color {
  color: orangered;
}

/* Popup */
.tw-modal {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-overlay {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-container {
  opacity: 0;
  visibility: hidden;
  transform: translateY(-50px);
  transition: all 0.3s ease-in-out;
}

.tw-modal .tw-modal-overlay {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open {
  opacity: 1;
  visibility: visible;
}


/* Popup */
.tw-modal {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-overlay {
  opacity: 0;
  visibility: hidden;
  transition: all 0.3s ease-in-out;
}

.tw-modal-container {
  opacity: 0;
  visibility: hidden;
  transform: translateY(-50px);
  transition: all 0.3s ease-in-out;
}

.tw-modal .tw-modal-overlay {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open {
  opacity: 1;
  visibility: visible;
}

.tw-modal.open .tw-modal-container {
  transform: translateY(0);
  opacity: 1;
  visibility: visible;
}

/* Close button */
.tw-modal-close {
  cursor: pointer;
}

/* Animation */
@keyframes fadeIn {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}

.animated {
  animation-duration: 0.3s;
  animation-fill-mode: both;
}

.fadeIn {
  animation-name: fadeIn;
}</style>
