<template>
  <v-app
    id="inspire"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <side-bar />
    <right-side-bar/>
    <v-container>

    </v-container>
  </v-app>
</template>

<script>
import SideBar from "@/components/SideBar.vue";
import RightSideBar from "@/components/RightSideBar.vue";
export default {
  components: { SideBar, RightSideBar },
  
};
</script>
