<template>
  <div>
    <!-- Header Section -->
    <div class="bg-btn w-full">
      <div class="container flex w-full mx-auto bg-btn text-txt1 justify-around items-center py-4">
        <div>
          <h1 class="text-3xl font-bold">Modern</h1>
        </div>
        <div>
          
            <ul class="flex space-x-4">
              <li><nuxt-link to="/">Home</nuxt-link></li>
              <li><nuxt-link to="">About</nuxt-link></li>
              <li><nuxt-link to="">Team</nuxt-link></li>
              <li><nuxt-link to="">Contact Us</nuxt-link></li>
            </ul>
          
        </div>
      </div>
    </div>

    <main class="container mx-auto py-8">
      <section class="text-center mb-8">
        <h2 class="text-4xl font-semibold mb-4">Welcome to the Modern Chicken Coop Project</h2>
        <p class="text-lg text-gray-700">
          Discover innovative solutions for sustainable poultry farming with improved ventilation,
          environmental efficiency, and enhanced poultry welfare.
        </p>
      </section>

      <!-- About Section -->
      <section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-8">
        <div>
          <h3 class="text-2xl font-bold mb-4">About the Project</h3>
          <p class="text-gray-700">
            Our project addresses challenges in poultry farming with innovative designs for improved air quality,
            waste management, and overall sustainability, using locally available materials.
          </p>
        </div>
        <div>
          <img
            src="../Alabama Chicken.jpg"
            alt="Modern Chicken Coop"
            class="w-full rounded-lg shadow-md"
          />
        </div>
      </section>

      <!-- Team Section -->
      <section class="mb-8">
        <h3 class="text-2xl font-bold mb-4">Team Members</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
          <div class="p-4 bg-gray-100 rounded-lg shadow-md">
            <h4 class="font-semibold text-lg">John Doe</h4>
            <p class="text-gray-600">Lead Engineer</p>
          </div>
          <div class="p-4 bg-gray-100 rounded-lg shadow-md">
            <h4 class="font-semibold text-lg">Jane Smith</h4>
            <p class="text-gray-600">Software Developer</p>
          </div>
          <div class="p-4 bg-gray-100 rounded-lg shadow-md">
            <h4 class="font-semibold text-lg">Ahmed Ali</h4>
            <p class="text-gray-600">Mechanical Designer</p>
          </div>
        </div>
      </section>

      <!-- Contact Section -->
      <section class="mb-8">
        <h3 class="text-2xl font-bold mb-4">Contact Us</h3>
        <form class="space-y-4">
          <div>
            <label for="name" class="block text-gray-700">Name</label>
            <input
              id="name"
              type="text"
              class="w-full border-gray-300 rounded-lg shadow-sm focus:ring focus:ring-blue-300"
            />
          </div>
          <div>
            <label for="email" class="block text-gray-700">Email</label>
            <input
              id="email"
              type="email"
              class="w-full border-gray-300 rounded-lg shadow-sm focus:ring focus:ring-blue-300"
            />
          </div>
          <div>
            <label for="message" class="block text-gray-700">Message</label>
            <textarea
              id="message"
              rows="4"
              class="w-full border-gray-300 rounded-lg shadow-sm focus:ring focus:ring-blue-300"
            ></textarea>
          </div>
          <button
            type="submit"
            class="bg-blue-700 text-white py-2 px-4 rounded-lg shadow hover:bg-blue-800"
          >
            Send Message
          </button>
        </form>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <div class="text-black font-sans">
        <div>
          <h4>Follow Us</h4>
          <a href="">Facebook</a>
          <a href="">Instagram</a>
          <a href="">Twitter</a>
        </div>
        <div>
          <a href="">About Us</a>
          <a href="">Terms of Service</a>
          <a href="">Privacy Policy</a>
          <a href="">Returns & Refunds</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>
