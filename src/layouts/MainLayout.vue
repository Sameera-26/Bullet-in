<template>
  <q-layout view="lHh Lpr lFf">
    <q-header>
      <q-toolbar class="bg-white text-primary text-h4 title q-pa-md q-px-xl">
        <div class="flex flex-row q-pa-md">
          <q-title class="text-primary">Bullet</q-title>
          <q-title class="text-black">-In </q-title>
        </div>
        <q-space />

        <!--
        notice shrink property since we are placing it
        as child of QToolbar
      -->
        <q-tabs v-model="tab" shrink class="text-black relative">
          <q-tab name="tab1" label="Home" />
          <q-tab name="tab2" label="Vendor" />
          <q-tab name="tab3" label="Pricing" />
          <q-tab name="tab4" label="Contact Us" />
          <q-tab name="tab5" label="About US" />
        </q-tabs>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "MainLayout",
});
</script>

<style>
.title {
  font-family: "Righteous";
  font-weight: "bold";
}
</style>
