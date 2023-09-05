<script setup lang="ts">
import {useCourse} from "~/composables/useCourse";

const course = useCourse();
console.log(course);
</script>

<template>
  <h1>Lesson</h1>
  <p>This is a lesson</p>
</template>

<style scoped>

</style>