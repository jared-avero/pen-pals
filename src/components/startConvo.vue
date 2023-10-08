<script setup lang="ts">
defineProps<{}>()
</script>

<template>
  <form>
    <div class="name-div">
      <label for="user-name" value="Name">Name</label>
      <input type="text" class="name" id="user-name" name="user-name" />
    </div>
    <div class="subject-div">
      <label for="subject" value="Subject">Subject</label>
      <input type="text" class="subject" id="subject" name="subject" />
    </div>
    <div class="introduction-div">
      <label for="intro" value="Introduction">Introduction</label>
      <textarea name="intro" id="intro" cols="25" rows="5"></textarea>
    </div>
  </form>
</template>

<style scoped>

</style>