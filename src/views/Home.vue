<template>
  <div class="">
    <header class="bg-blue-900 h-60">
      <h1 class="text-3xl font-bold text-white flex justify-center items-center py-6">Expense Manager</h1>
      <p class="text-white font-bold text-xl">Hello Tawakalitu</p>
    </header>
    <div class=" bg-white -mt-14 rounded-t-3xl">
      <Expenses />
    </div>
    <div></div>
  </div>
</template>

<script>
// @ is an alias to /src
import Expenses from '@/components/Expenses.vue'

export default {
  name: 'Home',
  components: {
    Expenses
  },
  data(){
    return {

    }
  }
}
</script>
