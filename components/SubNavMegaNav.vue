<template>
  <div>
    <!-- Sub Nav -->
    <div class="py-15 border-bottom px-25 d-md-block d-none">
      <div class="width-limiter">
        <div class="row no-gutters justify-content-end">
          <div
            class="row no-gutters align-items-center mr-30 font-4 text-grey pointer"
            id="mega-nav-toggle"
          >
            <span>Courses</span>
            <img
              src="https://minio.cb.lk/public/fa-5.13/svgs/solid/chevron-down.svg"
              class="ml-10"
              style="height: 15px;"
            />
          </div>
          <div
            class="row no-gutters align-items-center mr-30 font-4 text-grey pointer"
          >
            <span>Events</span>
            <img
              src="https://minio.cb.lk/public/fa-5.13/svgs/solid/chevron-down.svg"
              class="ml-10"
              style="height: 15px;"
            />
          </div>
          <div
            class="row no-gutters align-items-center mr-30 font-4 text-grey pointer"
          >
            <span>Blogs</span>
            <img
              src="https://minio.cb.lk/public/fa-5.13/svgs/solid/chevron-down.svg"
              class="ml-10"
              style="height: 15px;"
            />
          </div>
          <div
            class="row no-gutters align-items-center mr-30 font-4 text-grey pointer"
          >
            <span>Campus Superheroes</span>
          </div>
          <div
            class="row no-gutters align-items-center font-4 text-grey pointer"
          >
            <span>Contact</span>
          </div>
        </div>
      </div>
    </div>

    <!-- Mega Nav -->
    <div class="py-50 border-bottom px-25 d-none bg-white" id="mega-nav">
      <div class="width-limiter">
        <div class="row">
          <div class="col-3">
            <img
              src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/online-courses.svg"
              style="height: 40px;"
            />
            <div class="font-3 bold mt-15 text-grey-light-1">
              ONLINE COURSES
            </div>
            <div class="mt-35 mb-15">
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer mr-20" href="#">
                  C++ Master Course
                </a>
                <div
                  class="bg-gradient-yellow white font-1 p-1 d-inline-block"
                  style="border-radius: 2px;"
                >
                  NEW
                </div>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  JAVA Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Python for Developers
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Web Dev with Python - Django
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Data Science
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Competitive Programming
                </a>
              </div>
            </div>
            <button class="button-tertiary mt-15">
              Explore All
              <img
                src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/button-icon-orange.svg"
                class="ml-2"
              />
            </button>
          </div>
          <div class="col-3">
            <img
              src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/classroom-courses.svg"
              style="height: 40px;"
            />
            <div class="font-3 bold mt-15 text-grey-light-1">
              CLASSROOM COURSES
            </div>
            <div class="mt-35 mb-15">
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  C++ Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  JAVA Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Python for Developers
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Web Dev with Python - Django
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer mr-20" href="#">
                  Data Science
                </a>
                <div
                  class="bg-gradient-yellow white font-1 p-1 d-inline-block"
                  style="border-radius: 2px;"
                >
                  NEW
                </div>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Competitive Programming
                </a>
              </div>
            </div>
            <button class="button-tertiary mt-15">
              Explore All
              <img
                src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/button-icon-orange.svg"
                class="ml-2"
              />
            </button>
          </div>
          <div class="col-3">
            <img
              src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/live-courses.svg"
              style="height: 40px;"
            />
            <div class="font-3 bold mt-15 text-grey-light-1">LIVE COURSES</div>
            <div class="mt-35 mb-15">
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  C++ Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  JAVA Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Python for Developers
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Web Dev with Python - Django
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Data Science
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Competitive Programming
                </a>
              </div>
            </div>
            <button class="button-tertiary mt-15">
              Explore All
              <img
                src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/button-icon-orange.svg"
                class="ml-2"
              />
            </button>
          </div>
          <div class="col-3">
            <img
              src="https://cb-thumbnails.s3.ap-south-1.amazonaws.com/live-courses.svg"
              style="height: 40px;"
            />
            <div class="row no-gutters align-items-center mt-15">
              <div class="font-3 bold text-grey-light-1 mr-20">
                INDUSTRIAL TRAINING
              </div>
              <div
                class="bg-gradient-yellow white font-1 p-1 d-inline-block"
                style="border-radius: 2px;"
              >
                NEW
              </div>
            </div>
            <div class="mt-35 mb-15">
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  C++ Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  JAVA Master Course
                </a>
              </div>
              <div class="mb-20 row no-gutters align-items-center">
                <a class="font-4 bold pointer" href="#">
                  Python for Developers
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    document.querySelector("#mega-nav-toggle").addEventListener("click", () => {
      const meganav = document.querySelector("#mega-nav");

      if (meganav.classList.contains("d-none")) {
        meganav.classList.remove("d-none");
      } else {
        meganav.classList.add("d-none");
      }
    });
  },
};
</script>
