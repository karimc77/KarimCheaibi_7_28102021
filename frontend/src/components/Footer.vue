<template>
  <footer
    class="bottom-0 w-full bg-gray-600 shadow-lg py-5 backdrop-filter backdrop-blur-sm bg-opacity-100"
  >
    <div
      class="container mx-auto
            flex justify-center mb-5"
    >
      <router-link v-if="status == 'isConnected'" to="/wall">
        <img
          class="object-contain h-10"
          src="../assets/icons/icon-white-navbar.png"
          alt="Groupomania logo"
        />
      </router-link>
      <router-link v-else to="/">
        <img
          class="object-contain h-10"
          src="../assets/icons/icon-white-navbar.png"
          alt="Groupomania logo"
        />
      </router-link>
    </div>
    <div class="flex justify-center">
      <ul class="text-white text-center">
        <li class="flex pb-2 hover:text-red-400">
          <MailIcon class="h-6 w-5 mr-2" />
          <a href="#"> Nous contacter</a>
        </li>
        <li class="flex pb-2 hover:text-red-400">
          <AnnotationIcon class="h-6 w-5 mr-2" />
          <a href="#"> Mentions légales</a>
        </li>
      </ul>
    </div>
  </footer>
</template>

<script>
import { mapState } from "vuex";

import { MailIcon, AnnotationIcon } from "@heroicons/vue/solid";

export default {
  components: { MailIcon, AnnotationIcon },

  computed: {
    ...mapState(["status"]),
  },
};
</script>
