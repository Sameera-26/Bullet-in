<template>
  <q-page>
    <div class="q-pa-md q-mx-xl q-py-xl q-mb-xl q-space-x-lg q-md:w-1/2">
      <div class="ti text-left text-primary text-h3">
        Make You Product Upto Date With our Latest CVE's Database.
      </div>
      <div class="t2 text-left text-grey-8 text-body1 q-py-md q-md:w-1/2">
        Purchase a plan according to your need and make sure your system is upto
        date with latest path of vulnerability.
      </div>
      <div class="flex">
        <q-img
          src="https://seekvectorlogo.com/wp-content/uploads/2017/12/microsoft-vector-logo.png"
          style="height: 20px; max-width: 100px"
          class="responsive"
        />
        <q-img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJeZIPvUv8zAc9pW0pO8_dBeMI5BYl7jcrD5FZsau-iYvUFxn8bIqA7SvfdtGa01x5sxM&usqp=CAU"
          style="height: 28px; max-width: 90px"
          class="responsive q-mx-sm"
        />
        <q-img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTW0HW6OXboG2JNSQ1qDop4WDYUbhfEVdtGFWVaJQEks-6s7r3RudxFiUyBHx-ik1TybXQ&usqp=CAU"
          style="height: 30px; max-width: 70px"
          class="responsive q-mx-sm"
        />
        <q-img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Microsoft_Office_2013-2019_logo_and_wordmark.svg/1024px-Microsoft_Office_2013-2019_logo_and_wordmark.svg.png"
          style="height: 20px; max-width: 80px"
          class="responsive q-mx-md"
        />
        <div class="ti text-primary text-weight-bold q-mx-xs">
          view more vendors
        </div>
        <q-btn
          color="primary"
          size="sm"
          icon="fa solid fa-right-long"
          flat
          class="q-mb-xl"
        ></q-btn>
      </div>
    </div>

    <div class="flex flex-row q-mx-xl">
      <img
        src="~assets/workk.svg"
        class="flex flex-row"
        style="height: 400px; max-width: 400px"
      />
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
<style>
.ti {
  font-family: "Sen-bold";
  font-weight: bold;
  max-width: 40%;
}
.t2 {
  font-family: "Sen";
  font-weight: bold;
  max-width: 42%;
}
</style>
