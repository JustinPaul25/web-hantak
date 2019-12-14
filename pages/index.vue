<template>
  <div class="container mx-auto mt-10">
    <div class="flex mb-4">
      <div class="w-3/5 p-2 text-center border border-teal-500 rounded">

      </div>
      <div class="w-2/5 p-2 text-center">
        <button class="btn bg-teal-500 hover:bg-teal-700 text-white text-3xl font-bold py-3 px-4 rounded">
          Place Bet
        </button>
        <button class="btn bg-teal-500 hover:bg-teal-700 text-white text-3xl font-bold py-3 px-4 rounded mt-5">
          Roll Coin
        </button>
        <p class="font-extrabold text-teal-700 mt-5 text-2xl">Total Heads Bet</p>
        <p class="font-extrabold text-teal-700 text-5xl">{{this.$store.state.bet.heads}}</p>
        <p class="font-extrabold text-teal-700 mt-5 text-2xl">Total Tails Bet</p>
        <p class="font-extrabold text-teal-700 text-5xl">{{this.$store.state.bet.tails}}</p>
        <div class="bg-blue-100 border-t border-b border-teal-500 text-teal-700 px-4 py-3" role="alert">
          <p class="text-sm">App Made by:</p>
          <a href="https://www.justinpaul.cf" target="_blank" class="font-bold">Justin Paul E. Layan</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    methods: {
      
    },

    created() {
      
    }

  }
</script>

<style>
  .btn {
    width: 100%;
  }
</style>
