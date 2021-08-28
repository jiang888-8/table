<template>
  <div>
    <jd-table>
      <template v-slot:name='scope'>
        <h3>{{scope.row}}</h3>
      </template>
      <template v-slot:age='scope'>
        <h3>{{scope.row}}</h3>
      </template>
      <template v-slot:img='scope'>
        <img :src="scope.row" alt="">
      </template>
    </jd-table>
  </div>
</template>

<script>
import jdTable from './components/jd_table.vue'
export default {
  data () {
    return {

    }
  },

  components: {
    jdTable
  },

  created () {

  },

  methods: {

  }
}
</script>

<style scoped>

</style>
