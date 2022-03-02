<template>
  <v-header />
  <main>
    <div class="container">
      <section class="section-1">
        <div class="flex">
          <div class="pb-2">
            <h1>Digital Marketing. Creative Design.</h1>
            <p>
              "Your work is going to fill a large part of your life, and the
              only way to be truly satisfied is to do what you believe is great
              work. And the only way to do great work is to love what you do."
            </p>
            <div class="pb-2">
              <img src="./assets/images/person-logo.png" alt="person logo" />
              <p class="font-bold">Samantha Norton</p>
              <img src="./assets/images/stars.png" />
            </div>
            <div class="pb-2">
              <button class="bg-orange-500 px-4 py-2 rounded-full">
                Get started now
              </button>
            </div>
          </div>
          <div>
            <img src="./assets/images/sec-1.png" alt="" />
          </div>
        </div>
      </section>
      <section class="section-2">
        <div class="text-center">
          <span class="text-blue-600">Event Technology</span>
          <h2>
            The solution that <br />
            your business can rely on
          </h2>
          <p>
            Your work is going to fill a large part of your life, and the only
            way to be truly satisfied is to do what you believe is great work.
            And the only way to do great work is to love what you do.
          </p>
        </div>
        <div>
          <img src="./assets/images/sec-2.png" alt="" />
        </div>
      </section>
      <section class="section-3">
        <div class="flex">
          <div>
            <h3>
              Experience design and intelligent marketing for growing brands
            </h3>
            <p>
              The first rule of any technology used in a business is that
              automation applied to an efficient operation will magnify the
              efficiency.
            </p>
            <div>
              <img src="" alt="#" />
              <h3>Customer Support</h3>
              <p>Make every detail perfect & limit the number of details.</p>
              <button>Read more</button>
              <div>
                <img src="" alt="" />
                <h3>Customer Support</h3>
                <p>Make every detail perfect & limit the number of details.</p>
              </div>
              <div>
                <img src="" alt="" />
                <h3>Email marketing</h3>
                <p>Make every detail perfect & limit the number of details.</p>
              </div>
            </div>
          </div>
          <div>
            <h3>Get in touch of the world</h3>
            <p>
              Your work is going to fill a large part of your life, and the only
              way to be truly satisfied.
            </p>
            <form class="w-full max-w-lg">
              <div class="flex flex-wrap -mx-3 mb-6">
                <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-first-name"
                  >
                    First Name
                  </label>
                  <input
                    class="appearance-none block w-full bg-gray-200 text-gray-700 border border-red-500 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white"
                    id="grid-first-name"
                    type="text"
                    placeholder="Jane"
                  />
                  <p class="text-red-500 text-xs italic">
                    Please fill out this field.
                  </p>
                </div>
                <div class="w-full md:w-1/2 px-3">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-last-name"
                  >
                    Last Name
                  </label>
                  <input
                    class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                    id="grid-last-name"
                    type="text"
                    placeholder="Doe"
                  />
                </div>
              </div>
              <div class="flex flex-wrap -mx-3 mb-6">
                <div class="w-full px-3">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-password"
                  >
                    Password
                  </label>
                  <input
                    class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                    id="grid-password"
                    type="password"
                    placeholder="******************"
                  />
                  <p class="text-gray-600 text-xs italic">
                    Make it as long and as crazy as you'd like
                  </p>
                </div>
              </div>
              <div class="flex flex-wrap -mx-3 mb-2">
                <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-city"
                  >
                    City
                  </label>
                  <input
                    class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                    id="grid-city"
                    type="text"
                    placeholder="Albuquerque"
                  />
                </div>
                <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-state"
                  >
                    State
                  </label>
                  <div class="relative">
                    <select
                      class="block appearance-none w-full bg-gray-200 border border-gray-200 text-gray-700 py-3 px-4 pr-8 rounded leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                      id="grid-state"
                    >
                      <option>New Mexico</option>
                      <option>Missouri</option>
                      <option>Texas</option>
                    </select>
                    <div
                      class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700"
                    >
                      <svg
                        class="fill-current h-4 w-4"
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                      >
                        <path
                          d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                        />
                      </svg>
                    </div>
                  </div>
                </div>
                <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
                  <label
                    class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2"
                    for="grid-zip"
                  >
                    Zip
                  </label>
                  <input
                    class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500"
                    id="grid-zip"
                    type="text"
                    placeholder="90210"
                  />
                </div>
              </div>
            </form>
          </div>
        </div>
      </section>
      <section class="section-4">
        <div class="flex">
          <div>
            adfasf
            <img src="" alt="" />
          </div>
          <div>
            <h2>See why we are trusted the world over</h2>
            <p>See why we are trusted the world over</p>
            <div>
              <select>
                <option>Do you provide customer support?</option>
                <option>How much traffic can the hosting handle?</option>
                <option>Do you have any questions for us?</option>
                <option>What is your return policy?</option>
              </select>
              <select>
                <option>Do you provide customer support?</option>
                <option>How much traffic can the hosting handle?</option>
                <option>Do you have any questions for us?</option>
                <option>What is your return policy?</option>
              </select>
              <select>
                <option>Do you provide customer support?</option>
                <option>How much traffic can the hosting handle?</option>
                <option>Do you have any questions for us?</option>
                <option>What is your return policy?</option>
              </select>
              <select>
                <option>Do you provide customer support?</option>
                <option>How much traffic can the hosting handle?</option>
                <option>Do you have any questions for us?</option>
                <option>What is your return policy?</option>
              </select>
            </div>
          </div>
        </div>
      </section>
      <section class="section-5">
        <div class="flex">
          <div>
            <h2>Marketing and digital products that grow businesses!</h2>
            <p>
              The first rule of any technology used in a business is that
              automation applied to an efficient operation will magnify the
              efficiency.
            </p>
            <div>stats</div>
          </div>
          <div>
            <h3>Professional ticket</h3>
            <span>$45.00</span>
            <p>Per month</p>
            <ul>
              <li>Meet and Greet with Speakers</li>
              <li>Video Facilities</li>
              <li>Speaker Facilities</li>
              <li>Questions & Answers</li>
              <li>Questions & Answers</li>
              <li>Dedicated account manager</li>
            </ul>
            <button>Get Ticket</button>
          </div>
        </div>
      </section>
      <section class="section-6">
        <div
          id="carouselExampleCaptions"
          class="carousel slide relative"
          data-bs-ride="carousel"
        >
          <div
            class="carousel-indicators absolute right-0 bottom-0 left-0 flex justify-center p-0 mb-4"
          >
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="0"
              class="active"
              aria-current="true"
              aria-label="Slide 1"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="1"
              aria-label="Slide 2"
            ></button>
            <button
              type="button"
              data-bs-target="#carouselExampleCaptions"
              data-bs-slide-to="2"
              aria-label="Slide 3"
            ></button>
          </div>
          <div class="carousel-inner relative w-full overflow-hidden">
            <div class="carousel-item active relative float-left w-full">
              <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(15).jpg"
                class="block w-full"
                alt="..."
              />
              <div
                class="carousel-caption hidden md:block absolute text-center"
              >
                <h5 class="text-xl">First slide label</h5>
                <p>
                  Some representative placeholder content for the first slide.
                </p>
              </div>
            </div>
            <div class="carousel-item relative float-left w-full">
              <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(22).jpg"
                class="block w-full"
                alt="..."
              />
              <div
                class="carousel-caption hidden md:block absolute text-center"
              >
                <h5 class="text-xl">Second slide label</h5>
                <p>
                  Some representative placeholder content for the second slide.
                </p>
              </div>
            </div>
            <div class="carousel-item relative float-left w-full">
              <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(23).jpg"
                class="block w-full"
                alt="..."
              />
              <div
                class="carousel-caption hidden md:block absolute text-center"
              >
                <h5 class="text-xl">Third slide label</h5>
                <p>
                  Some representative placeholder content for the third slide.
                </p>
              </div>
            </div>
          </div>
          <button
            class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev"
          >
            <span
              class="carousel-control-prev-icon inline-block bg-no-repeat"
              aria-hidden="true"
            ></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next"
          >
            <span
              class="carousel-control-next-icon inline-block bg-no-repeat"
              aria-hidden="true"
            ></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </section>
      <section class="section-7">
        <div class="flex">
          <div>
            <span>an unique marketing template</span>
            <p>
              "Any strategy that gets a message to rise above the clutter is
              terrific from the advertiser's perspective. Even if it's not much
              of a secret, it's still a pretty good marketing idea."
            </p>
            <button>Meet the team</button>
          </div>
          <div>
            <ul>
              <li>
                <img src="" alt="" />
              </li>
              <li>
                <img src="" alt="" />
              </li>
              <li>
                <img src="" alt="" />
              </li>
              <li>
                <img src="" alt="" />
              </li>
              <li>
                <img src="" alt="" />
              </li>
              <li>
                <img src="" alt="" />
              </li>
            </ul>
          </div>
        </div>
      </section>
      <section class="section-8">
        <span>FROM OUR BLOG</span>
        <h2>Recent News & Updates</h2>
        <div class="flex">
          <div>
            <div>
              <img src="" alt="" />
              <span>DESIGN</span>
              <h3>Best Blogs To Follow About Web Design</h3>
              <p>
                Et magni et ea unde tempore. Corrupti quia adipisci qui dicta
                sint.
              </p>
            </div>
            <div>
              <img src="" alt="" />
              <span>TUTORIAL</span>
              <h3>5 Great Web Design Resources</h3>
              <p>
                Et magni et ea unde tempore. Corrupti quia adipisci qui dicta
                sint.
              </p>
            </div>
          </div>
          <div>
            <span>MARKETING</span>
            <h3>What Will Website Be Like In 100 Years?</h3>
          </div>
        </div>
      </section>
    </div>
  </main>
</template>

<script>
import VHeader from "./components/Header.vue";

export default {
  name: "App",
  components: { VHeader },
};
</script>
