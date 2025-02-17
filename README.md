<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script
      src="https://kit.fontawesome.com/a076d05399.js"
      crossorigin="anonymous"
    ></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Akash's Portfolio</title>
  </head>
  <body class="bg-gradient-to-r from-cyan-500 to-yellow-500 text-white">
    <header class="text-center py-8">
      <div class="flex flex-col items-center">
        <img src="./assets/akash.jpg" class="w-32 h-32 rounded-full border-4 border-white shadow-lg" />


        <h1 class="text-3xl font-bold mt-4">Akash</h1>
        <p class="text-lg">Web Developer | BCA Student | Gamer</p>
      </div>
    </header>

    <nav class="bg-gray-900 py-4 sticky top-0 w-full shadow-lg">
      <ul class="flex flex-wrap justify-center space-x-4 md:space-x-8">
        <li>
          <a href="#about" class="text-white hover:text-yellow-400 transition"
            >About Me</a
          >
        </li>
        <li>
          <a
            href="#education"
            class="text-white hover:text-yellow-400 transition"
            >Education</a
          >
        </li>
        <li>
          <a
            href="#projects"
            class="text-white hover:text-yellow-400 transition"
            >Projects</a
          >
        </li>
        <li>
          <a href="#skills" class="text-white hover:text-yellow-400 transition"
            >Skills</a
          >
        </li>
        <li>
          <a href="#contact" class="text-white hover:text-yellow-400 transition"
            >Contact</a
          >
        </li>
      </ul>
    </nav>

    <section
      id="about"
      class="max-w-4xl mx-auto bg-white text-gray-900 p-6 mt-6 rounded-lg shadow-md"
    >
      <h2 class="text-2xl font-bold mb-2">About Me</h2>
      <p>
        I am Akash, a 22-year-old BCA student at Galgotias University. I love
        coding and building web applications. My interests include web
        development, problem-solving, and learning new technologies.
      </p>
    </section>

    <section
      id="education"
      class="max-w-4xl mx-auto bg-white text-gray-900 p-6 mt-6 rounded-lg shadow-md"
    >
      <h2 class="text-2xl font-bold mb-2">Education</h2>
      <table class="w-full border-collapse border border-gray-300 text-center">
        <tr class="bg-gray-200">
          <th class="border p-2">Qualification</th>
          <th class="border p-2">Board</th>
          <th class="border p-2">Percentage</th>
        </tr>
        <tr>
          <td class="border p-2">BCA</td>
          <td class="border p-2">Galgotias University</td>
          <td class="border p-2">Currently Pursuing</td>
        </tr>
      </table>
    </section>

    <section
      id="projects"
      class="max-w-4xl mx-auto bg-white text-gray-900 p-6 mt-6 rounded-lg shadow-md"
    >
      <h2 class="text-2xl font-bold mb-2">Projects</h2>
      <ul class="list-disc pl-6">
        <li>
          <strong>Portfolio Website:</strong> Built using HTML, CSS, and
          JavaScript.
        </li>
        <li>
          <strong>Quiz Game:</strong> A web-based quiz game using JavaScript.
        </li>
        <li>
          <strong>Calculator:</strong> A fully functional calculator using
          JavaScript.
        </li>
        <li>
          <strong>Calculator in C:</strong> A console-based arithmetic
          calculator.
        </li>
      </ul>
    </section>

    <section
      id="skills"
      class="max-w-4xl mx-auto bg-white text-gray-900 p-6 mt-6 rounded-lg shadow-md"
    >
      <h2 class="text-2xl font-bold mb-2">Technical Skills</h2>
      <div class="flex flex-wrap justify-center gap-4">
        <span class="bg-blue-500 text-white px-4 py-2 rounded-lg shadow"
          >HTML</span
        >
        <span class="bg-blue-500 text-white px-4 py-2 rounded-lg shadow"
          >CSS</span
        >
        <span class="bg-blue-500 text-white px-4 py-2 rounded-lg shadow"
          >JavaScript</span
        >
        <span class="bg-blue-500 text-white px-4 py-2 rounded-lg shadow"
          >C</span
        >
      </div>
    </section>

    <section
      id="contact"
      class="max-w-4xl mx-auto bg-white text-gray-900 p-6 mt-6 rounded-lg shadow-md"
    >
      <h2 class="text-2xl font-bold mb-2">Contact Info</h2>
      <p>
        <strong>Email:</strong>
        <a href="https://mail.google.com/mail/u/0/" class="text-blue-500"
          >ajha03481@gmail.com</a
        >
      </p>
      <p>
        <strong>x:</strong>
        <a href="https://x.com/" class="text-blue-500"
          >https://x.com/Akash88code</a
        >
      </p>
    </section>

    <footer class="text-center py-4 mt-6 bg-gray-900 text-white">
      <p>&copy; 2025 Akash. All rights reserved.</p>
    </footer>
  </body>
</html>
