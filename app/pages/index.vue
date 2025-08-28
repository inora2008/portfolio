<script setup lang="ts">

</script>

<template>
  <!-- Hero Section -->
  <section id="home" class="relative text-center py-20 bg-gradient-to-r from-blue-500 to-indigo-700 text-white">
    <div class="absolute inset-0 bg-black opacity-20"></div>
    <div class="relative max-w-4xl mx-auto px-4">
      <h2 class="text-4xl md:text-5xl font-bold mb-4 animate-pulse">Welcome to My Portfolio</h2>
      <p class="text-xl mb-6">I am Inora, an 11th-grade student at a lycee for gifted students.</p>
      <div class="flex justify-center gap-4 mt-8">
        <a href="#projects" class="border-2 border-white text-white px-6 py-3 rounded-lg hover:bg-white hover:text-primary transition shadow-md">See My Work</a>
        <a href="#contact" class="border-2 border-white text-white px-6 py-3 rounded-lg hover:bg-white hover:text-primary transition">Contact Me</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 bg-white">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="text-3xl font-bold mb-6 text-center">About Me</h3>
      <div class="flex flex-col md:flex-row items-center gap-8">
        <div class="w-full md:w-1/3">
          <div class="rounded-full bg-gray-200 w-48 h-48 mx-auto overflow-hidden shadow-lg">
            <img src="/img/about%20me.png" alt="Inora" class="w-full h-full object-cover">
          </div>
        </div>
        <div class="w-full md:w-2/3">
          <p class="text-gray-700 leading-relaxed mb-4">
            My name is Inora, an 11th-grade student passionate about IT and programming. I enjoy learning new technologies and solving problems that develop my logic and creativity. In my free time, I like cooking, playing basketball, reading, and playing guitar. My favorite subjects are algebra, computer science, and chemistry..
          </p>
          <p class="text-gray-700 leading-relaxed mb-4">
            I also participate in volunteer projects because I want to help people and be part of a team. My goal is to become a FLEX program finalist and one of the best programmers. This portfolio helps me grow and find new opportunities.
          </p>
          <div class="flex gap-4 mt-6">
            <a href="#" class="text-primary hover:text-secondary">
              <i class="fab fa-github fa-2x"></i>
            </a>
            <a href="#" class="text-primary hover:text-secondary">
              <i class="fab fa-linkedin fa-2x"></i>
            </a>
            <a href="#" class="text-primary hover:text-secondary">
              <i class="fab fa-twitter fa-2x"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="Hobbies & Skills" class="py-20 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4">
      <h3 class="text-3xl font-bold mb-12 text-center">My Hobbies & Skills</h3>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-react text-4xl text-blue-500 mb-2"></i>
          <h4 class="font-semibold">Playing guitar</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-node-js text-4xl text-green-600 mb-2"></i>
          <h4 class="font-semibold">Volunteer work</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-js-square text-4xl text-yellow-500 mb-2"></i>
          <h4 class="font-semibold">Playing basketball</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fas fa-database text-4xl text-blue-700 mb-2"></i>
          <h4 class="font-semibold">Teamwork</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-css3-alt text-4xl text-blue-400 mb-2"></i>
          <h4 class="font-semibold">Cooking</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-html5 text-4xl text-orange-500 mb-2"></i>
          <h4 class="font-semibold">Leadership skills</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fab fa-git-alt text-4xl text-red-500 mb-2"></i>
          <h4 class="font-semibold">Reading books</h4>
        </div>
        <div class="bg-white p-4 rounded shadow text-center">
          <i class="fas fa-server text-4xl text-green-400 mb-2"></i>
          <h4 class="font-semibold">Communication skills</h4>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-20 bg-white">
    <div class="max-w-6xl mx-auto px-4">
      <h3 class="text-3xl font-bold mb-12 text-center">My Achievements</h3>
      <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">

        <!-- Project Card 1 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition transform hover:-translate-y-2">
          <div class="h-48 overflow-hidden">
            <img src="/img/enviromen.png" alt="NextGen Environmental Summit" class="w-full h-full object-cover">
          </div>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-2">NextGen Environmental Summit</h4>
            <p class="text-gray-600 mb-4">A transformative five-day program for aspiring changemakers who are passionate about the planet and eager to gain hands-on experience in real-world environmental action.</p>
          </div>
        </div>

        <!-- Project Card 2 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition transform hover:-translate-y-2">
          <div class="h-48 overflow-hidden">
            <img src="data:image/jpeg;base64,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" alt="Codding For Girl " class="w-full h-full object-cover">
          </div>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-2">Codding For Girl</h4>
            <p class="text-gray-600 mb-4">A one-month course that introduced me to the basics of programming. I learned how to write simple code and build small projects. This experience motivated me to keep growing in tech.</p>

          </div>
        </div>

        <!-- Project Card 3 -->
        <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition transform hover:-translate-y-2">
          <div class="h-48 overflow-hidden">
            <img src="/img/math.png" alt="Math Olympiad" class="w-full h-full object-cover">
          </div>
          <div class="p-6">
            <h4 class="text-xl font-bold mb-2">Math Olympiad</h4>
            <p class="text-gray-600 mb-4">I participated in a school-level Math Olympiad and won 3rd place. It was a great opportunity to challenge myself and improve my problem-solving skills.</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 bg-gray-50">
    <div class="max-w-3xl mx-auto px-4">
      <h3 class="text-3xl font-bold mb-12 text-center">Contact Me</h3>
      <form class="bg-white p-8 rounded-lg shadow-md space-y-6">
        <div>
          <label for="name" class="block text-gray-700 font-semibold mb-2">Name</label>
          <input type="text" id="name" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary" placeholder="Your Name" required>
        </div>
        <div>
          <label for="email" class="block text-gray-700 font-semibold mb-2">Email</label>
          <input type="email" id="email" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary" placeholder="you@example.com" required>
        </div>
        <div>
          <label for="message" class="block text-gray-700 font-semibold mb-2">Message</label>
          <textarea id="message" rows="5" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary" placeholder="Your message..." required></textarea>
        </div>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-indigo-600 transition w-full">Send Message</button>
      </form>
    </div>
  </section>
</template>

<style scoped>

</style>