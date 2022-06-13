<template>
  <div class="home">
    <DataTable/>
  </div>
</template>

<script>
// @ is an alias to /src
import DataTable from '@/components/DataTable.vue'

export default {
  name: 'HomeView',
  components: {
    DataTable
  }
}
</script>
