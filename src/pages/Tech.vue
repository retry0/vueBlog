<template>
  <Layout>
    <!-- hero -->
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-10">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-right">
        <div class="leading-tight">Tech Stack</div>
      </div>
    </div>
    <!-- end hero -->
      <!-- PROFESSIONAL PROFILE -->
      <div class="overflow-x-hidden border-gray-200">
        <div class="container-inner mx-auto text-xl pt-8 pb-4 mb-4 mt-4 relative">

          <div class="absolute left-0" style="bottom: 25px; transform: translateX(-100%)">
            <svg width="170px" height="170px">
              <use xlink:href="#dots-triangle" />
            </svg>
          </div>

        <div class="absolute right-0" style="top: 25px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

          <div class="flex flex-col sm:flex-row justify-between items-center mb-12">
            <div
              class="flex-1 text-lg sm:text-xl ml-6">
            
            </div>
          </div>
        </div>
      </div>
      <!-- END PROFESSIONAL PROFILE -->

      <!-- PROFESSIONAL EXPERIENCE -->
      <div class="overflow-x-hidden border-gray-200 bg-background-primary">
        <hr width="50%" style="margin: auto" />
        <div class="container-inner mx-auto text-xl mt-8 relative">
          <h2 class="font-bold mb-6" id="about">Technology</h2>
          <div class="flex flex-col sm:flex-row justify-between items-center mb-8">
            <div class="flex-1 text-lg sm:text-xl ml-6">
              My professional experiences as Software Engineer i am several using languange
              <ul class="text-lg sm:text-xl mx-6">
                <li class="my-6">
                  <strong>Languange <br></strong>
                  <ul class="pl-6" style="list-style-type: circle;">
                    <li>PHP</li>
                    <li>Javscript</li>
                  </ul>
                </li>
                <li class="my-6">
                  <strong>E-Life Solutions Plt <br>
                      Software Engineer  </strong>(01/2018 ~ 07/2019)
                  <ul class="pl-6" style="list-style-type: circle;">
                   <li>Developed RESTful API for mobile applications and IOT Devices using NodeJS,Express</li>
  <li>Develop Project Management System company using Laravel and mysql for our database.</li>
  <li>Helped creating the profit and loss statement for a new project as an intern in the project planning department.</li>
                    </ul>
                </li>
                <li class="my-6">
                  <strong>E-Life Solutions Plt <br>
                      Junior Software Engineer
                   </strong>(2017/07 ~ 2017/12)
                  <ul class="pl-6" style="list-style-type: circle;">
                   <li>Developed on module reporting at application to decision risk for Electromagnetic, we call ERMA using C++(QT) and also MySQL for database.</li>
                    </ul>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <!-- END PROFESSIONAL EXPERIENCE -->

      <!-- EDUCATION -->
      <div class="overflow-x-hidden border-gray-200 bg-background-primary">
        <div class="container-inner mx-auto text-xl mt-2 relative">
          <h2 class="font-bold mb-6" id="about">Education</h2>
          <div class="flex flex-col sm:flex-row justify-between items-center mb-4">
            <div class="flex-1 text-lg sm:text-xl ml-6">
              I was raised with education being paramount. I am proud to hold three degrees that have shaped my expertise and form a unique blend of technical, leadership, and communication skills.
              <ul class="text-lg sm:text-xl mx-6">
                <li class="my-6">
                  <strong>Bachelor's of Science in Computer Science (Incomplete)</strong> <br /> Major Software Engineering
                </li>
                 <li class="my-6">
                  <strong>Assosicated Degree in Informatic Engineering  (Completed)</strong><br />Major Software Engineering
                </li>
              </ul>
            </div>
          </div>
        </div>
        <hr width="50%" style="margin: auto" />
      </div>
      <!-- END EDUCATION -->

      <!-- PERSONAL INTERESTS -->
      <div class="overflow-x-hidden border-gray-200">
        <div class="container-inner mx-auto text-xl pt-8 pb-4 mt-4 mb-8 relative">
          <h2 class="font-bold mb-6" id="about">Others dream of cookies...</h2>

          <div class="absolute left-0" style="bottom: 25px; transform: translateX(-100%)">
            <svg width="170px" height="170px">
              <use xlink:href="#dots-triangle" />
            </svg>
          </div>

        <div class="absolute right-0" style="top: 25px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

          <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
            <div
              class="flex-1 text-lg sm:text-xl ml-6"
            > I'm energized by learning new technologies and I embrace the grind of developing a new skill. I relax by  watching movie, and competing in anything and everything.</div>
          </div>
        </div>
      </div>
      <!-- END PERSONAL INTERESTS -->
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Tech Stack"
  }
};
</script>

