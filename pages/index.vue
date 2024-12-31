<template>
    <div class="bg-[#1a1b20] pt-3">
        <div class="container flex mx-auto bg-blue-100 text-blue-900 mt-4 rounded-md p-4 justify-between items-center">
  <!-- Brand Section -->
  <div>
    <h1 class="text-3xl sm:text-2xl font-bold text-blue-800">Modern</h1>
  </div>

  <!-- Navigation Links -->
  <div>
    <ul class="flex text-md space-x-6 justify-center sm:justify-start">
      <li>
        <nuxt-link
          to="/"
          class="text-blue-900 hover:text-blue-700 transition duration-300 ease-in-out"
        >
          Home
        </nuxt-link>
      </li>
      <li>
        <nuxt-link
          to="#innovative"
          class="text-blue-900 hover:text-blue-700 transition duration-300 ease-in-out"
        >
        Innovative
        </nuxt-link>
      </li>
      <li>
        <nuxt-link
          to="#team"
          class="text-blue-900 hover:text-blue-700 transition duration-300 ease-in-out"
        >
          Team
        </nuxt-link>
      </li>

      <li>
        <nuxt-link
          to="#gallery"
          class="text-blue-900 hover:text-blue-700 transition duration-300 ease-in-out"
        >
          Gallery
        </nuxt-link>
      </li>
      <li>
        <nuxt-link
          to="#contact"
          class="text-blue-900 hover:text-blue-700 transition duration-300 ease-in-out"
        >
          Contact
        </nuxt-link>
      </li>
    </ul>
  </div>
</div>



        <section class="grid grid-cols-1 md:grid-cols-10 w-9/12 mx-auto justify-center place-items-center gap-8 mb-8 p-4">
  <div class="md:col-span-10 lg:col-span-5 flex flex-col justify-center">
    <h1 class="text-3xl md:text-4xl lg:text-5xl text-[#9ce1b6] text-left font-sans font-bold leading-tight">
      Revolutionizing Poultry Farming: Cleaner Air, Smarter Waste Management.
    </h1>
  </div>

  <div class="md:col-span-10 lg:col-span-5">
    <img
      src="/assets/images/new.jpg"
      alt="Modern Chicken Coop"
      class="w-full h-auto max-h-[500px] lg:max-h-[600px] rounded-md shadow-md object-cover"
    />
  </div>
</section>


<section id="innovative" class="py-12 bg-white">
  <div class="container mx-auto">
    <h2 class="text-4xl font-extrabold text-blue-900 text-center mb-8">Innovative Features</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
      <!-- Feature 1: Smart Ventilation System -->
      <div class="bg-blue-50 p-6 rounded-lg shadow-lg transition-all transform hover:scale-105 hover:shadow-xl hover:bg-blue-100">
        <h3 class="text-2xl font-semibold text-blue-800 mb-3">Smart Ventilation System</h3>
        <p class="text-gray-700">Advanced airflow mechanisms for improved air quality.</p>
      </div>

      <!-- Feature 2: Eco-Friendly Waste Management -->
      <div class="bg-blue-50 p-6 rounded-lg shadow-lg transition-all transform hover:scale-105 hover:shadow-xl hover:bg-blue-100">
        <h3 class="text-2xl font-semibold text-blue-800 mb-3">Eco-Friendly Waste Management</h3>
        <p class="text-gray-700">Systems for easy waste collection and disposal.</p>
      </div>

      <!-- Feature 3: Sustainability Focus -->
      <div class="bg-blue-50 p-6 rounded-lg shadow-lg transition-all transform hover:scale-105 hover:shadow-xl hover:bg-blue-100">
        <h3 class="text-2xl font-semibold text-blue-800 mb-3">Sustainability Focus</h3>
        <p class="text-gray-700">Recyclable materials and energy-efficient components.</p>
      </div>

      <!-- Feature 4: Modular Design -->
      <div class="bg-blue-50 p-6 rounded-lg shadow-lg transition-all transform hover:scale-105 hover:shadow-xl hover:bg-blue-100">
        <h3 class="text-2xl font-semibold text-blue-800 mb-3">Modular Design</h3>
        <p class="text-gray-700">Customizable layouts for scalability.</p>
      </div>
    </div>
  </div>
</section>

       
            <!-- <section class="text-center bg-blue-100 py-32">
                <h1 class="text-5xl font-extrabold text-blue-900 mb-4">Modern Chicken House</h1>
                <p class="text-lg text-gray-700">"Clean, Efficient, Sustainable"</p>
                <p class="mt-6 text-gray-600">
                    Introducing innovative solutions for poultry farming to address air quality, waste management, and
                    productivity challenges.
                </p>
            </section> -->
           

  


 






        <!-- <section class="w-9/12 mt-5 mx-auto">
            <h3 class="text-4xl text-[#d3dad1] font-extrabold mb-4">Gallery</h3>
            <div class="relative">
                <div ref="gallerySlider" class="flex overflow-x-auto gap-8 scrollbar-hidden">
                    <div v-for="(image, index) in images" :key="index" class="flex-shrink-0">
                        <h2>{{ image }}</h2>
                        <NuxtImg src="../assets/images/new" alt="Modern Chicken Coop" width="300" height="300"
                            class="rounded-md shadow-md object-cover" />
                    </div>
                </div>
            </div>
        </section> -->

         
 
        <section id="gallery" class="mt-10 mx-auto">
  <div class="container mx-auto text-center">
    <h3 class="text-4xl text-left text-[#d3dad1] font-extrabold mb-6">Gallery</h3>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <div class="group relative">
        <img
          src="/assets/images/new.jpg"
          alt="Demo 1"
          class="rounded-lg shadow-lg object-cover h-150 w-full transition-transform duration-300 ease-in-out transform group-hover:scale-105"
        />
        <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition-opacity duration-300 ease-in-out flex items-center justify-center">
          <p class="text-white text-xl font-bold">Explore Design 1</p>
        </div>
      </div>
      <div class="group relative">
        <img
          src="/assets/images/new.jpg"
          alt="Demo 2"
          class="rounded-lg shadow-lg object-cover h-150 w-full transition-transform duration-300 ease-in-out transform group-hover:scale-105"
        />
        <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition-opacity duration-300 ease-in-out flex items-center justify-center">
          <p class="text-white text-xl font-bold">Explore Design 2</p>
        </div>
      </div>
      <div class="group relative">
        <img
          src="/assets/images/new.jpg"
          alt="Demo 2"
          class="rounded-lg shadow-lg object-cover h-150 w-full transition-transform duration-300 ease-in-out transform group-hover:scale-105"
        />
        <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition-opacity duration-300 ease-in-out flex items-center justify-center">
          <p class="text-white text-xl font-bold">Explore Design 2</p>
        </div>
      </div>
    </div>
    <p class="mt-6 text-[#d3dad1]">Experience the transformation with our advanced chicken house designs.</p>
  </div>
</section>





  <section id="team" class="p-8">
  <div class="container mx-auto">
    <h3 class="text-4xl text-[#d3dad1] font-extrabold mb-4">Team Members</h3>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
      <div
        v-for="member in members"
        :key="member.id"
        class="bg-[#9ce1b6] text-[#0071b6] p-6 rounded-lg shadow-md transform transition-all duration-300 hover:scale-100 hover:rotate-1 hover:shadow-xl hover:bg-[#81cfa0]"
      >
        <h3 class="text-xl font-bold mb-2">{{ member.name }}</h3>
        <p class="text-md text-[#1a1b20]">Id: {{ member.departmentId }}</p>
        <p class="text-md text-[#1a1b20]">Role: {{ member.role }}</p>
        <p class="text-md text-[#1a1b20]">Phone: {{ member.phone }}</p>
        <p class="text-md text-[#1a1b20]">Email: {{ member.otherContacts }}</p>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="w-9/12 mx-auto px-6 py-16 bg-inherit">
  <h3 class="text-4xl text-white text-left font-extrabold mb-6">Contact Us</h3>
  
  <div class="w-full mx-auto bg-[#1f2937] p-8 rounded-lg shadow-lg transform transition duration-300 hover:scale-105">
    <!-- Contact Form -->
    <form @submit.prevent="handleSubmit">
      <div class="space-y-6">

        <!-- Name -->
        <div>
          <label for="name" class="block text-lg font-semibold text-[#d3dad1]">Your Name</label>
          <input type="text" id="name" v-model="form.name" required
            class="w-full px-4 py-3 bg-[#2c3747] text-[#f9f9f9] border-2 border-transparent rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:outline-none"
            placeholder="Enter your name" />
        </div>

        <!-- Email -->
        <div>
          <label for="email" class="block text-lg font-semibold text-[#d3dad1]">Your Email</label>
          <input type="email" id="email" v-model="form.email" required
            class="w-full px-4 py-3 bg-[#2c3747] text-[#f9f9f9] border-2 border-transparent rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:outline-none"
            placeholder="Enter your email" />
        </div>

        <!-- Message -->
        <div>
          <label for="message" class="block text-lg font-semibold text-[#d3dad1]">Your Message</label>
          <textarea id="message" v-model="form.message" required rows="6"
            class="w-full px-4 py-3 bg-[#2c3747] text-[#f9f9f9] border-2 border-transparent rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:outline-none"
            placeholder="Write your message here"></textarea>
        </div>

        <!-- Submit Button -->
        <div class="">
          <button type="submit"
            class="py-3 px-6 font-semibold text-white bg-[#1D4ED8] rounded-md shadow-md hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition duration-200">
            Send Message
          </button>
        </div>
      </div>
    </form>
  </div>
</section>

<footer id="footer" class="bg-blue-100 text-blue-900 py-7 mt-8">
  <div class="container mx-auto flex flex-wrap justify-between items-center">
    <!-- Left Section: Branding -->
    <div class="mb-4 sm:mb-0">
      <h1 class="text-3xl font-bold text-blue-900">Modern</h1>
      <p class="text-lg text-blue-800">© 2024 Modern, All Rights Reserved</p>
    </div>

    <!-- Middle Section: Navigation Links -->
    <div class="mb-4 sm:mb-0 text-lg">
      <ul class="flex space-x-8">
        <li><nuxt-link to="/" class="hover:underline text-blue-800">Home</nuxt-link></li>
        <li><nuxt-link to="/about" class="hover:underline text-blue-800">About</nuxt-link></li>
        <li><nuxt-link to="/team" class="hover:underline text-blue-800">Team</nuxt-link></li>
        <li><nuxt-link to="/contact" class="hover:underline text-blue-800">Contact Us</nuxt-link></li>
      </ul>
    </div>

    <!-- Right Section: Social Media Links -->
    <div class="flex space-x-6">
      <a href="https://facebook.com" target="_blank" class="text-blue-600 hover:text-blue-800">
        <i class="fab fa-facebook-f text-2xl"></i>
      </a>
      <a href="https://twitter.com" target="_blank" class="text-blue-600 hover:text-blue-800">
        <i class="fab fa-twitter text-2xl"></i>
      </a>
      <a href="https://linkedin.com" target="_blank" class="text-blue-600 hover:text-blue-800">
        <i class="fab fa-linkedin-in text-2xl"></i>
      </a>
    </div>
  </div>
</footer>

    </div>


</template>
<script>

export default {
    data() {
        return {
            images: [
                { src: '/images/new.jpg' },
            ],
            members: [
                {
                    id: 1,
                    name: 'Ephrem Mandefro',
                    departmentId: 'ETS0536/14',
                    role: 'Software Engineer',
                    phone: '+251938413473',
                    otherContacts: 'epahaman48@gmail.com',
                },
                {
                    id: 2,
                    name: 'Yeabsra Alemayehu',
                    departmentId: 'ETS1656/14',
                    role: 'Electrical Engineer',
                    phone: '+251946333013',
                    otherContacts: 'yeabsraalemayehu592@gmail.com',
                },
                {
                    id: 3,
                    name: 'Daniel Fentie',
                    departmentId: 'ETS0284/11',
                    role: 'Mechanical Engineer',
                    phone: '+251983407305',
                    otherContacts: 'danielfentie2022@gmail.com',
                },
                {
                    id: 3,
                    name: 'Eyuel Befkadu',
                    departmentId: 'ETS0611/14',
                    role: 'Environmental Engineer',
                    phone: '+251977746975',
                    otherContacts: 'eyuelbefkaf@gmail.com',
                },
                {
                    id: 3,
                    name: 'Natnael Dagnachew',
                    departmentId: 'ETS1255/14',
                    role: 'Chemical Engineer',
                    phone: '+251988176996',
                    otherContacts: 'natnaelgeberehana@gmail.com',
                },
                {
                    id: 3,
                    name: 'Adoniyas Desalegn',
                    departmentId: 'ETS0125/14',
                    role: 'Electrical Engineer',
                    phone: '+251963039627',
                    otherContacts: 'adonilol708@gmail.com',
                },
                {
                    id: 3,
                    name: 'Meklit Zewude',
                    departmentId: 'ETS1031/14',
                    role: 'Mining Engineer',
                    phone: '+251989923639',
                    otherContacts: 'meklitzewde490@gmail.com',
                },
                {
                    id: 3,
                    name: 'Natnael Asaye',
                    departmentId: 'ETS1230/14',
                    role: 'Civil Engineer',
                    phone: '+251966000160',
                    otherContacts: 'natnaelasaye5@gemail.com',
                },
                {
                    id: 3,
                    name: 'Ewket Lemma',
                    departmentId: '',
                    role: 'Architect',
                    phone: '555-123-4567',
                    otherContacts: 'robert.brown@email.com',
                },

                // Add more members as needed
            ],
            form: {
                name: '',
                email: '',
                message: ''
            }
        };

    },
    methods: {
        handleSubmit() {
            // Here you can handle form submission logic like sending to an API
            alert(`Message from ${this.form.name} received! We will respond shortly.`);
            this.form.name = '';
            this.form.email = '';
            this.form.message = '';
        }
    },
    mounted() {
        const slider = this.$refs.gallerySlider;
        const imageWidth = 300 + 16; // 300px image + 16px gap
        let scrollAmount = 0;

        // Duplicate content ensures seamless scrolling
        setInterval(() => {
            scrollAmount += imageWidth;

            // Reset scroll to start when reaching the end of the original images
            if (scrollAmount >= (this.images.length * imageWidth)) {
                scrollAmount = 0;
                slider.scrollTo({ left: 0 });
            }

            slider.scrollTo({
                left: scrollAmount,
                behavior: "smooth",
            });
        }, 1000); // Adjust interval for auto-scrolling (6 seconds)
    },
};
</script>

<style scoped>
/* Hide scrollbar for cleaner appearance */
.scrollbar-none::-webkit-scrollbar {
    display: none;
}

.scrollbar-none {
    -ms-overflow-style: none;
    /* IE and Edge */
    scrollbar-width: none;
    /* Firefox */
}
</style>
