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
            <Button text=" Get started now" class="bg-orange-500 pb-2" />
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
            <h2>
              Experience design and intelligent marketing for growing brands
            </h2>
            <p>
              The first rule of any technology used in a business is that
              automation applied to an efficient operation will magnify the
              efficiency.
            </p>
            <div class="flex flex-row">
              <div>
                <img src="./assets/images/sec-3/sec-3_img-1.svg" alt="img" />
                <h3>Customer Support</h3>
                <p>Make every detail perfect & limit the number of details.</p>
                <Button text="Read more" class="text-blue-100 bg-blue-800" />
              </div>
              <div>
                <img src="./assets/images/sec-3/sec-3_img-2.svg" alt="img" />
                <h3>Email marketing</h3>
                <p>Make every detail perfect & limit the number of details.</p>
              </div>
            </div>
          </div>
          <div>
            <img src="./assets/images/sec-3/sec-3_img-3.png" alt="img" />
            <h3>Get in touch of the world</h3>
            <p>
              Your work is going to fill a large part of your life, and the only
              way to be truly satisfied.
            </p>
            <v-form />
          </div>
        </div>
      </section>
      <section class="section-4">
        <div class="flex">
          <div>
            <img src="./assets/images/sec-4/sec-4_img.png" alt="img" />
          </div>
          <div>
            <h2>See why we are trusted the world over</h2>
            <p>See why we are trusted the world over</p>
            <div class="flex flex-col">
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
            <Button text="Get Ticket" class="text-blue-100 bg-blue-800" />
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
        <div class="flex flex-col">
          <div>
            <span>an unique marketing template</span>
            <p>
              "Any strategy that gets a message to rise above the clutter is
              terrific from the advertiser's perspective. Even if it's not much
              of a secret, it's still a pretty good marketing idea."
            </p>
            <Button text="Meet the team" class="text-blue-100 bg-blue-800" />
          </div>
          <div>
            <ul class="flex flex-row">
              <li>
                <img src="./assets/images/sec-7/sec-7_img-1.png" alt="" />
              </li>
              <li>
                <img src="./assets/images/sec-7/sec-7_img-2.png" alt="" />
              </li>
              <li>
                <img src="./assets/images/sec-7/sec-7_img-3.png" alt="" />
              </li>
              <li>
                <img src="./assets/images/sec-7/sec-7_img-4.png" alt="" />
              </li>
              <li>
                <img src="./assets/images/sec-7/sec-7_img-5.png" alt="" />
              </li>
              <li>
                <img src="./assets/images/sec-7/sec-7_img-6.png" alt="" />
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
              <img src="./assets/images/sec-8/sec-8_img-1.png" alt="photo" />
              <span>DESIGN</span>
              <h3>Best Blogs To Follow About Web Design</h3>
              <p>
                Et magni et ea unde tempore. Corrupti quia adipisci qui dicta
                sint.
              </p>
            </div>
            <div>
              <img src="./assets/images/sec-8/sec-8_img-2.png" alt="photo" />
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
  <v-footer />
</template>

<script>
import VHeader from "./components/Header.vue";
import VFooter from "./components/Footer.vue";
import VForm from "./components/Form.vue";
import Button from "./components/Button.vue";

export default {
  name: "App",
  components: { Button, VHeader, VFooter, VForm },
};
</script>
