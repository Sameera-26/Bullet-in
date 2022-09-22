<template>
  <div class="justify-center">
    <div
      class="t5 sm:text-5xl lg:text-5xl md:text-6xl text-primary text-center q-mt-xl q-my-xl"
    >
      Trusted by over 5 businesses
    </div>
    <div class="row justify-center mx-16">
      <!-- column-1 -->
      <div
        class="col-md-3 col-lg-3 col-xs-10 col-sm-10 mx-16 q-mt-xl q-gutter-x-sm q-mx-xl"
      >
        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mb-xl q-mx-xl row"
        >
          <q-btn
            color="secondary"
            size="lg sm:sm"
            icon="fa fa-plus-circle"
            flat
            class="q-mb-xs"
          ></q-btn>
          Transistor
        </div>
        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mx-xl q-mt-md text-center row"
        >
          <q-btn
            color="secondary"
            size="lg sm:sm"
            icon="fa fa-file"
            flat
            class="q-mb-sm"
          ></q-btn>
          Tuple
        </div>
      </div>
      <!-- column-2 -->
      <div
        class="col-md-3 col-lg-3 col-xs-10 col-sm-10 q-mx-md mt-2 q-py-lg q-gutter-x-sm"
      >
        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mx-xl q-mb-xl q-mt-md text-center row"
        >
          <q-btn
            color="secondary"
            size="lg sm:sm"
            icon="fa fa-sun"
            flat
            class="q-mb-sm"
          ></q-btn>
          Mirage
        </div>

        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mx-xl q-mt-md text-center row"
        >
          <q-btn
            color="secondary"
            size="lg sm:sm"
            icon="fa-brands fa-laravel"
            flat
            class="q-mb-sm"
          ></q-btn>
          Laravel
        </div>
      </div>
      <!-- column-3 -->
      <div
        class="col-md-3 col-lg-3 col-xs-10 col-sm-10 q-mx-md sm:-my-4 q-py-lg q-gutter-x-sm"
      >
        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mx-xl q-mb-xl mt-10 text-center row"
        >
          <q-btn
            color="secondary"
            size="lg sm:sm"
            icon="fa fa-u"
            flat
            class="q-mb-xs"
          ></q-btn>
          StaticKit
        </div>

        <div
          class="t6 sm:text-2xl lg:text-3xl md:text-3xl text-secondary q-mx-xl q-mt-xl text-center row"
        >
          <q-btn
            color="secondary"
            size="xl sm:sm"
            icon="fa fa-dollar"
            flat
            class="q-mb-sm"
          ></q-btn>
          Statamic
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BusinessComp",
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
