<!-- SignUp.vue -->
<template>
  <div class="min-h-screen flex items-center justify-center bg-gray-100">
    <div class="max-w-md w-full px-6 py-8 bg-white rounded-lg shadow-md">
      <h2 class="text-3xl font-semibold text-center">Sign Up</h2>
      <form @submit.prevent="submitForm">
        <div class="mt-4">
          <label for="name" class="block text-gray-700 font-medium">Name</label>
          <input v-model="name" type="text" id="name" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
        </div>
        <div class="mt-4">
          <label for="email" class="block text-gray-700 font-medium">Email</label>
          <input v-model="email" type="email" id="email" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
        </div>
        <div class="mt-4">
          <label for="password" class="block text-gray-700 font-medium">Password</label>
          <input v-model="password" type="password" id="password" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:border-blue-500 focus:ring focus:ring-blue-200">
        </div>
        <div class="mt-6">
          <button type="submit" class="w-full px-4 py-2 text-base font-semibold text-white bg-blue-600 rounded-md shadow-md hover:bg-blue-700 focus:outline-none focus:ring focus:ring-blue-200">Sign Up</button>
        </div>
      </form>
      <div class="mt-4 text-center">
        <p class="text-sm text-gray-600">Already have an account? <router-link to="/signin" class="text-blue-600 font-semibold">Sign In</router-link></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "",
      email: "",
      password: "",
    };
  },
  methods: {
    submitForm() {
      // You can add your sign-up logic here
      console.log("Sign Up form submitted!");
    },
  },
};
</script>
