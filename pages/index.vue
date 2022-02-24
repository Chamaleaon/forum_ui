<template>
  <div>
    <div v-for="i in 20" :key="i" class="p-2 mb-2 rounded bg-purple-500">
      {{ i }}. Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur
      officiis nesciunt, ut provident, accusantium ad natus ullam reprehenderit
      molestias suscipit explicabo, soluta minus necessitatibus. Ratione
      corporis inventore maxime incidunt dolore?
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
