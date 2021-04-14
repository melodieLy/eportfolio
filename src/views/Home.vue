<template>
  <div>
    <div class="firstPage">
      <img src="@/assets/avatars.svg" height="550">
      <div id="jobTitle">fzefez</div>    
    </div>
    <mainHome/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import MainHome from "@/components/MainHome.vue";
@Component({
  components: {
    MainHome
  }
})
export default class Home extends Vue {}
</script>
