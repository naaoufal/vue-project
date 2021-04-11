<template>
  <div class="home">
    <addOne />
  </div>
</template>

<script>
import addOne from '@/components/addOne'
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    addOne,
  },
};
</script>
