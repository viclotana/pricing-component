<template>
  <c-theme-provider>
    <c-reset />
    <!--Your application goes here -->
    <HelloWorld />
  </c-theme-provider>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>
