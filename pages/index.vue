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
        <div class="lg:tw-w-3/4">
          <h1 class="lg:tw-text-6xl text-color tw-text-4xl tw-font-extrabold" data-aos="fade-up">
            Who we are?
          </h1>
          <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">


          <p class="tw-mt-4 tw-text-justify" data-aos="fade-up">


            <span class="tw-text-justify  tw-mb-4">
              JumbaSoft is an innovative organization that focuses on empowering businesses with advanced digital
              marketing strategies and revolutionary web development solutions. We are dedicated to delivering measurable
              and impactful results, helping our valued clients exceed their goals in the ever-changing digital landscape.
            </span>
            <br>
            <br>
            <span class="tw-mt-3 tw-text-justify">
              JumbaSoft combines cutting-edge technology with extensive industry knowledge to deliver customized and
              innovative solutions that address the specific requirements of every client.
            </span>
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
      <div class="tw-max-w-7xl tw-mx-auto tw-px-4 tw-sm:px-6 lg:tw-px-8">
        <div class="tw-lg:text-center">

          <h1 class="tw-mt-2 lg:tw-text-6xl tw-text-4xl tw-leading-8 tw-font-extrabold text-color" data-aos="fade-up">
            Our Team
          </h1>
          <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">
        </div>

        <div class="tw-mt-10">
          <div class="tw-mt-5 tw-grid tw-grid-cols-1 tw-gap-5 sm:tw-grid-cols-2 lg:tw-grid-cols-3">

            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/joeltassiga.jpeg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
                  Massama-Joel TASSIGA
                </h3>
                <div>
                  <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">Founder and CEO</p>
                  <p class="tw-mt-1 tw-text-justify tw-text-sm tw-text-gray-900">
                    Massama Massama-Joel TASSIGA is a versatile digital marketer and web developer with a diverse skill
                    set. Alongside my expertise in web development, I have a talent for event planning and possess strong
                    critical thinking abilities. I have experience in front-end development, as well as
                    utilizing MS Excel and PowerPoint for data analysis and presentations.
                  </p>
                  <div class="tw-flex tw-justify-center tw-space-x-4 tw-mt-4">

                    <ul class="tw-flex tw-items-center tw-gap-4">
                      <li>
                        <a href="https://www.linkedin.com/in/massama-joel-tassiga-04954ab8/" target="_blank"
                          class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
                        <a href="https://twitter.com/JTassiga" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                            xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
                        <a href="https://www.instagram.com/joeltassigagram/" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                                <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                                  <stop stop-color="#B13589"></stop>
                                  <stop offset="0.79309" stop-color="#C62F94"></stop>
                                  <stop offset="1" stop-color="#8A3AC8"></stop>
                                </radialGradient>
                                <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                                  <stop stop-color="#E0E8B7"></stop>
                                  <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                                  <stop offset="0.71474" stop-color="#E2425C"></stop>
                                  <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                                </radialGradient>
                                <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
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

                    </ul>
                  </div>
                </div>
              </div>
            </div>


            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/sergetassiga.jpg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
                  Serge TASSIGA
                </h3>
                <div>
                  <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">CTO</p>
                  <p class="tw-mt-1 tw-text-justify tw-text-sm tw-text-gray-900">
                    Serge Tassiga is a talented Frontend Developer with a strong background in creating visually appealing
                    and user-friendly web applications. I have extensive expertise in HTML, CSS, JavaScript, NuxtJs,
                    TailwindCSS, and Vuetify. With these skills, I can design responsive websites that effortlessly adapt
                    to different screen sizes.
                  </p>
                  <div class="tw-flex tw-justify-center tw-gap-8 tw-mt-4">

                    <ul class="tw-flex tw-items-center tw-gap-4">
                      <li>
                        <a href="https://www.linkedin.com/in/serge-anan-tassiga-759b6b190/" target="_blank"
                          class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
                        <a href="https://twitter.com/STassiga" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                            xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
                        <a href="https://www.instagram.com/__iamsergeo/" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                                <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                                  <stop stop-color="#B13589"></stop>
                                  <stop offset="0.79309" stop-color="#C62F94"></stop>
                                  <stop offset="1" stop-color="#8A3AC8"></stop>
                                </radialGradient>
                                <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                                  <stop stop-color="#E0E8B7"></stop>
                                  <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                                  <stop offset="0.71474" stop-color="#E2425C"></stop>
                                  <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                                </radialGradient>
                                <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
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

                    </ul>
                  </div>
                </div>
              </div>
            </div>

            <div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
              <div class="tw-px-4 tw-py-5 tw-sm:p-6">
                <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/Blaise-Pascal AGBETSOMEDO.jpg" alt="">
                <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
                  Blaise Pascal AGBETSOMEDO
                </h3>
                <div>
                  <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">Business development and Marketing enthusiast</p>
                  <p class="tw-mt-1 tw-text-sm tw-text-gray-900 tw-text-justify">
                    Blaise Pascal is an accomplished logistics professional known for my expertise in managing On
                    Board Computer systems. With a BA (Hons) He is pursuing actually as a degree in International Business
                    and Trade, He combines theoretical knowledge with practical application.
                  </p>
                  <div class="tw-flex tw-justify-center tw-space-x-4 tw-mt-4">
                    <ul class="tw-flex tw-items-center tw-gap-4">
                      <li>
                        <a href="https://www.linkedin.com/in/blaise-pascal-agbetsomedo-1b9306203/" target="_blank"
                          class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
                        <a href="https://twitter.com/BAgbetsomedo" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                            xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
                        <a href="https://www.instagram.com/blaisepascalagbetsomedo/" target="_blank" class="tw-text-white">
                          <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                                <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                                  <stop stop-color="#B13589"></stop>
                                  <stop offset="0.79309" stop-color="#C62F94"></stop>
                                  <stop offset="1" stop-color="#8A3AC8"></stop>
                                </radialGradient>
                                <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
                                  gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                                  <stop stop-color="#E0E8B7"></stop>
                                  <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                                  <stop offset="0.71474" stop-color="#E2425C"></stop>
                                  <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                                </radialGradient>
                                <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                                  gradientUnits="userSpaceOnUse"
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


                    </ul>
                  </div>
                </div>
              </div>
            </div>

            <!-- Add more team members here -->


            

          </div>

          
        </div>

        <div class="tw-mt-5 tw-grid tw-grid-cols-1 tw-gap-5 sm:tw-grid-cols-2 lg:tw-grid-cols-3">

<div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
  <div class="tw-px-4 tw-py-5 tw-sm:p-6">
    <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/joeltassiga.jpeg" alt="">
    <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
      Massama-Joel TASSIGA
    </h3>
    <div>
      <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">Founder and CEO</p>
      <p class="tw-mt-1 tw-text-justify tw-text-sm tw-text-gray-900">
        Massama Massama-Joel TASSIGA is a versatile digital marketer and web developer with a diverse skill
        set. Alongside my expertise in web development, I have a talent for event planning and possess strong
        critical thinking abilities. I have experience in front-end development, as well as
        utilizing MS Excel and PowerPoint for data analysis and presentations.
      </p>
      <div class="tw-flex tw-justify-center tw-space-x-4 tw-mt-4">

        <ul class="tw-flex tw-items-center tw-gap-4">
          <li>
            <a href="https://www.linkedin.com/in/massama-joel-tassiga-04954ab8/" target="_blank"
              class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
            <a href="https://twitter.com/JTassiga" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
            <a href="https://www.instagram.com/joeltassigagram/" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                    <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                      <stop stop-color="#B13589"></stop>
                      <stop offset="0.79309" stop-color="#C62F94"></stop>
                      <stop offset="1" stop-color="#8A3AC8"></stop>
                    </radialGradient>
                    <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                      <stop stop-color="#E0E8B7"></stop>
                      <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                      <stop offset="0.71474" stop-color="#E2425C"></stop>
                      <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                    </radialGradient>
                    <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
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

        </ul>
      </div>
    </div>
  </div>
</div>


<div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
  <div class="tw-px-4 tw-py-5 tw-sm:p-6">
    <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/sergetassiga.jpg" alt="">
    <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
      Serge TASSIGA
    </h3>
    <div>
      <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">CTO</p>
      <p class="tw-mt-1 tw-text-justify tw-text-sm tw-text-gray-900">
        Serge Tassiga is a talented Frontend Developer with a strong background in creating visually appealing
        and user-friendly web applications. I have extensive expertise in HTML, CSS, JavaScript, NuxtJs,
        TailwindCSS, and Vuetify. With these skills, I can design responsive websites that effortlessly adapt
        to different screen sizes.
      </p>
      <div class="tw-flex tw-justify-center tw-gap-8 tw-mt-4">

        <ul class="tw-flex tw-items-center tw-gap-4">
          <li>
            <a href="https://www.linkedin.com/in/serge-anan-tassiga-759b6b190/" target="_blank"
              class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
            <a href="https://twitter.com/STassiga" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
            <a href="https://www.instagram.com/__iamsergeo/" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                    <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                      <stop stop-color="#B13589"></stop>
                      <stop offset="0.79309" stop-color="#C62F94"></stop>
                      <stop offset="1" stop-color="#8A3AC8"></stop>
                    </radialGradient>
                    <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                      <stop stop-color="#E0E8B7"></stop>
                      <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                      <stop offset="0.71474" stop-color="#E2425C"></stop>
                      <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                    </radialGradient>
                    <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
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

        </ul>
      </div>
    </div>
  </div>
</div>

<div class="tw-bg-white tw-overflow-hidden tw-shadow tw-rounded-lg">
  <div class="tw-px-4 tw-py-5 tw-sm:p-6">
    <img class="tw-mx-auto tw-h-48 tw-w-48 tw-rounded-full" src="../assets/Blaise-Pascal AGBETSOMEDO.jpg" alt="">
    <h3 class="tw-mt-6 tw-text-center tw-font-extrabold tw-text-xl tw-text-black">
      Blaise Pascal AGBETSOMEDO
    </h3>
    <div>
      <p class="tw-mt-2 tw-text-center tw-text-md tw-font-bold text-color">Business development and Marketing enthusiast</p>
      <p class="tw-mt-1 tw-text-sm tw-text-gray-900 tw-text-justify">
        Blaise Pascal is an accomplished logistics professional known for my expertise in managing On
        Board Computer systems. With a BA (Hons) He is pursuing actually as a degree in International Business
        and Trade, He combines theoretical knowledge with practical application.
      </p>
      <div class="tw-flex tw-justify-center tw-space-x-4 tw-mt-4">
        <ul class="tw-flex tw-items-center tw-gap-4">
          <li>
            <a href="https://www.linkedin.com/in/blaise-pascal-agbetsomedo-1b9306203/" target="_blank"
              class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg" fill="none">
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
            <a href="https://twitter.com/BAgbetsomedo" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 -4 48 48" version="1.1"
                xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000">
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
            <a href="https://www.instagram.com/blaisepascalagbetsomedo/" target="_blank" class="tw-text-white">
              <svg width="24" height="24" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
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
                    <radialGradient id="paint0_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(12 23) rotate(-55.3758) scale(25.5196)">
                      <stop stop-color="#B13589"></stop>
                      <stop offset="0.79309" stop-color="#C62F94"></stop>
                      <stop offset="1" stop-color="#8A3AC8"></stop>
                    </radialGradient>
                    <radialGradient id="paint1_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
                      gradientTransform="translate(11 31) rotate(-65.1363) scale(22.5942)">
                      <stop stop-color="#E0E8B7"></stop>
                      <stop offset="0.444662" stop-color="#FB8A2E"></stop>
                      <stop offset="0.71474" stop-color="#E2425C"></stop>
                      <stop offset="1" stop-color="#E2425C" stop-opacity="0"></stop>
                    </radialGradient>
                    <radialGradient id="paint2_radial_87_7153" cx="0" cy="0" r="1"
                      gradientUnits="userSpaceOnUse"
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


        </ul>
      </div>
    </div>
  </div>
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
          "Unlock the power of digital growth with JumbaSoft - Where creativity meets strategy, and results meet success."
        </h1>
      </div>
      <!-- end hero -->
      <!-- end hero -->



    </section>


    <section class="tw-bg-white lg:tw-p-12 pt-0 tw-pb-12 tw-px-8 tw-py-8 tw-mb-4">

      <div class="tw-px-6 tw-mb-8">
        <h1 class="tw-mt-2 tw-mb-2 lg:tw-text-6xl tw-text-4xl tw-font-extrabold text-color" data-aos="fade-up">
          Why JumbaSoft?
        </h1>
        <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">


      </div>


      <div class="lg:tw-p-8">
        <div class="tw-grid lg:tw-grid-cols-3 tw-gap-8 tw-py-12">

          <div class="tw-shadow-2xl tw-p-4 tw-rounded tw-shadow-orange-600">
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
              <span class="tw-text-lg tw-font-bold text-color">Expertise and Experience</span>
              <span>We boasts a team of highly skilled professionals with extensive expertise in marketing.</span>
            </p>
          </div>


          <div class="tw-shadow-2xl tw-p-4 tw-rounded tw-shadow-orange-600">
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
              <span class="tw-text-lg tw-font-bold text-color">Innovative Solutions</span>
              <span>We thrive on innovation and stay up-to-date with the latest marketing trends, technologies, and
                strategies</span>
            </p>

          </div>

          <div class="tw-shadow-2xl tw-p-4 tw-rounded tw-shadow-orange-600">
            <svg class="tw-rounded-full tw-bg-gray-200 tw-p-3" width="50" version="1.1" id="Uploaded to svgrepo.com"
              xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 32 32"
              xml:space="preserve" fill="#000000">
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
              <g id="SVGRepo_iconCarrier">
                <style type="text/css">
                  .puchipuchi_een {
                    fill: #111918;
                  }
                </style>
                <path class="puchipuchi_een"
                  d="M21,24c0,0.552-0.447,1-1,1h-8c-0.553,0-1-0.448-1-1s0.447-1,1-1h8C20.553,23,21,23.448,21,24z M20,26h-8c-0.553,0-1,0.448-1,1s0.447,1,1,1h8c0.553,0,1-0.448,1-1S20.553,26,20,26z M15,29v1c0,0.552,0.448,1,1,1s1-0.448,1-1v-1 H15z M26,11c0,5-5,8-5,10c0,0.552-0.448,1-1,1h-8c-0.552,0-1-0.448-1-1c0-2-5-5-5-10C6,5.477,10.477,1,16,1S26,5.477,26,11z M17,4 c0-0.552-0.447-1-1-1c-4.411,0-8,3.589-8,8c0,0.552,0.447,1,1,1s1-0.448,1-1c0-3.309,2.691-6,6-6C16.553,5,17,4.552,17,4z">
                </path>
              </g>
            </svg>
            <p class="tw-flex tw-flex-col">
              <span class="tw-text-lg tw-font-bold text-color">Results-Oriented Focus</span>
              <span>Our ultimate goal at JumbaSoft is to drive measurable results for our clients.</span>
            </p>

          </div>

        </div>

      </div>

      <div class="tw-items-center tw-gap-4 lg:tw-p-6 tw-p-6 tw-mt-4">
        <h1 class="lg:tw-text-6xl text-color tw-text-3xl tw-font-extrabold" data-aos="fade-up">
          What We Stand For?
        </h1>
        <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">
      </div>

      <div
        class="tw-flex tw-flex-col lg:tw-flex-row tw-gap-6 lg:tw-gap-8 md:tw-gap-8 tw-container lg:tw-p-8 tw-p-4 lg:tw-justify-center tw-items-center tw-w-full">

        <div
          class="tw-flex tw-shadow-2xl tw-shadow-orange-600 tw-rounded-lg tw-bg-white tw-block tw-p-6  tw-cursor-pointer tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class="tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/goal.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold tw-mb-2 text-color">Our Goal</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-justify tw-text-center tw-max-w-sm">
            Our goal is to empower businesses through our expertise in digital marketing strategies and web development
            solutions. We are committed to delivering measurable results, allowing our clients to exceed their objectives
            in an ever-evolving digital environment. Our ultimate aim is to establish ourselves as the trusted partner of
            choice, supporting businesses in their growth and success.
          </p>
        </div>

        <div
          class="tw-flex tw-shadow-2xl tw-shadow-orange-600 tw-rounded-lg tw-bg-white tw-block tw-cursor-pointer tw-p-6  tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class=" tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/mission.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold text-color tw-mb-2">Our Mission</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-center tw-max-w-sm tw-text-justify">
            At JumbaSoft, our mission is to empower businesses with cutting-edge digital marketing strategies and
            groundbreaking web development solutions. We are relentless in our dedication to delivering tangible and
            quantifiable outcomes, enabling our esteemed clients to surpass their objectives within the dynamic and
            ever-transforming digital domain.
          </p>
        </div>
        <!-- Vision -->
        <div
          class="tw-flex tw-shadow-2xl tw-shadow-orange-600 tw-rounded-lg tw-bg-white tw-block tw-cursor-pointer tw-p-6 tw-flex-col tw-items-center tw-justify-center lg:tw-w-1/3"
          data-aos="fade-up">
          <div class=" tw-p-3 tw-mb-2">
            <img class="" width="600" src="../assets/vision.png">
          </div>
          <h3 class="tw-text-xl tw-font-extrabold text-color tw-mb-2">Our Vision</h3>
          <p class="tw-text-sm tw-font-medium tw-text-black tw-text-center tw-max-w-sm tw-text-justify">
            Our unwavering vision is to become the unwavering ally and preferred partner for businesses, propelling their
            triumphs and expansion. We aim to achieve this by leveraging our profound expertise, unyielding determination,
            and ethical approach. By consistently providing exceptional services, we aspire to be the go-to choice for
            businesses seeking to thrive in the digital landscape.
          </p>
        </div>
      </div>


    </section>


    <section class="tw-w-full tw-h-full lg:tw-p-8 lg:tw-pb-12 tw-p-4">

      <div class="tw-px-6">
        <h1 class=" lg:tw-text-6xl tw-text-4xl tw-font-extrabold text-color" data-aos="fade-up">
          Our Services
        </h1>
        <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">
      </div>


      <div class="lg:tw-pb-12 tw-pt-8 tw-grid lg:tw-grid-cols-4 tw-gap-4 lg:tw-gap-0 tw-w-full tw-h-full">

        <div class=" tw-h-full tw-bg-white tw-block tw-cursor-pointer tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
              src="https://img.freepik.com/free-photo/corporate-management-strategy-solution-branding-concept_53876-167088.jpg?w=740&t=st=1687374457~exp=1687375057~hmac=dcdd2d0abfa37541021572261996114f825321a316f3a7161f378fb786d9ea0e"
              alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-2xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Digital Marketing</h1>
            </div>
          </div>

        </div>

        <div class="tw-cursor-pointer tw-bg-white tw-block tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
              src="https://img.freepik.com/premium-photo/graphic-design-studio_72104-935.jpg?w=740" alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-2xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Graphic Design</h1>
            </div>
          </div>


        </div>

        <div class="tw-cursor-pointer tw-bg-white tw-block tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover"
              src="https://img.freepik.com/premium-psd/four-app-ui-mockup-top-angle-view_173079-442.jpg?w=740"
              alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-2xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">UX/UI Design</h1>
            </div>
          </div>


        </div>

        <div class="tw-cursor-pointer tw-bg-white tw-block tw-w-full tw-shadow-sm tw-shadow-indigo-100">
          <div
            class="tw-relative tw-overflow-hidden tw-bg-cover tw-bg-no-repeat tw-w-full tw-h-96 hover:tw-shadow-orange-700 hover:tw-shadow-xl hover:tw-border-b-14 hover:tw-border-orange-700 hover:tw-ease-out  hover:tw-transition-all hover:tw-rounded">
            <img
              class="tw-absolute tw-top-0 tw-left-0 tw-w-full tw-h-full tw-object-cover hover:tw-transition hover:tw-duration-300 hover:tw-ease-in-out hover:tw-scale-110"
              src="https://img.freepik.com/premium-photo/programming-background-with-person-working-with-codes-computer_23-2150010150.jpg?w=740"
              alt="Banner Image">
            <div
              class="tw-relative tw-w-full tw-h-full tw-flex tw-flex-col tw-justify-end tw-items-center tw-bg-gray-900 tw-bg-opacity-30">
              <h1 class="tw-text-2xl tw-font-bold tw-text-white tw-py-4" data-aos="fade-up">Web Development</h1>
            </div>
          </div>


        </div>
      </div>

    </section>





    <section class="tw-bg-white lg:tw-p-12 tw-pb-12 tw-px-4 tw-py-8 tw-mb-4">

      <div class="tw-px-6 tw-mb-4 ">
        <h1 class=" lg:tw-text-6xl tw-text-4xl tw-font-extrabold text-color" data-aos="fade-up">
          Careers
        </h1>
        <hr class="lg:tw-w-48 tw-w-24 tw-h-2 bg-color tw-my-2" data-aos="fade-up">
      </div>

      <div class="tw-flex tw-flex-col lg:tw-flex-row lg:tw-p-8">

        <v-img class="tw-rounded-lg tw-shadow-2xl tw-shadow-white tw-cursor-pointer"
          src="https://img.freepik.com/free-photo/portrait-handsome-african-black-young-business-man-working-laptop-office-desk_231208-680.jpg?w=740&t=st=1687375475~exp=1687376075~hmac=a89af287fe8ff84fb41aab7f82eda270a361de7c2fe007dcdbfa76ff15e07f3d"
          width="500px"></v-img>


        <div class="tw-p-4 lg:tw-pt-0 lg:tw-mx-12">
          <h1 class=" lg:tw-text-4xl tw-mb-4 tw-text-3xl tw-font-extrabold tw-text-black" data-aos="fade-up">
            Transform Your Professional Journey!

          </h1>


          <span class="tw-mt-12 tw-text-justify" data-aos="fade-up">
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
