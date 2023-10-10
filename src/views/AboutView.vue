<script setup>
import '../styles/index.css'

const openAlert = () => {
  window.alert("clicked")
}
</script>

<template>
  <main>
    <div class="react-container">
      <h2>Loans Manager</h2>
      <button class="project-button" @click="openAlert">Add loans</button>
    </div>
  </main>
</template>
