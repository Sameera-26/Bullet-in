<template>
  <div class="row">
    <div class="col-md-7 col-lg-6 col-xs-12 col-sm-12">
      <div class="sm:mx-2 mx-10">
        <div>
          <div
            class="ti text-left text-primary my-2 md:w-[82%] lg:w-[82%] sm:leading-normal lg:leading-normal sm:text-4xl xs:text-4xl lg:text-5xl"
          >
            Make You Product Upto Date With our Latest CVE's Database.
          </div>
          <div
            class="t2 text-left text-grey-8 md:w-[88%] lg:w-[88%] sm:text-md md:text-md py-6"
          >
            Purchase a plan according to your need and make sure your system is
            upto date with latest path of vulnerability.
          </div>
          <div class="flex">
            <q-img
              src="https://seekvectorlogo.com/wp-content/uploads/2017/12/microsoft-vector-logo.png"
              class="responsive w-[10%] h-[10%]"
            />
            <q-img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJeZIPvUv8zAc9pW0pO8_dBeMI5BYl7jcrD5FZsau-iYvUFxn8bIqA7SvfdtGa01x5sxM&usqp=CAU"
              class="responsive mt-2 q-mx-sm w-[10%] h-[10%]"
            />
            <q-img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTW0HW6OXboG2JNSQ1qDop4WDYUbhfEVdtGFWVaJQEks-6s7r3RudxFiUyBHx-ik1TybXQ&usqp=CAU"
              class="responsive q-mx-sm w-[10%] h-[10%]"
            />
            <q-img
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Microsoft_Office_2013-2019_logo_and_wordmark.svg/1024px-Microsoft_Office_2013-2019_logo_and_wordmark.svg.png"
              class="responsive mx-4 w-[10%] h-[10%]"
            />
            <div class="ti text-primary sm:text-sm text-weight-bold">
              view more vendors
            </div>
            <q-btn
              color="primary"
              size="sm"
              icon="fa solid fa-right-long"
              flat
              class="md:-mt-4"
            ></q-btn>
          </div>
          <img
            src="~assets/mail.svg"
            class="gt-sm -mt-8 ml-auto"
            style="height: 600px"
          />
        </div>
      </div>
    </div>
    <!-- RIGHT COLUMNNN -->
    <div class="col-md-5 col-lg-6 col-xs-10 col-sm-10">
      <img
        src="~assets/pic-1.svg"
        class="ml-auto md:mb-16 md:px-14"
        style="height: 330px"
      />

      <div class="py-6 mb-5 space-x-4">
        <div class="text-left">
          <q-btn
            color="white"
            size="md"
            icon="fa  fa-users"
            flat
            class="mx-4 mb-10 bg-grey-7 h-14"
          />
        </div>
        <div
          class="t3 text-left text-primary md:w-[72%] lg:w-[72%] sm:text-4xl xs:text-4xl lg:text-5xl sm:leading-normal lg:leading-normal"
        >
          Deliver what your customers want every time.
        </div>
        <div
          class="t4 text-left text-grey-8 md:w-[72%] lg:w-[82%] sm:text-md md:text-md my-4"
        >
          Deliver what your customers want every time Lorem ipsum dolor, sit
          amet consectetur adipisicing elit. placeat, in qn exercitatio magnaa
          in the quollmlld molestias quioninina aspernatur deserunt
          voluptatibus.
        </div>

        <div class="row text-weight-bold md:text-h4 sm:text-2xl t5">
          <div class="text-primary t5">24/7</div>
          <div class="text-primary t5 sm:mx-8 mx-14">99.9%</div>
          <div class="text-primary sm:mx-0 t5 mx-4">100k+</div>
        </div>
        <div class="row text-grey-7 md:text-sm sm:text-sm t5 md:mx-4">
          <div class="">Delivery</div>
          <div class="sm:mx-8">Surity</div>
          <div class="sm:mx-6">Members</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "IntroComp",
};
</script>
<style>
@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";

.ti {
  font-family: "Sen-bold";
}
.t2 {
  font-family: "Sen";
  font-weight: bold;
  max-width: 80%;
}
.t3 {
  font-family: "Sen-bold";
}
.t4 {
  font-family: "Sen";
}

.t5 {
  font-family: "Sen-bold";
}
.t6 {
  font-family: "Sen";
}
</style>
