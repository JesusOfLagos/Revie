<template>
  <div class="min-h-screen bg-gray-100">
    <!-- Hero section -->
    <section class="bg-blue-600 py-20 text-white text-center">
      <div class="container mx-auto">
        <h1 class="text-4xl font-bold mb-4">Welcome to Our Landing Page</h1>
        <p class="text-lg mb-8">A simple and beautiful Vue.js landing page with Tailwind CSS.</p>
        <a href="#features" class="bg-white text-blue-600 py-2 px-6 rounded-full hover:bg-blue-100 hover:text-blue-700 transition-all duration-200">Learn More</a>
      </div>
    </section>

    <!-- Features section -->
    <section id="features" class="py-16">
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">Features</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Feature 1 -->
          <div class="bg-white shadow-lg rounded-lg p-6">
            <i class="text-3xl text-blue-600 mb-4 fas fa-check-circle"></i>
            <h3 class="text-xl font-bold mb-2">Feature 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, quam eu varius dictum, justo ex semper augue.</p>
          </div>

          <!-- Feature 2 -->
          <div class="bg-white shadow-lg rounded-lg p-6">
            <i class="text-3xl text-blue-600 mb-4 fas fa-check-circle"></i>
            <h3 class="text-xl font-bold mb-2">Feature 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, quam eu varius dictum, justo ex semper augue.</p>
          </div>

          <!-- Feature 3 -->
          <div class="bg-white shadow-lg rounded-lg p-6">
            <i class="text-3xl text-blue-600 mb-4 fas fa-check-circle"></i>
            <h3 class="text-xl font-bold mb-2">Feature 3</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, quam eu varius dictum, justo ex semper augue.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact form section -->
    <section class="bg-blue-600 py-16 text-white">
      <div class="container mx-auto">
        <h2 class="text-3xl font-bold text-center mb-8">Contact Us</h2>
        <div class="max-w-lg mx-auto">
          <form class="flex flex-col">
            <input type="text" class="bg-white text-gray-800 rounded-lg p-3 mb-4" placeholder="Name">
            <input type="email" class="bg-white text-gray-800 rounded-lg p-3 mb-4" placeholder="Email">
            <textarea class="bg-white text-gray-800 rounded-lg p-3 mb-4" rows="4" placeholder="Message"></textarea>
            <button type="submit" class="bg-white text-blue-600 py-2 px-6 rounded-full hover:bg-blue-100 hover:text-blue-700 transition-all duration-200">Send Message</button>
          </form>
        </div>
      </div>
    </section>

    <!-- Footer section -->
    <footer class="bg-gray-800 py-6 text-white text-center">
      <p>&copy; 2023 Your Company. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';
</style>
