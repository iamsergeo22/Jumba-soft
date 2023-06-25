<template>
  <div class="font-sans tw-flex tw-flex-col tw-opacit-90">


    <header>
      <nav
        class="font-sans tw-shadow-lg tw-mx-auto tw-flex tw-flex-wrap tw-gap-4 tw-px-8 tw-lg:justify-evenly tw-justify-between tw-items-center tw-py-6">
        <div>
          <nuxt-link to="/">
            <h1 class="tw-text-4xl tw-font-extrabold tw-text-orange-600">
              JumbaSoft
            </h1>
          </nuxt-link>

        </div>
        <div class="tw-block lg:tw-hidden">
          <button @click="toggleMenu"
            class="tw-flex tw-items-center tw-px-3 tw-py-2 border tw-rounded tw-border-gray-500 hover:tw-border-gray-600">
            <svg class="tw-current-color tw-h-3 tw-w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" fill="gray" />
            </svg>
          </button>
        </div>
        <ul
          class="tw-tracking-wide tw-items-center tw-font-medium tw-w-full tw-block tw-flex-grow lg:tw-space-x-8 tw-space-y-6 lg:tw-space-y-0 lg:tw-flex lg:tw-flex-initial lg:tw-w-auto tw-items-center tw-mt-8 lg:tw-mt-0"
          :class="{ 'tw-block': isOpen, 'tw-hidden': !isOpen }">
          <li class="tw-mb-6 lg:tw-mb-0">
            <!-- <search-input /> -->
          </li>

          <li @click="closeMenu">
            <nuxt-link to="/" :class="$route.path === '/' ? 'active' : ''"
              class="text-black font-medium	hover:text-orange-800 text-md hover:no-underline">Home</nuxt-link>
          </li>
          <li @click="closeMenu">
            <nuxt-link to="/project" :class="$route.path === '/project' ? 'active' : ''"
              class="text-black font-medium	hover:text-orange-800 text-md hover:no-underline">Projects</nuxt-link>
          </li>

         <!--  <li @click="closeMenu">
            <nuxt-link to="/contact" :class="$route.path === '/contact' ? 'active' : ''"
              class="text-black font-medium	hover:text-orange-800 text-md hover:no-underline">Contact</nuxt-link>
          </li> -->
          <div class="lg:tw-hidden tw-block" @click="closeMenu">
          <button @click="$router.push('/contact')"
            class="tw-group tw-relative tw-border-2 tw-h-12 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-orange-600 tw-border hover:tw-shadow-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-bg-white tw-text-lg tw-shadow-2xl">
            <div
              class="tw-absolute tw-inset-0 tw-w-3 tw-bg-orange-700 tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
            </div>
            <span class="tw-relative tw-inline-flex tw-items-center text-md tw-gap-2 tw-text-black group-hover:tw-text-white">
              Send a request
              <svg class="tw-w-5 tw-h-5 tw--transition-all tw-duration-[250ms] tw-ease-out" fill="none"
                stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3">
                </path>
              </svg>
            </span>
          </button>
        </div>

        <button @click="$router.push('/contact')"
            class="tw-group lg:tw-block tw-hidden tw-relative tw-border-2 tw-h-12 tw-mt-4 tw-cursor-pointer hover:tw-transform hover:tw-translate-x-2 hover:tw-transition-transform hover:tw-duration-300 hover:tw-shadow-orange-600 tw-border hover:tw-shadow-lg tw-w-48 tw-overflow-hidden tw-rounded-lg tw-bg-white tw-text-lg tw-shadow-2xl">
            <div
              class="tw-absolute tw-inset-0 tw-w-3 tw-bg-orange-700 tw--transition-all tw-duration-[250ms] tw-ease-out group-hover:tw-w-full">
            </div>
            <span class="tw-relative tw-inline-flex tw-items-center tw-gap-2 tw-text-black group-hover:tw-text-white">
              Send a request
              <svg class="tw-w-5 tw-h-5 tw--transition-all tw-duration-[250ms] tw-ease-out" fill="none"
                stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3">
                </path>
              </svg>
            </span>
          </button>

        </ul>
      </nav>
    </header>



    <div class="tw-flex-grow">
      <Nuxt />
    </div>


    <footer class="tw-text-white">

      <div class="tw-relative tw-w-full tw-h-full tw-p-12 tw-pb-4 tw-bg-black tw-bg-opacity-80">

        <v-row class="">

          <v-col  class="tw-text-left tw-mt-8" cols="12" md="3" lg="3">
            <nuxt-link to="/">
            <h1 class="tw-text-4xl tw-font-extrabold tw-mb-4 tw-text-orange-600">
              JumbaSoft
            </h1>
          </nuxt-link>
            <p class="tw-text-white tw-text-md tw-justify-center">
              Every image featured on this website has been designed using Canvas.
            </p>
          </v-col>

          <v-col class="tw-mt-8" cols="12" md="3" lg="3">
            <h3 class="tw-text-white tw-font-extrabold tw-mb-4">Contact Us</h3>
            <p class="tw-text-white tw-text-md">
              <span class="tw-mb-12"><strong>Location:</strong> Accra, Ghana</span><br>
              <a href="mailto:info@Jumbasoft.net" class="tw-text-white tw-mb-8">
                <strong>Email:</strong>
                info@Jumbasoft.net</a><br />
              <a href="tel:+233-53-124-2989" class="tw-text-white tw-mb-8"><strong>Ghana Tel:</strong> 
                +233 53 124 2989
              </a><br />
              <a href="tel:+250-785-658-174" class="tw-text-white tw-mb-8"><strong>Rwanda Tel:</strong> 
                +250 785 658 174
              </a>
            </p>
          </v-col>
          <v-col class="tw-mt-8" cols="12" md="6" lg="3">
            <h3 class="tw-text-white tw-font-extrabold tw-mb-4">Useful Links</h3>
            <ul class="tw-list-disc tw-list-inside tw-text-gray-400 tw-leading-6">
              <li>
                <a href="/privacy" class="tw-text-white">Privacy Policy</a>
              </li>
              <li>
                <a href="/contact" class="tw-text-white">Contact us</a>
              </li>


            </ul>
          </v-col>
          <v-col class="tw-mt-8" cols="12" md="6" lg="3">
            <h3 class="tw-text-white tw-font-extrabold tw-mb-4">Connect with Us</h3>
            <div class="tw-mb-4">
              <ul class="tw-flex tw-items-center tw-gap-4">
                <li>
                  <a href="https://www.linkedin.com/company/sheba-plastic/" target="_blank" class="tw-text-white">
                    <svg width="32" height="32" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
                      <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                      <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                      <g id="SVGRepo_iconCarrier">
                        <path fill="#0A66C2"
                          d="M12.225 12.225h-1.778V9.44c0-.664-.012-1.519-.925-1.519-.926 0-1.068.724-1.068 1.47v2.834H6.676V6.498h1.707v.783h.024c.348-.594.996-.95 1.684-.925 1.802 0 2.135 1.185 2.135 2.728l-.001 3.14zM4.67 5.715a1.037 1.037 0 01-1.032-1.031c0-.566.466-1.032 1.032-1.032.566 0 1.031.466 1.032 1.032 0 .566-.466 1.032-1.032 1.032zm.889 6.51h-1.78V6.498h1.78v5.727zM13.11 2H2.885A.88.88 0 002 2.866v10.268a.88.88 0 00.885.866h10.226a.882.882 0 00.889-.866V2.865a.88.88 0 00-.889-.864z">
                        </path>
                      </g>
                    </svg> </a>
                </li>

                <li>
                  <a href="https://twitter.com/ShebaPlastic" target="_blank" class="tw-text-white">
                    <svg width="32" height="32" viewBox="0 -4 48 48" version="1.1" xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
                      <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                      <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                      <g id="SVGRepo_iconCarrier">
                        <title>Twitter-color</title>
                        <desc>Created with Sketch.</desc>
                        <defs> </defs>
                        <g id="Icons" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                          <g id="Color-" transform="translate(-300.000000, -164.000000)" fill="#00AAEC">
                            <path
                              d="M348,168.735283 C346.236309,169.538462 344.337383,170.081618 342.345483,170.324305 C344.379644,169.076201 345.940482,167.097147 346.675823,164.739617 C344.771263,165.895269 342.666667,166.736006 340.418384,167.18671 C338.626519,165.224991 336.065504,164 333.231203,164 C327.796443,164 323.387216,168.521488 323.387216,174.097508 C323.387216,174.88913 323.471738,175.657638 323.640782,176.397255 C315.456242,175.975442 308.201444,171.959552 303.341433,165.843265 C302.493397,167.339834 302.008804,169.076201 302.008804,170.925244 C302.008804,174.426869 303.747139,177.518238 306.389857,179.329722 C304.778306,179.280607 303.256911,178.821235 301.9271,178.070061 L301.9271,178.194294 C301.9271,183.08848 305.322064,187.17082 309.8299,188.095341 C309.004402,188.33225 308.133826,188.450704 307.235077,188.450704 C306.601162,188.450704 305.981335,188.390033 305.381229,188.271578 C306.634971,192.28169 310.269414,195.2026 314.580032,195.280607 C311.210424,197.99061 306.961789,199.605634 302.349709,199.605634 C301.555203,199.605634 300.769149,199.559408 300,199.466956 C304.358514,202.327194 309.53689,204 315.095615,204 C333.211481,204 343.114633,188.615385 343.114633,175.270495 C343.114633,174.831347 343.106181,174.392199 343.089276,173.961719 C345.013559,172.537378 346.684275,170.760563 348,168.735283"
                              id="Twitter"> </path>
                          </g>
                        </g>
                      </g>
                    </svg>
                  </a>
                </li>

                <li>
                  <a href="https://www.instagram.com/sheba_plastic/" target="_blank" class="tw-text-white">
                    <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                      <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                      <g id="SVGRepo_iconCarrier">
                        <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint0_radial_87_7153)"></rect>
                        <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint1_radial_87_7153)"></rect>
                        <rect x="2" y="2" width="28" height="28" rx="6" fill="url(#paint2_radial_87_7153)"></rect>
                        <path
                          d="M23 10.5C23 11.3284 22.3284 12 21.5 12C20.6716 12 20 11.3284 20 10.5C20 9.67157 20.6716 9 21.5 9C22.3284 9 23 9.67157 23 10.5Z"
                          fill="white"></path>
                        <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M16 21C18.7614 21 21 18.7614 21 16C21 13.2386 18.7614 11 16 11C13.2386 11 11 13.2386 11 16C11 18.7614 13.2386 21 16 21ZM16 19C17.6569 19 19 17.6569 19 16C19 14.3431 17.6569 13 16 13C14.3431 13 13 14.3431 13 16C13 17.6569 14.3431 19 16 19Z"
                          fill="white"></path>
                        <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M6 15.6C6 12.2397 6 10.5595 6.65396 9.27606C7.2292 8.14708 8.14708 7.2292 9.27606 6.65396C10.5595 6 12.2397 6 15.6 6H16.4C19.7603 6 21.4405 6 22.7239 6.65396C23.8529 7.2292 24.7708 8.14708 25.346 9.27606C26 10.5595 26 12.2397 26 15.6V16.4C26 19.7603 26 21.4405 25.346 22.7239C24.7708 23.8529 23.8529 24.7708 22.7239 25.346C21.4405 26 19.7603 26 16.4 26H15.6C12.2397 26 10.5595 26 9.27606 25.346C8.14708 24.7708 7.2292 23.8529 6.65396 22.7239C6 21.4405 6 19.7603 6 16.4V15.6ZM15.6 8H16.4C18.1132 8 19.2777 8.00156 20.1779 8.0751C21.0548 8.14674 21.5032 8.27659 21.816 8.43597C22.5686 8.81947 23.1805 9.43139 23.564 10.184C23.7234 10.4968 23.8533 10.9452 23.9249 11.8221C23.9984 12.7223 24 13.8868 24 15.6V16.4C24 18.1132 23.9984 19.2777 23.9249 20.1779C23.8533 21.0548 23.7234 21.5032 23.564 21.816C23.1805 22.5686 22.5686 23.1805 21.816 23.564C21.5032 23.7234 21.0548 23.8533 20.1779 23.9249C19.2777 23.9984 18.1132 24 16.4 24H15.6C13.8868 24 12.7223 23.9984 11.8221 23.9249C10.9452 23.8533 10.4968 23.7234 10.184 23.564C9.43139 23.1805 8.81947 22.5686 8.43597 21.816C8.27659 21.5032 8.14674 21.0548 8.0751 20.1779C8.00156 19.2777 8 18.1132 8 16.4V15.6C8 13.8868 8.00156 12.7223 8.0751 11.8221C8.14674 10.9452 8.27659 10.4968 8.43597 10.184C8.81947 9.43139 9.43139 8.81947 10.184 8.43597C10.4968 8.27659 10.9452 8.14674 11.8221 8.0751C12.7223 8.00156 13.8868 8 15.6 8Z"
                          fill="white"></path>
                        <defs>
                          <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                            gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                            <stop stop-color="#B13589"></stop>
                            <stop offset="0.79309" stop-color="#C62F94"></stop>
                            <stop offset="1" stop-color="#8A3AC8"></stop>
                          </radialGradient>
                          <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                            gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                            <stop stop-color="#E0E8B7"></stop>
                            <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                            <stop offset="0.71474" stop-color="#E2425C"></stop>
                            <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                          </radialGradient>
                          <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                            gradientTransform="translate(0.500002 3) rotate(-8.1301) scale(38.8909 8.31836)">
                            <stop offset="0.156701" stop-color="#406ADC"></stop>
                            <stop offset="0.467799" stop-color="#6A45BE"></stop>
                            <stop offset="1" stop-color="#6A45BE" stop-opacity="0"></stop>
                          </radialGradient>
                        </defs>
                      </g>
                    </svg>
                  </a>
                </li>

                <!--  <li>
                <a href="#" class="tw-text-white">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor"
                    class="bi bi-facebook" viewBox="0 0 16 16" id="IconChangeColor">
                    <path
                      d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"
                      id="mainIconPathAttribute" fill="#ffffff" filter="url(#shadow)"></path>
                    <filter id="shadow">
                      <feDropShadow id="shadowValue" stdDeviation=".5" dx="0" dy="0" flood-color="black">
                      </feDropShadow>
                    </filter>
                  </svg>
                </a>
              </li>
 -->

              </ul>
            </div>
          </v-col>
        </v-row>

          
        <v-divider class="tw-my-4 tw-text-white tw-bg-white"></v-divider>
        <div class="tw-text-center tw-text-white">
          <p>&copy; 2023 JumbaSoft. All rights reserved</p>
        </div>



      </div>
    </footer>

    <div style="display:none">
      <svg id="dots-triangle" width="170" height="170" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M168.152 170a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm-18.478-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm-18.478 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.479a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm-18.479 0a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zM94.24 133.043a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm-18.478 36.956a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm-18.478 55.434a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.479a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm-18.479 73.913a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.479a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm-18.478 92.391a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0 18.479a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.479a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM1.848 133.044a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.695zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0 18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-55.435a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.479a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.695 1.848 1.848 0 0 1 0 3.695zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm0-18.478a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696z"
          fill="#2C8056" fill-rule="evenodd" opacity=".503" />
      </svg>
    </div>
  </div>
</template>

<script>
import Popup from "@/components/Popup";

export default {
  components: {
    Popup,
  },

  mounted() {
    this.showDialog = true;
  },
  data() {
    return {
      isOpen: false,
      showDialog: false,
      theme: 'theme-light'
    };
  },
  methods: {
    toggleMenu() {
      this.isOpen = !this.isOpen;
    },
    closeMenu() {
      this.isOpen = false;
    },

  }

}

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans&family=Poppins&display=swap');

footer {
  background-image: url(https://img.freepik.com/premium-photo/ambitious-business-man-climbing-stairs-success_31965-3080.jpg?w=740);
  background-size: cover;
}

button {
  border: 0.5px solid orangered;
}

.text-color {
  color: orangered;
}

button:hover {
  border: none;
}

.font-sans {
  font-family: 'Josefin Sans', sans-serif;
  font-family: 'Poppins', sans-serif;
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
