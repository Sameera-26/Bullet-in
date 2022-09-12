<template>
  <q-layout view="lHh Lpr lFf">
    <q-header>
      <q-toolbar class="bg-white text-primary text-h4 title q-pa-md q-px-xl ">
        <div class="flex flex-row q-pa-md q-mb-xl">
          <q-title class="text-primary">Bullet</q-title>
          <q-title class="text-black">-In </q-title>
        </div>
        <q-space />
                  <!-- MENU ITEMS -->
                  <div class="gt-sm">
                <!-- hidden for medium screens -->
                <div class= "text-black text-h6 space-x-12">
                <a href="#" class="hover:text-secondary">Home</a>
                <a href="#" class="hover:text-secondary">Vendor</a>
                <a href="#" class="hover:text-secondary">Pricing</a>
                <a href="#" class="hover:text-secondary">Contact Us</a>
                <a href="#" class="hover:text-secondary">About Us</a>
              </div>
            </div>

            <q-btn 
            color="primary"
                size="md"
                icon="fa  fa-bars"
                flat
                class=" mx-4 lt-md mb-10 bg-grey-2 h-14">
        <q-menu auto-close 
        transition-show="jump-down"
          transition-hide="jump-up">
          <q-list class="text-h6 text-center" style="min-width: 500px">
            <q-item clickable>
              <q-item-section>Home</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Vendors</q-item-section>
            </q-item>

            <q-item clickable>
              <q-item-section>Pricing</q-item-section>
            </q-item>

            <q-item clickable>
              <q-item-section>About Us</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Contact Us</q-item-section>
            </q-item>
            

          </q-list>
        </q-menu>
      </q-btn>
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
   @import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";

.title {
  font-family: "Righteous";
  font-weight: "bold";
}
</style>
