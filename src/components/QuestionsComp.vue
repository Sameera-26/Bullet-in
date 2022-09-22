<template>
  <div class="justify-center">
    <q-separator color="accent" class="q-mt-xl" inset />

    <div
      class="t5 sm:text-5xl lg:text-5xl md:text-6xl text-primary text-center q-pt-xl q-ma-lg"
    >
      Frequently asked questions
    </div>
    <div class="row">
      <div class="col-lg-3"></div>
      <div class="col-md-6 col-lg-6 col-xs-12 col-sm-12 md:w-[71%]">
        <q-separator color="accent" class="q-mt-lg q-mb-lg" inset />

        <q-expansion-item
          expand-separator
          class="t6 text-black sm:text-xl lg:text-2xl md:text-2xl"
          label="Do customers get support with anything else?"
          :header-inset-level="1.3"
          :content-inset-level="1.3"
          group="groupA"
        >
          <q-card>
            <q-card-section
              class="t6 text-grey-8 sm:text-xl md:text-xl md:w-[95%]"
            >
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem,
              eius reprehenderit eos corrupti commodi magni quaerat ex numquam.
            </q-card-section>
          </q-card>
        </q-expansion-item>
        <div class="col-3 flex-center">
          <q-separator color="accent" class="q-mt-lg q-mb-lg" inset />
        </div>
        <q-expansion-item
          expand-separator
          class="t6 text-black sm:text-xl lg:text-2xl md:text-2xl"
          label="How long does is take to recover?"
          :header-inset-level="1.3"
          :content-inset-level="1.3"
          group="groupA"
        >
          <q-card>
            <q-card-section
              class="t6 text-grey-8 sm:text-xl md:text-xl md:w-[95%]"
            >
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem,
              eius reprehenderit eos corrupti commodi magni quaerat ex numquam.
            </q-card-section>
          </q-card>
        </q-expansion-item>
        <q-separator color="accent" class="q-mt-lg q-mb-lg" inset />
        <q-expansion-item
          expand-separator
          class="t6 text-black sm:text-xl lg:text-2xl md:text-2xl"
          label="How much will it cost?"
          :header-inset-level="1.3"
          :content-inset-level="1.3"
          group="groupA"
        >
          <q-card>
            <q-card-section
              class="text-grey-8 sm:text-xl md:text-xl md:w-[95%]"
            >
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem,
              eius reprehenderit eos corrupti commodi magni quaerat ex numquam.
            </q-card-section>
          </q-card>
        </q-expansion-item>
        <q-separator color="accent" class="q-mt-lg q-mb-lg" inset />
        <q-expansion-item
          expand-separator
          class="t6 text-black sm:text-xl lg:text-2xl md:text-2xl"
          label="What is your target audience?"
          :header-inset-level="1.3"
          :content-inset-level="1.3"
          group="groupA"
        >
          <q-card>
            <q-card-section
              class="text-grey-8 sm:text-xl md:text-xl md:w-[95%]"
            >
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem,
              eius reprehenderit eos corrupti commodi magni quaerat ex numquam.
            </q-card-section>
          </q-card>
        </q-expansion-item>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "QuestionsComp",
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
