<template>
  <div class="home">
    <formSection/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import formSection from "@/components/form.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    formSection
  }
};
</script>
