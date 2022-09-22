<template>
  <q-page>
    <div class="mx-16">
      <IntroComp />
    </div>
    <PlatformsComp />
    <BusinessComp />
    <QuestionsComp />
    <q-separator color="accent" class="q-mt-lg q-mb-lg content-center" inset />

    <EndingComp />
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import IntroComp from "../components/IntroComp.vue";
import PlatformsComp from "../components/PlatformsComp.vue";
import BusinessComp from "../components/BusinessComp.vue";
import QuestionsComp from "../components/QuestionsComp.vue";
import EndingComp from "../components/EndingComp.vue";
export default defineComponent({
  name: "IndexPage",
  components: {
    IntroComp,
    PlatformsComp,
    BusinessComp,
    EndingComp,
    QuestionsComp,
  },
});
</script>
<style></style>
