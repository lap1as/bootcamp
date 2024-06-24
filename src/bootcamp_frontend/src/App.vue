<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
  <br/>
  <button @click="increase">Add</button>
    {{ licznik }}
  </main>
</template>

<script>
export default{
  data(){
    return {
      licznik: 0
    }
  },
  methods: {
    increase() {
      this.licznik++
    }
  }
}
</script>
