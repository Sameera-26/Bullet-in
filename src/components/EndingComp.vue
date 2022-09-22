<template>
  <div
    class="t5 sm:text-5xl lg:text-6xl md:text-6xl text-primary text-center q-pt-xl"
  >
    Ready to dive in?
  </div>
  <div
    class="t5 sm:text-4xl lg:text-6xl md:text-6xl text-primary text-center q-ma-lg"
  >
    Start your free trial today.
  </div>
  <div class="row justify-center">
    <q-btn
      unelevated
      rounded
      color="info"
      class="md:text-xl sm:text-xl q-mx-sm capitalize"
      label="Learn More"
    />
    <q-btn
      unelevated
      rounded
      color="positive"
      class="md:text-xl sm:text-xl q-mx-sm capitalize"
      label="Get Started"
    />
  </div>

  <q-separator color="accent" class="q-mt-xl q-mb-xl" inset />
  <div
    class="row text-grey-7 md:text-xl sm:text-xl q-gutter-x-xl justify-center"
  >
    <a href="#" class="hover:text-secondary">About</a>
    <a href="#" class="hover:text-secondary">Blog</a>
    <a href="#" class="hover:text-secondary">Jobs</a>
    <a href="#" class="hover:text-secondary">Press</a>
    <a href="#" class="hover:text-secondary">Accessibility</a>
    <a href="#" class="hover:text-secondary">Partners</a>
  </div>
  <div class="row q-my-lg q-gutter-x-lg justify-center">
    <q-btn
      color="secondary"
      size="md"
      icon="fa-brands fa-facebook"
      flat
    ></q-btn>
    <q-btn
      color="secondary"
      size="md"
      icon="fa-brands fa-instagram"
      flat
    ></q-btn>
    <q-btn color="secondary" size="md" icon="fa-brands fa-twitter" flat></q-btn>
    <q-btn color="secondary" size="md" icon="fa-brands fa-github" flat></q-btn>
  </div>
  <div
    class="row text-grey-6 md:text-xl sm:text-xl q-gutter-x-xl justify-center"
  >
    <div>© 2020 Workflow, Inc. All rights reserved.</div>
  </div>
  <div></div>
</template>
<script>
export default {
  name: "EndingComp",
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
