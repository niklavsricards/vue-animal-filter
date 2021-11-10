<template>
  <div class="filters">
    <FilterButton v-for="item in buttonFilterItems" :item="item" :key="item" />
  </div>
</template>

<script>
import FilterButton from "@/components/FilterButton";

export default {
  name: 'Filters',
  components: {
    FilterButton
  },
  data: () => ({
    buttonFilterItems: ['All', 'Cats', 'Dogs', 'Birds', 'Mice']
  })
}
</script>

<style scoped>
  .filters {
    margin-top: 50px;
  }
</style>
