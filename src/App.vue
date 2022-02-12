<template>
  <div id="app" class="">
    <div class="header-cover static" v-if="visible">
        <div class="relative w-full bg-no-repeat bg-cover lg:bg-center sm:bg-center bg__height" v-bind:style="{ backgroundImage:'url(' + imgPath2 + ')' }" v-if="visible">
            <div class="absolute bottom-36 right-0 left-0 mx-auto sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-center">
                 <h2 class="text-center sm:text-4xl text-[#fff]">
                    <span class="block judul">The Wedding Of</span>
                    <span class="block py-2 waterfall">Yulia & Andri</span>
                </h2>
            </div>
            <div class="absolute -bottom-5 right-0 left-0  back_waves">
              <svg class="w-full" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#2A2C21"/>
              </svg>
            </div>
        </div>
      <section class="relative w-full h-screen bg-satu">
          <div class="py-20">
            <div class="mx-auto mb-3">
              <img src="@/assets/logo1.png" alt="" class="mx-auto w-1/4 col-span-2" srcset="">
              <h2 class="text-center sm:text-4xl text-[#fff]">
                    <span class="block waterfall_satu">We Tied The Knot!</span>
                    <p class="text-xl mt-3 heading-5">Kami hanya ingin menghabiskan Tiga Waktu Bersama, Sekarang, Selalu dan Selamanya.</p>
              </h2>
            </div>
            <img  data-aos="zoom-in"  src="@/assets/bag-3.jpg" class="lg:w-3/12 lg:h-4/5 sm:w-1/2 bg-cover bg-no-repeat mx-auto rounded-3xl border-4 border-white shadow-lg" alt="" srcset="">
          </div>
      <svg class="w-full absolute -bottom-4 right-0 left-0" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#CAD1C2"/>
      </svg>
      </section>

      <section class="w-full h-44 bg-dua">
          <div class="p-16">
              <h2 class="text-center sm:text-4xl text-[#fff] ">
                    <span class="nama__font_satu"  data-aos="zoom-in" data-aos-delay="600">Kedua Mempelai</span>
              </h2>
          </div>
      </section>
      <svg class="w-full absolute right-0 left-0" viewBox="0 0 221 8" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M55.25 1.8C27.625 1.8 13.8125 3.15 0 4.5V0H221V4.5C207.188 5.85 193.375 7.2 165.75 7.2C110.5 7.2 110.5 1.8 55.25 1.8Z" fill="#CAD1C2"/>
      </svg>

      <section class="w-full h-screen bg-tiga">
          <div class="p-16">
                <div class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4">
                  <div class="flex flex-col w-5/6 lg:w-2/5 mx-auto lg:mx-0 rounded-none lg:rounded-l-lg mt-9">
                      <h2 class="text-center sm:text-4xl text-[#fff] " data-aos="zoom-in" data-aos-delay="600">
                            <span class="nama__font_satu">Ellyas Mozart Zulkarnaen Situmorang, S.H., M.H.</span>
                            <p class="text-sm text-gray-800 leading-7 tracking-widest">Putra ke Enam dari <br>
                                Alm. Bapak P.S. Situmorang, S.H. dan Ibu M. Pangaribuan <br>
                                Palembang, Sumatera Selatan
                            </p>
                        <div class="p-4">
                          <button class="px-3 py-3 bg-gray-800 rounded-lg">
                            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                              <path fill-rule="evenodd" clip-rule="evenodd" d="M7.465 1.066C8.638 1.012 9.012 1 12 1C14.988 1 15.362 1.013 16.534 1.066C17.706 1.119 18.506 1.306 19.206 1.577C19.939 1.854 20.604 2.287 21.154 2.847C21.714 3.396 22.146 4.06 22.422 4.794C22.694 5.494 22.88 6.294 22.934 7.464C22.988 8.639 23 9.013 23 12C23 14.988 22.987 15.362 22.934 16.535C22.881 17.705 22.694 18.505 22.422 19.205C22.146 19.9391 21.7133 20.6042 21.154 21.154C20.604 21.714 19.939 22.146 19.206 22.422C18.506 22.694 17.706 22.88 16.536 22.934C15.362 22.988 14.988 23 12 23C9.012 23 8.638 22.987 7.465 22.934C6.295 22.881 5.495 22.694 4.795 22.422C4.06092 22.146 3.39582 21.7133 2.846 21.154C2.28638 20.6047 1.85331 19.9399 1.577 19.206C1.306 18.506 1.12 17.706 1.066 16.536C1.012 15.361 1 14.987 1 12C1 9.012 1.013 8.638 1.066 7.466C1.119 6.294 1.306 5.494 1.577 4.794C1.85372 4.06008 2.28712 3.39531 2.847 2.846C3.39604 2.2865 4.06047 1.85344 4.794 1.577C5.494 1.306 6.294 1.12 7.464 1.066H7.465ZM16.445 3.046C15.285 2.993 14.937 2.982 12 2.982C9.063 2.982 8.715 2.993 7.555 3.046C6.482 3.095 5.9 3.274 5.512 3.425C4.999 3.625 4.632 3.862 4.247 4.247C3.88205 4.60205 3.60118 5.03428 3.425 5.512C3.274 5.9 3.095 6.482 3.046 7.555C2.993 8.715 2.982 9.063 2.982 12C2.982 14.937 2.993 15.285 3.046 16.445C3.095 17.518 3.274 18.1 3.425 18.488C3.601 18.965 3.882 19.398 4.247 19.753C4.602 20.118 5.035 20.399 5.512 20.575C5.9 20.726 6.482 20.905 7.555 20.954C8.715 21.007 9.062 21.018 12 21.018C14.938 21.018 15.285 21.007 16.445 20.954C17.518 20.905 18.1 20.726 18.488 20.575C19.001 20.375 19.368 20.138 19.753 19.753C20.118 19.398 20.399 18.965 20.575 18.488C20.726 18.1 20.905 17.518 20.954 16.445C21.007 15.285 21.018 14.937 21.018 12C21.018 9.063 21.007 8.715 20.954 7.555C20.905 6.482 20.726 5.9 20.575 5.512C20.375 4.999 20.138 4.632 19.753 4.247C19.3979 3.88207 18.9657 3.60121 18.488 3.425C18.1 3.274 17.518 3.095 16.445 3.046V3.046ZM10.595 15.391C11.3797 15.7176 12.2534 15.7617 13.0669 15.5157C13.8805 15.2697 14.5834 14.7489 15.0556 14.0422C15.5278 13.3356 15.7401 12.4869 15.656 11.6411C15.572 10.7953 15.197 10.005 14.595 9.405C14.2112 9.02148 13.7472 8.72781 13.2363 8.54515C12.7255 8.36248 12.1804 8.29536 11.6405 8.34862C11.1006 8.40187 10.5792 8.57418 10.1138 8.85313C9.64846 9.13208 9.25074 9.51074 8.9493 9.96185C8.64786 10.413 8.45019 10.9253 8.37052 11.462C8.29084 11.9986 8.33115 12.5463 8.48854 13.0655C8.64593 13.5847 8.91648 14.0626 9.28072 14.4647C9.64496 14.8668 10.0938 15.1832 10.595 15.391ZM8.002 8.002C8.52702 7.47698 9.15032 7.0605 9.8363 6.77636C10.5223 6.49222 11.2575 6.34597 12 6.34597C12.7425 6.34597 13.4777 6.49222 14.1637 6.77636C14.8497 7.0605 15.473 7.47698 15.998 8.002C16.523 8.52702 16.9395 9.15032 17.2236 9.8363C17.5078 10.5223 17.654 11.2575 17.654 12C17.654 12.7425 17.5078 13.4777 17.2236 14.1637C16.9395 14.8497 16.523 15.473 15.998 15.998C14.9377 17.0583 13.4995 17.654 12 17.654C10.5005 17.654 9.06234 17.0583 8.002 15.998C6.94166 14.9377 6.34597 13.4995 6.34597 12C6.34597 10.5005 6.94166 9.06234 8.002 8.002V8.002ZM18.908 7.188C19.0381 7.06527 19.1423 6.91768 19.2143 6.75397C19.2863 6.59027 19.3248 6.41377 19.3274 6.23493C19.33 6.05609 19.2967 5.87855 19.2295 5.71281C19.1622 5.54707 19.0624 5.39651 18.936 5.27004C18.8095 5.14357 18.6589 5.04376 18.4932 4.97652C18.3275 4.90928 18.1499 4.87598 17.9711 4.87858C17.7922 4.88119 17.6157 4.91965 17.452 4.9917C17.2883 5.06374 17.1407 5.1679 17.018 5.298C16.7793 5.55103 16.6486 5.88712 16.6537 6.23493C16.6588 6.58274 16.7992 6.91488 17.0452 7.16084C17.2911 7.40681 17.6233 7.54723 17.9711 7.5523C18.3189 7.55737 18.655 7.42669 18.908 7.188V7.188Z" fill="#F8F8F8"/>
                            </svg>

                          </button>
                        </div>
                      </h2>
                  </div>
                  <div class="flex flex-col w-5/6 lg:w-1/4 mx-auto lg:mx-0 rounded-none lg:rounded-l-lg ">
                      <img src="@/assets/bag-3.jpg" class="bg-cover bg-no-repeat mx-auto gambar-bulat" alt="" srcset="" data-aos="zoom-in" data-aos-delay="900">
                  </div>
                </div>
          </div>
      </section>
      <section class="w-full h-screen bg-dua relative">
      <svg class="w-full absolute -top-16 right-0 left-0" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#CAD1C2"/>
      </svg>
           <div class="p-16">
                <div class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4">
                  <div class="flex flex-col w-5/6 lg:w-1/4 mx-auto lg:mx-0 rounded-none lg:rounded-l-lg ">
                    <img src="@/assets/bag-3.jpg" class="bg-cover bg-no-repeat mx-auto gambar-bulat" alt="" srcset="" data-aos="zoom-in" data-aos-delay="800">
                  </div>
                  <div class="flex flex-col w-5/6 lg:w-2/5 mx-auto lg:mx-0 rounded-none lg:rounded-l-lg mt-9">
                      <h2 class="text-center sm:text-4xl text-[#fff] " data-aos="zoom-in" data-aos-delay="600">
                            <span class="nama__font_satu">Deasy Natalina Sitorus, A.Md</span>
                            <p class="text-sm text-gray-800 leading-7 tracking-widest">Putri Sulung dari <br>
                                Alm. Bapak W. Sitorus dan Ibu J. Samosir <br>
                                Pancoran, Jakarta Selatan
                            </p>
                        <div class="p-4">
                          <button class="px-3 py-3 bg-gray-800 rounded-lg">
                            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                              <path fill-rule="evenodd" clip-rule="evenodd" d="M7.465 1.066C8.638 1.012 9.012 1 12 1C14.988 1 15.362 1.013 16.534 1.066C17.706 1.119 18.506 1.306 19.206 1.577C19.939 1.854 20.604 2.287 21.154 2.847C21.714 3.396 22.146 4.06 22.422 4.794C22.694 5.494 22.88 6.294 22.934 7.464C22.988 8.639 23 9.013 23 12C23 14.988 22.987 15.362 22.934 16.535C22.881 17.705 22.694 18.505 22.422 19.205C22.146 19.9391 21.7133 20.6042 21.154 21.154C20.604 21.714 19.939 22.146 19.206 22.422C18.506 22.694 17.706 22.88 16.536 22.934C15.362 22.988 14.988 23 12 23C9.012 23 8.638 22.987 7.465 22.934C6.295 22.881 5.495 22.694 4.795 22.422C4.06092 22.146 3.39582 21.7133 2.846 21.154C2.28638 20.6047 1.85331 19.9399 1.577 19.206C1.306 18.506 1.12 17.706 1.066 16.536C1.012 15.361 1 14.987 1 12C1 9.012 1.013 8.638 1.066 7.466C1.119 6.294 1.306 5.494 1.577 4.794C1.85372 4.06008 2.28712 3.39531 2.847 2.846C3.39604 2.2865 4.06047 1.85344 4.794 1.577C5.494 1.306 6.294 1.12 7.464 1.066H7.465ZM16.445 3.046C15.285 2.993 14.937 2.982 12 2.982C9.063 2.982 8.715 2.993 7.555 3.046C6.482 3.095 5.9 3.274 5.512 3.425C4.999 3.625 4.632 3.862 4.247 4.247C3.88205 4.60205 3.60118 5.03428 3.425 5.512C3.274 5.9 3.095 6.482 3.046 7.555C2.993 8.715 2.982 9.063 2.982 12C2.982 14.937 2.993 15.285 3.046 16.445C3.095 17.518 3.274 18.1 3.425 18.488C3.601 18.965 3.882 19.398 4.247 19.753C4.602 20.118 5.035 20.399 5.512 20.575C5.9 20.726 6.482 20.905 7.555 20.954C8.715 21.007 9.062 21.018 12 21.018C14.938 21.018 15.285 21.007 16.445 20.954C17.518 20.905 18.1 20.726 18.488 20.575C19.001 20.375 19.368 20.138 19.753 19.753C20.118 19.398 20.399 18.965 20.575 18.488C20.726 18.1 20.905 17.518 20.954 16.445C21.007 15.285 21.018 14.937 21.018 12C21.018 9.063 21.007 8.715 20.954 7.555C20.905 6.482 20.726 5.9 20.575 5.512C20.375 4.999 20.138 4.632 19.753 4.247C19.3979 3.88207 18.9657 3.60121 18.488 3.425C18.1 3.274 17.518 3.095 16.445 3.046V3.046ZM10.595 15.391C11.3797 15.7176 12.2534 15.7617 13.0669 15.5157C13.8805 15.2697 14.5834 14.7489 15.0556 14.0422C15.5278 13.3356 15.7401 12.4869 15.656 11.6411C15.572 10.7953 15.197 10.005 14.595 9.405C14.2112 9.02148 13.7472 8.72781 13.2363 8.54515C12.7255 8.36248 12.1804 8.29536 11.6405 8.34862C11.1006 8.40187 10.5792 8.57418 10.1138 8.85313C9.64846 9.13208 9.25074 9.51074 8.9493 9.96185C8.64786 10.413 8.45019 10.9253 8.37052 11.462C8.29084 11.9986 8.33115 12.5463 8.48854 13.0655C8.64593 13.5847 8.91648 14.0626 9.28072 14.4647C9.64496 14.8668 10.0938 15.1832 10.595 15.391ZM8.002 8.002C8.52702 7.47698 9.15032 7.0605 9.8363 6.77636C10.5223 6.49222 11.2575 6.34597 12 6.34597C12.7425 6.34597 13.4777 6.49222 14.1637 6.77636C14.8497 7.0605 15.473 7.47698 15.998 8.002C16.523 8.52702 16.9395 9.15032 17.2236 9.8363C17.5078 10.5223 17.654 11.2575 17.654 12C17.654 12.7425 17.5078 13.4777 17.2236 14.1637C16.9395 14.8497 16.523 15.473 15.998 15.998C14.9377 17.0583 13.4995 17.654 12 17.654C10.5005 17.654 9.06234 17.0583 8.002 15.998C6.94166 14.9377 6.34597 13.4995 6.34597 12C6.34597 10.5005 6.94166 9.06234 8.002 8.002V8.002ZM18.908 7.188C19.0381 7.06527 19.1423 6.91768 19.2143 6.75397C19.2863 6.59027 19.3248 6.41377 19.3274 6.23493C19.33 6.05609 19.2967 5.87855 19.2295 5.71281C19.1622 5.54707 19.0624 5.39651 18.936 5.27004C18.8095 5.14357 18.6589 5.04376 18.4932 4.97652C18.3275 4.90928 18.1499 4.87598 17.9711 4.87858C17.7922 4.88119 17.6157 4.91965 17.452 4.9917C17.2883 5.06374 17.1407 5.1679 17.018 5.298C16.7793 5.55103 16.6486 5.88712 16.6537 6.23493C16.6588 6.58274 16.7992 6.91488 17.0452 7.16084C17.2911 7.40681 17.6233 7.54723 17.9711 7.5523C18.3189 7.55737 18.655 7.42669 18.908 7.188V7.188Z" fill="#F8F8F8"/>
                            </svg>

                          </button>
                        </div>
                      </h2>
                  </div>
                </div>
          </div>
      </section>
      <section class="w-full bg-satu-dua relative">
        <svg class="w-full absolute -top-4 right-0 left-0" viewBox="0 0 221 8" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M55.25 1.8C27.625 1.8 13.8125 3.15 0 4.5V0H221V4.5C207.188 5.85 193.375 7.2 165.75 7.2C110.5 7.2 110.5 1.8 55.25 1.8Z" fill="#CAD1C2"/>
        </svg>
          <div class="p-20">
                <div class="flex flex-col sm:flex-row justify-center pt-20 my-12 sm:my-4" >
                      <div class="flex flex-col h-auto bg-no-repeat bg-cover bg-center w-10/12 lg:w-7/12 mx-auto lg:mx-0 rounded-lg mt-4 sm:-mt-6 shadow-lg z-10" v-bind:style="{ backgroundImage:'url(' + imgPath3 + ')' }" data-aos="flip-left" data-aos-delay="200" >
                            <h2 class="text-center sm:text-4xl text-[#fff] p-10">
                              <p class="text-sm text-white mb-10 ">Dengan mengucap syukur atas kebaikan Tuhan Yang Maha Kuasa dan dengan segenap kerendahan hati, tanpa mengurangi rasa hormat. Kami mohon doa dan restu dari Bapak/Ibu/Saudara/i untuk hadir dihari bahagia Pernikahan kami yang akan dilaksanakan pada :
                              </p>
                              <img src="@/assets/icon.png" class="w-40 mx-auto" alt="" srcset="">
                            </h2>
                              <span class="nama__font_dua text-white text-center">Deasy Natalina Sitorus, A.Md</span>
                              <hr class="w-10/12 mx-auto mt-5 mb-10">
                              <p class="text-xl mt-3 heading-5 text-center">Selasa, 29 Juni 2021</p>
                              <p class="text-xl heading-5 text-center">10.00 WIB</p>
                              <div class="container mx-auto flex flex-wrap pt-4 pb-12">
                                    <div class="w-full md:w-2/6 p-5 flex flex-col flex-grow flex-shrink">
                                        <hr class="w-full mx-auto align-middle">
                                    </div>
                                    <div class="w-full md:w-0  flex flex-col flex-grow flex-shrink">
                                      <svg width="50" height="50" class="mx-auto" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M16 8.5L17.53 10.03L16.47 11.09L9.99997 4.62L3.52997 11.09L2.46997 10.03L9.99997 2.5L14 6.5V4.5H16V8.5ZM9.99997 6.04L16 12.03V18H3.99997V12.03L9.99997 6.04ZM12 17V12H7.99997V17H12Z" fill="#F8F8F8"/>
                                      </svg>
                                    </div>
                                    <div class="w-full md:w-2/6 p-5 flex flex-col flex-grow flex-shrink">
                                      <hr class="w-full mx-auto align-middle">
                                    </div>
                              </div>
                              <span class="nama__font_dua text-white text-center">Lokasi</span>
                              <p class="text-xl mt-3 heading-5 text-center">GKPI Jemaat Khusus <br>
                              Sidorame Medan
                              </p>
                              <div class="mx-auto">
                                <button class="text-white text-sm font-bold py-2 px-4 rounded-full inline-flex items-center button-submit-card">
                                    <span class="text-white"> View Map</span>
                                </button>
                              </div>
                              <p class="text-sm mt-3 text-center p-5">Mengingat pandemi covid-19, kami tidak dapat mengundang seluruh keluarga dan sahabat kami secara langsung, karena penting bagi kita semua untuk menjaga semuanya agar tetap aman, namun dengan segala kerendahan hati, kami mengundang Bapak, Ibu, Saudara/i kiranya berkenan hadir secara virtual melalui youtube live (link berikut)</p>
                              <div class="mx-auto mb-5">
                                <button class="text-sm font-bold py-2 px-4 rounded-full inline-flex items-center button-submit-card">
                                    <span class="text-white"> Youtube Live</span>
                                </button>
                              </div>
                        </div>
                </div>
          </div>
          <svg class="w-full absolute -bottom-4 right-0 left-0" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#CAD1C2"/>
          </svg>
      </section>
      <section class="w-full bg-dua h-auto relative">
              <div class="p-10">
                  <!--Card 1-->
                  <div class="w-1/2 lg:w-3/5 lg:flex mx-auto h-80 card-satu" data-aos="flip-left" data-aos-delay="200">
                    <div class=" lg:w-1/2 flex-none bg-cover bg-center lg:rounded-l-3xl text-center overflow-hidden" v-bind:style="{ backgroundImage:'url(' + imgPath2 + ')' }" title="Mountain">
                    </div>
                    <div class="border-r border-b border-l border-gray-400 lg:rounded-r-3xl bg-white  p-4 flex flex-col justify-center leading-normal">
                      <div class="mb-8 text-center">
                        <span class="nama__font_dua_tiga text-gray-700 text-center">Menuju Hari Bahagia</span>
                        <p class="text-gray-700 text-sm leading-6 text-center mt-4">Waktu berganti begitu cepat, dalam penantian kami yang penuh doa, kami berharap kehadiran secara daring dan doa restu seluruh keluarga, sahabat dan saudara terkasih, untuk menjadi saksi ikrar janji suci kami di hari bahagia</p>
                      </div>
                    </div>
                  </div>
                </div>
      </section>
      <section class="w-full h-auto bg-tiga-empat relative">
          <svg class="w-full absolute right-0 left-0" viewBox="0 0 221 8" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M55.25 1.8C27.625 1.8 13.8125 3.15 0 4.5V0H221V4.5C207.188 5.85 193.375 7.2 165.75 7.2C110.5 7.2 110.5 1.8 55.25 1.8Z" fill="#CAD1C2"/>
          </svg>
          <div class="p-16">
                <div class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4" data-aos="flip-left" data-aos-delay="200">
                    <div class="w-8/12 rounded-3xl h-screen card-input p-10 text-center" > 
                           <span class="nama__font_dua_tiga_satu">RSVP</span>
                           <hr class="w-1/2 mx-auto mt-9">
                           <p class="mt-10 mb-20">Bantu kami mempersiapkan jamuan yang hangat untuk anda semua dengan mengirimkan konfirmasi kehadiran melalui form berikut ini</p>
                          <div class="mb-24">
                            <label class="block text-white text-left mt-4 text-lg font-bold mb-2" for="username">
                              Name
                            </label>
                            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
                          </div>
                          <div class="mb-28">
                            <label class="block text-white text-left mt-4 text-lg font-bold mb-2" for="username">
                             Will You Attend ?
                            </label>
                            <div class=" text-left">
                              <div>
                                <input type="radio" name="" id=""> Yes
                              </div>
                              <div>
                                 <input type="radio" name="" id=""> No
                              </div>
                            </div>
                          </div>
                          <div class="mb-10">
                            <label class="block text-white text-left mt-4 text-lg font-bold mb-2" for="username">
                              How Many Guest Coming with you?
                            </label>
                            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
                          </div>
                          <button class="bg-gray-900 text-center text-sm font-bold py-2 px-4 w-full rounded-full ">
                               SUBMIT
                          </button>
                    </div>
                </div>
                 <div class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4" data-aos="flip-left" data-aos-delay="200">
                    <div class="w-8/12 rounded-3xl h-auto card-input p-10 text-center">
                           <span class="nama__font_dua_tiga_satu">Covid19</span>
                           <hr class="w-1/2 mx-auto mt-9">
                           <p class="mt-10 mb-20">Untuk menjaga acara pernikahan ini aman dari resiko penularan Covid-19, <br>
                            mohon memperhatikan anjuran berikut sebelum Bapak, Ibu, Saudara/i hadir ke lokasi:
                          </p>
                          <button class="bg-gray-50 text-black text-sm font-bold py-2 px-4 rounded-full inline-flex items-center button-submit">
                              <p class="text-black"> Anjuran Terkait Covid 19</p>
                          </button>
                         
                    </div>
                </div>
                <div class="flex flex-col sm:flex-row justify-center pt-12 my-12 sm:my-4" data-aos="flip-left" data-aos-delay="200">
                    <div class="w-8/12 rounded-3xl h-auto card-input p-10 text-center">
                           <span class="nama__font_dua_tiga_satu">Wedding Gift</span>
                           <hr class="w-1/2 mx-auto mt-9">
                           <p class="mt-10 mb-20">Bagi Keluarga dan Sahabat <br>
                            yang ingin mengirimkan hadiah, <br>
                            silahkan mengirimkannya melalui :
                          </p>
                          <div class="p-5">
                          <button class="bg-gray-50 text-black text-sm py-2 px-28 rounded-full ">
                              <p class="text-black"> Tranfer</p>
                          </button>
                          </div>
                          <button class="bg-gray-50 text-black text-sm py-2 px-28 rounded-full ">
                              <p class="text-black"> Kirim</p>
                          </button>
                    </div>
                </div>
                          <svg class="w-full absolute -bottom-4 right-0 left-0" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#CAD1C2"/>
                      </svg>
          </div>
      </section>
      <section class="w-full bg-dua h-auto relative">
              <div class="mx-auto text-center">
                
                        <span class="dancing text-gray-900  text-6xl text-center" data-aos="zoom-in" data-aos-delay="900">Our Gallery</span>
                        <p class="text-sm pt-3" data-aos="zoom-in" data-aos-delay="900">"Every Love Story is Beautiful, but Ours is My Favourite"</p>
                  
                       <div class="container mx-auto flex flex-wrap pt-4 pb-12">

                          <div class="w-full mb-4">
                            <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0"></div>
                          </div>

                          <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink" style="height:600px;" data-aos="zoom-in" data-aos-delay="900"> 
                            <div class="flex-1 overflow-hidden shadow bg-cover  w-10/12 mx-auto bg-no-repeat bg-bottom rounded-3xl" style=""  v-bind:style="{ backgroundImage:'url(' + imgPath + ')' }">
                              <a href="#" class="flex flex-wrap no-underline hover:no-underline">
                                
                              </a>
                            </div>
                           
                          </div>



                          <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink" data-aos="zoom-in" data-aos-delay="900">
                            <div class="flex-1 bg-white overflow-hidden w-10/12 mx-auto shadow bg-cover bg-no-repeat bg-bottom rounded-3xl "  v-bind:style="{ backgroundImage:'url(' + imgPath + ')' }">
                            
                              <a href="#" class="flex flex-wrap no-underline hover:no-underline">
                               
                              </a>
                            </div>
                            
                          </div>



                          <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink" data-aos="zoom-in" data-aos-delay="900">
                            <div class="flex-1 bg-white overflow-hidden w-10/12 mx-auto shadow bg-cover bg-no-repeat bg-bottom rounded-3xl "  v-bind:style="{ backgroundImage:'url(' + imgPath + ')' }">
                           
                                
                            </div>
                            
                          </div>


                        </div>
              </div>
      </section>
      <section class="w-full h-screen bg-tiga-empat relative bg-cover bg-no-repeat bg-bottom rounded-3xl" v-bind:style="{ backgroundImage:'url(' + imgPath + ')' }">
         <svg class="w-full absolute right-0 left-0" viewBox="0 0 221 8" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M55.25 1.8C27.625 1.8 13.8125 3.15 0 4.5V0H221V4.5C207.188 5.85 193.375 7.2 165.75 7.2C110.5 7.2 110.5 1.8 55.25 1.8Z" fill="#CAD1C2"/>
          </svg>
          
      </section>
       <section class="w-full h-screen relative"  style="background-color: #1C1C1C;">
         
          <svg class="w-full absolute -top-10 right-0 left-0" viewBox="0 0 190 8" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M47.5 0C95 0 95 5.4 142.5 5.4C166.25 5.4 178.125 4.05 190 2.7V7.2H0V2.7C11.875 1.35 23.75 0 47.5 0Z" fill="#1C1C1C"/>
          </svg>
          <img src="@/assets/log.png" class="w-3/12 mx-auto pt-24" alt="" srcset="" data-aos="zoom-in" data-aos-delay="1000">
          <h1 class="text-center font-extrabold text-4xl" data-aos="zoom-in" data-aos-delay="1000">@undangan_web</h1>
          <div class="p-5 text-center">
          <button class="px-3 py-3 rounded-lg mr-4" style="background-color: #9F8548;" data-aos="zoom-in" data-aos-delay="500">
            <svg width="18" height="20" viewBox="0 0 24 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M6.12664 28V14.8616H0V10.1311H6.12664V6.0907C6.12664 2.9157 9.74568 0 18.0847 0C21.461 0 23.9577 0.18354 23.9577 0.18354L23.761 4.60099C23.761 4.60099 21.2148 4.58693 18.4363 4.58693C15.4291 4.58693 14.9473 5.37275 14.9473 6.67702V10.1311H24L23.6061 14.8616H14.9473V28H6.12664Z" fill="white"/>
            </svg>
          </button>
          <button class="px-3 py-3  rounded-lg" style="background-color: #9F8548;" data-aos="zoom-in" data-aos-delay="500">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M7.465 1.066C8.638 1.012 9.012 1 12 1C14.988 1 15.362 1.013 16.534 1.066C17.706 1.119 18.506 1.306 19.206 1.577C19.939 1.854 20.604 2.287 21.154 2.847C21.714 3.396 22.146 4.06 22.422 4.794C22.694 5.494 22.88 6.294 22.934 7.464C22.988 8.639 23 9.013 23 12C23 14.988 22.987 15.362 22.934 16.535C22.881 17.705 22.694 18.505 22.422 19.205C22.146 19.9391 21.7133 20.6042 21.154 21.154C20.604 21.714 19.939 22.146 19.206 22.422C18.506 22.694 17.706 22.88 16.536 22.934C15.362 22.988 14.988 23 12 23C9.012 23 8.638 22.987 7.465 22.934C6.295 22.881 5.495 22.694 4.795 22.422C4.06092 22.146 3.39582 21.7133 2.846 21.154C2.28638 20.6047 1.85331 19.9399 1.577 19.206C1.306 18.506 1.12 17.706 1.066 16.536C1.012 15.361 1 14.987 1 12C1 9.012 1.013 8.638 1.066 7.466C1.119 6.294 1.306 5.494 1.577 4.794C1.85372 4.06008 2.28712 3.39531 2.847 2.846C3.39604 2.2865 4.06047 1.85344 4.794 1.577C5.494 1.306 6.294 1.12 7.464 1.066H7.465ZM16.445 3.046C15.285 2.993 14.937 2.982 12 2.982C9.063 2.982 8.715 2.993 7.555 3.046C6.482 3.095 5.9 3.274 5.512 3.425C4.999 3.625 4.632 3.862 4.247 4.247C3.88205 4.60205 3.60118 5.03428 3.425 5.512C3.274 5.9 3.095 6.482 3.046 7.555C2.993 8.715 2.982 9.063 2.982 12C2.982 14.937 2.993 15.285 3.046 16.445C3.095 17.518 3.274 18.1 3.425 18.488C3.601 18.965 3.882 19.398 4.247 19.753C4.602 20.118 5.035 20.399 5.512 20.575C5.9 20.726 6.482 20.905 7.555 20.954C8.715 21.007 9.062 21.018 12 21.018C14.938 21.018 15.285 21.007 16.445 20.954C17.518 20.905 18.1 20.726 18.488 20.575C19.001 20.375 19.368 20.138 19.753 19.753C20.118 19.398 20.399 18.965 20.575 18.488C20.726 18.1 20.905 17.518 20.954 16.445C21.007 15.285 21.018 14.937 21.018 12C21.018 9.063 21.007 8.715 20.954 7.555C20.905 6.482 20.726 5.9 20.575 5.512C20.375 4.999 20.138 4.632 19.753 4.247C19.3979 3.88207 18.9657 3.60121 18.488 3.425C18.1 3.274 17.518 3.095 16.445 3.046V3.046ZM10.595 15.391C11.3797 15.7176 12.2534 15.7617 13.0669 15.5157C13.8805 15.2697 14.5834 14.7489 15.0556 14.0422C15.5278 13.3356 15.7401 12.4869 15.656 11.6411C15.572 10.7953 15.197 10.005 14.595 9.405C14.2112 9.02148 13.7472 8.72781 13.2363 8.54515C12.7255 8.36248 12.1804 8.29536 11.6405 8.34862C11.1006 8.40187 10.5792 8.57418 10.1138 8.85313C9.64846 9.13208 9.25074 9.51074 8.9493 9.96185C8.64786 10.413 8.45019 10.9253 8.37052 11.462C8.29084 11.9986 8.33115 12.5463 8.48854 13.0655C8.64593 13.5847 8.91648 14.0626 9.28072 14.4647C9.64496 14.8668 10.0938 15.1832 10.595 15.391ZM8.002 8.002C8.52702 7.47698 9.15032 7.0605 9.8363 6.77636C10.5223 6.49222 11.2575 6.34597 12 6.34597C12.7425 6.34597 13.4777 6.49222 14.1637 6.77636C14.8497 7.0605 15.473 7.47698 15.998 8.002C16.523 8.52702 16.9395 9.15032 17.2236 9.8363C17.5078 10.5223 17.654 11.2575 17.654 12C17.654 12.7425 17.5078 13.4777 17.2236 14.1637C16.9395 14.8497 16.523 15.473 15.998 15.998C14.9377 17.0583 13.4995 17.654 12 17.654C10.5005 17.654 9.06234 17.0583 8.002 15.998C6.94166 14.9377 6.34597 13.4995 6.34597 12C6.34597 10.5005 6.94166 9.06234 8.002 8.002V8.002ZM18.908 7.188C19.0381 7.06527 19.1423 6.91768 19.2143 6.75397C19.2863 6.59027 19.3248 6.41377 19.3274 6.23493C19.33 6.05609 19.2967 5.87855 19.2295 5.71281C19.1622 5.54707 19.0624 5.39651 18.936 5.27004C18.8095 5.14357 18.6589 5.04376 18.4932 4.97652C18.3275 4.90928 18.1499 4.87598 17.9711 4.87858C17.7922 4.88119 17.6157 4.91965 17.452 4.9917C17.2883 5.06374 17.1407 5.1679 17.018 5.298C16.7793 5.55103 16.6486 5.88712 16.6537 6.23493C16.6588 6.58274 16.7992 6.91488 17.0452 7.16084C17.2911 7.40681 17.6233 7.54723 17.9711 7.5523C18.3189 7.55737 18.655 7.42669 18.908 7.188V7.188Z" fill="#F8F8F8"/>
            </svg>
          </button>

          </div>
      </section>
      
    
    </div>
    <transition name="fade" data-aos="fade-down">
        <div class="relative w-full h-screen bg-no-repeat bg-cover bg-left-bottom bg-fixed" v-if="!visible" v-bind:style="{ backgroundImage:'url(' + imgPath + ')' }">
            <div class="mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-center">
                <h2 class="text-center sm:text-4xl text-[#fff]">
                    <span class="block judul">The Wedding Of</span>
                    <span class="block py-5 nama__font">Yulia & Andri</span>
                </h2>
            </div>
            <div class="absolute bottom-20 right-0 left-0 mx-auto sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-center">
                <div class="text-center sm:text-4xl text-[#fff]">
                    <p class="text-xl mb-3 heading-3">Kepada Bapak/Ibu/Saudara/i</p>
                    <h4 class="text-2xl font-semibold heading-4">Nama Tamu</h4>
                    <p class="text-xl mt-3 heading-5">Mohon maaf bila ada kesalahan pada penulisan nama/gelar</p>
                    <button @click="visible = !visible" class="bg-gray-50 text-black text-sm font-bold py-2 px-4 rounded-full inline-flex items-center button-submit">
                        <span class="text-black"> Open Invitation</span>
                    </button>
                </div>
            </div>
        </div>
    </transition>
    <div class="flex justify-between fixed bottom-0 left-0 m-4 bg-fixed">
      <button class="p-4 text-sm font-bold tracking-wide text-white rounded-full focus:outline-none button_music">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M6 18.573C8.206 18.573 10 16.779 10 14.573V4.42797L19 7.69997V15.13C18.3949 14.7694 17.7044 14.5771 17 14.573C14.794 14.573 13 16.367 13 18.573C13 20.779 14.794 22.573 17 22.573C19.206 22.573 21 20.779 21 18.573V6.99997C21.0001 6.7948 20.937 6.59457 20.8193 6.42655C20.7016 6.25852 20.5349 6.13087 20.342 6.06097L9.342 2.06097C9.19099 2.00577 9.02889 1.98783 8.86947 2.00868C8.71005 2.02952 8.55801 2.08854 8.42627 2.18072C8.29454 2.27289 8.187 2.3955 8.11279 2.53813C8.03857 2.68076 7.99988 2.83919 8 2.99997V11.13C7.39487 10.7694 6.70439 10.5771 6 10.573C3.794 10.573 2 12.367 2 14.573C2 16.779 3.794 18.573 6 18.573Z" fill="white"/>
        </svg>
      </button>
    </div>
  </div>
</template>
<script>
import './assets/tailwind.css';
export default {
  name: 'App',
  data() {
    return {
      imgPath: require('@/assets/bag-1.jpg'),
      imgPath2: require('@/assets/bag-2.jpg'),
      imgPath3: require('@/assets/bag-5.jpg'),
      visible: false
    }
  }
}
</script>

<style>
  /* @import url('https://fonts.googleapis.com/css2?family=ABeeZee&family=Dancing+Script&family=Karla&family=Quicksand:wght@400;500&display=swap'); */
  @import url('https://fonts.googleapis.com/css2?family=ABeeZee&family=Dancing+Script&family=Karla&family=Quicksand:wght@400;500&family=Waterfall&display=swap');
  .header-cover{
    color: #fff;
  }
  .judul{
    font-family: 'Times New Roman', Times, serif;
    font-size: 1.5rem;
    padding-bottom: 10px;
    color: #fff;
  }
  .nama__font_satu{
    font-family: 'Dancing Script', cursive;
    /* font-weight: bold; */
    font-size: 28px;
    color: #2a2c21; 
  }
  .nama__font_dua{
    font-family: 'Dancing Script', cursive;
    /* font-weight: bold; */
    font-size: 30px;
    color: #fff; 
  }
  .dancing{
    font-family: 'Dancing Script', cursive;
  }
  .nama__font{
    font-family: 'Dancing Script', cursive;
    font-weight: bold;
    font-size: 64px;
    color: #fff;
  }
  .waterfall{
    font-family: 'Waterfall', cursive;
    font-weight: bold;
    font-size: 64px;
    color: #fff;
  }
  .waterfall_satu{
    font-size: 42px;
    font-family: 'Waterfall', cursive;
    font-weight: bold;
    color: #fff;
  }
  .heading-3{
    font-family: 'ABeeZee', sans-serif;
    font-size: 16px;
    color: #fff;

  }
  .heading-4{
    font-family: 'Karla', sans-serif;
    font-size: 28px;
    color: #fff;
    
  }
  .heading-5{
    font-family: 'Quicksand', sans-serif;
    font-size: 16px;
    padding-bottom: 20px;
    color: #fff;
  }

  .button-submit span{
    transition: all 0.5s;
    display: inline-block;
    position: relative;
    transition: 0.5s;
  }
  .button-submit span::after{
    content: ">";
    font-weight: bold;
    opacity: 0;
    position: absolute;
    top: 0;
    right: -5px;
    transition: 0.5s;
  }
  .button-submit:hover span {
    padding-right: 10px;
  }

  .button-submit:hover span:after {
    opacity: 1;
  }
  .fade-enter-active, .fade-leave-active {
    transition: opacity .5s;
  }
  .fade-enter, .fade-leave-to
  {
    opacity: 0;
  }
  .button_music{
    background-color: #F69F87;
  }
  .bg-satu{
    background-color: #2A2C21;
    height: 1200px;
  }
  .bg-satu-dua{
    background-color: #2A2C21;
    height: 1250px;
  }
  .bg-dua{
    background-color: #CAD1C2;
  }
  .bg-tiga{
    background-color: rgba(80,92,53,0.34);
  }
  .bg-tiga-empat{
    background-color: #EDEDED;
  }
  .bg__height{
    height: 1100px;
  }
  .gambar-bulat{
    border-radius: 150px;
  }
  .button-submit-card{
    background-color: #2A2C21;
  }
  .nama__font_dua_tiga{
    color: #2A2C21;
    font-family: 'Dancing Script', cursive;
    /* font-weight: bold; */
    font-size: 30px;
  }
  .nama__font_dua_tiga_satu{
    color: #fff;
    font-family: 'Dancing Script', cursive;
    /* font-weight: bold; */
    font-size: 30px;
  }
  .card-satu{
    border-radius: 2000px !important;
  }
  .card-input{
    background-image: linear-gradient(
    180deg,#474c38 0%,rgba(71,76,56,0.87) 100%);
  }
</style>
