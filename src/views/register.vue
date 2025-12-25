<script setup>
import { ref } from 'vue'

const name = ref('')
const email = ref('')
const password = ref('')
</script>

<template>
  <div class="p-6">
    <h1 class="text-xl font-bold mb-4">Register</h1>

    <input v-model="name" placeholder="Nama" class="border block mb-2 px-3 py-2" />
    <input v-model="email" placeholder="Email" class="border block mb-2 px-3 py-2" />
    <input v-model="password" type="password" placeholder="Password" class="border block mb-4 px-3 py-2" />

    <button class="bg-green-500 text-white px-4 py-2 rounded">
      Register
    </button>
  </div>
</template>
