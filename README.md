<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kelvin's GitHub Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-b from-gray-900 to-gray-800 text-white font-sans">

  <!-- Container -->
  <div class="max-w-6xl mx-auto p-6">

    <!-- Header -->
    <header class="text-center mb-12">
      <h1 class="text-5xl font-extrabold mb-2">Hello, I'm Kelvin 👋</h1>
      <h3 class="text-xl text-yellow-400">Full-Stack Developer | Crafting Scalable Digital Solutions</h3>
    </header>

    <!-- Tech Stack -->
    <section class="bg-gray-800/50 p-6 rounded-xl mb-12">
      <h2 class="text-3xl font-bold mb-4">🛠️ Tech Stack</h2>

      <div class="mb-4">
        <h3 class="font-semibold">Frontend:</h3>
        <div class="flex flex-wrap gap-2 mt-2">
          <span class="bg-red-600 px-3 py-1 rounded-full">HTML5</span>
          <span class="bg-blue-600 px-3 py-1 rounded-full">CSS3</span>
          <span class="bg-yellow-400 text-black px-3 py-1 rounded-full">JavaScript</span>
          <span class="bg-cyan-400 text-black px-3 py-1 rounded-full">React</span>
        </div>
      </div>

      <div class="mb-4">
        <h3 class="font-semibold">Backend:</h3>
        <div class="flex flex-wrap gap-2 mt-2">
          <span class="bg-green-600 px-3 py-1 rounded-full">Node.js</span>
          <span class="bg-purple-600 px-3 py-1 rounded-full">PHP</span>
        </div>
      </div>

      <div class="mb-4">
        <h3 class="font-semibold">Databases:</h3>
        <div class="flex flex-wrap gap-2 mt-2">
          <span class="bg-blue-700 px-3 py-1 rounded-full">MySQL</span>
          <span class="bg-green-700 px-3 py-1 rounded-full">MongoDB</span>
        </div>
      </div>

      <div>
        <h3 class="font-semibold">Tools:</h3>
        <div class="flex flex-wrap gap-2 mt-2">
          <span class="bg-red-500 px-3 py-1 rounded-full">Git</span>
          <span class="bg-blue-500 px-3 py-1 rounded-full">VS Code</span>
        </div>
      </div>
    </section>

    <!-- Projects & Learning -->
    <section class="flex flex-col md:flex-row gap-6 mb-12">
      <div class="flex-1 bg-gradient-to-br from-purple-600 to-pink-600 p-6 rounded-xl shadow-lg">
        <h2 class="text-2xl font-bold mb-3">🔭 Current Projects</h2>
        <ul class="list-disc list-inside space-y-2">
          <li>E-commerce platform (React & Node.js)</li>
          <li>SaaS application with real-time features</li>
          <li>Open-source contributions</li>
        </ul>
      </div>

      <div class="flex-1 bg-gradient-to-br from-blue-600 to-indigo-600 p-6 rounded-xl shadow-lg">
        <h2 class="text-2xl font-bold mb-3">🌱 Learning Goals</h2>
        <ul class="list-disc list-inside space-y-2">
          <li>Microservices Architecture</li>
          <li>AWS Cloud Technologies</li>
          <li>GraphQL implementations</li>
        </ul>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="bg-gray-800/50 p-6 rounded-xl text-center">
      <h2 class="text-3xl font-bold mb-4">📫 Let's Connect</h2>
      <div class="flex flex-wrap justify-center gap-4">
        <a href="https://www.linkedin.com/in/kelvin-kifunda/" target="_blank" class="bg-blue-600 px-4 py-2 rounded-lg hover:bg-blue-700 transition">
          LinkedIn
        </a>
        <a href="mailto:kelvinkifunda.077@gmail.com" class="bg-red-600 px-4 py-2 rounded-lg hover:bg-red-700 transition">
          Email Me
        </a>
        <a href="https://pincodes.github.io/portfolio/" target="_blank" class="bg-green-600 px-4 py-2 rounded-lg hover:bg-green-700 transition">
          Portfolio
        </a>
      </div>
    </section>

    <!-- Footer -->
    <footer class="text-center text-gray-400 mt-12">
      © <span id="year"></span> Kelvin Kifunda. All rights reserved.
    </footer>

  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
