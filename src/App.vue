<template>
  <div class="min-h-screen bg-gray-100">

    
    <nav class="bg-blue-900 text-white shadow-lg">
      <div class="max-w-7xl mx-auto flex justify-between items-center px-6 py-4">

    
        <div class="flex items-center gap-3">
          
          <img
            src="./assets/logo.jpg"
            alt="logo"
            class="w-12 h-12 rounded-full border-2 border-white"
          />

          <div>
            <h1 class="text-2xl font-bold">SOS THS</h1>
            <p class="text-sm text-gray-300">
              Technical High School
            </p>
          </div>
        </div>

        <!-- MENU -->
        <ul class="hidden md:flex gap-8 font-medium">
          <li><a href="#" class="hover:text-yellow-300">Home</a></li>
          <li><a href="#" class="hover:text-yellow-300">About</a></li>
          <li><a href="#" class="hover:text-yellow-300">Programs</a></li>
          <li><a href="#" class="hover:text-yellow-300">Contact</a></li>
        </ul>

      </div>
    </nav>

    
    <section class="bg-blue-900 text-white py-24">
      <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">

        <div>
          <h2 class="text-5xl font-bold leading-tight">
            Welcome To SOS THS
          </h2>

          <p class="mt-6 text-lg text-gray-200">
            A modern technical school empowering students with IT skills,
            innovation, and real-world learning.
          </p>

          <button class="mt-8 bg-yellow-400 text-black px-6 py-3 rounded-lg font-semibold hover:bg-yellow-300">
            Apply Now
          </button>
        </div>

        <div>
         <img
           src="./assets/student.jpg"
           alt="students"
           class="w-[350px] h-[250px] object-cover rounded-2xl shadow-2xl"
/>
        </div>

      </div>
    </section>

    
    <section class="py-20">
      <div class="max-w-7xl mx-auto px-6">

        <h3 class="text-4xl font-bold text-center mb-12">
          Why Choose Us
        </h3>

        <div class="grid md:grid-cols-3 gap-8">

          <div class="bg-white p-8 rounded-2xl shadow-lg">
            <h4 class="text-xl font-bold mb-3">💻 Practical Skills</h4>
            <p class="text-gray-600">
              Learn by doing real projects and hands-on practice.
            </p>
          </div>

          <div class="bg-white p-8 rounded-2xl shadow-lg">
            <h4 class="text-xl font-bold mb-3">🌐 Modern Technology</h4>
            <p class="text-gray-600">
              We teach up-to-date technologies used in industry.
            </p>
          </div>

          <div class="bg-white p-8 rounded-2xl shadow-lg">
            <h4 class="text-xl font-bold mb-3">🎓 Career Ready</h4>
            <p class="text-gray-600">
              Prepare students for jobs, freelancing, and entrepreneurship.
            </p>
          </div>

        </div>

      </div>
    </section>

  
    <footer class="bg-black text-white text-center py-8">
      <h4 class="text-2xl font-bold">SOS THS</h4>
      <p class="text-gray-400 mt-2">Building future tech leaders</p>
      <p class="text-gray-500 mt-4">© 2026 SOS Technical High School</p>
    </footer>

  </div>
</template>

<script setup>

</script>