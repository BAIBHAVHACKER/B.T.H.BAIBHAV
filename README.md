# B.T.H.BAIBHAV
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   B.T.H - Hackres
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&amp;family=Roboto&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Roboto', sans-serif;
    }
    h1, h2, h3, h4, h5, h6 {
      font-family: 'Orbitron', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-900 text-gray-100 min-h-screen flex flex-col">
  <header class="bg-gray-800 shadow-md">
   <div class="container mx-auto px-6 py-4 flex items-center justify-between">
    <div class="flex items-center space-x-3">
     <img alt="B.T.H logo, stylized letters B T H in neon blue on black background" class="w-12 h-12" height="48" src="https://storage.googleapis.com/a1aa/image/964695f8-d23f-45c0-51b3-ed3f1b37055f.jpg" width="48"/>
     <h1 class="text-3xl font-extrabold tracking-wide">
      B.T.H
     </h1>
    </div>
    <nav class="hidden md:flex space-x-8 text-lg font-semibold">
     <a class="hover:text-cyan-400 transition" href="#home">
      Home
     </a>
     <a class="hover:text-cyan-400 transition" href="#about">
      About
     </a>
     <a class="hover:text-cyan-400 transition" href="#services">
      Services
     </a>
     <a class="hover:text-cyan-400 transition" href="#news">
      News
     </a>
     <a class="hover:text-cyan-400 transition" href="#contact">
      Contact
     </a>
    </nav>
    <button aria-label="Toggle menu" class="md:hidden text-gray-300 hover:text-cyan-400 focus:outline-none" id="menu-btn">
     <i class="fas fa-bars fa-2x">
     </i>
    </button>
   </div>
   <nav aria-label="Mobile menu" class="md:hidden bg-gray-800 px-6 py-4 space-y-4 hidden" id="mobile-menu">
    <a class="block text-lg font-semibold hover:text-cyan-400 transition" href="#home">
     Home
    </a>
    <a class="block text-lg font-semibold hover:text-cyan-400 transition" href="#about">
     About
    </a>
    <a class="block text-lg font-semibold hover:text-cyan-400 transition" href="#services">
     Services
    </a>
    <a class="block text-lg font-semibold hover:text-cyan-400 transition" href="#news">
     News
    </a>
    <a class="block text-lg font-semibold hover:text-cyan-400 transition" href="#contact">
     Contact
    </a>
   </nav>
  </header>
  <main class="flex-grow">
   <section aria-label="Hero section with B.T.H branding and hacker theme" class="relative bg-gray-900 overflow-hidden" id="home">
    <img alt="Futuristic cyber cityscape at night with neon blue and green lights, digital rain effect overlay" class="w-full h-60 sm:h-96 object-cover" height="600" src="https://storage.googleapis.com/a1aa/image/d9432c11-61da-4b49-5004-a3384f6a62ce.jpg" width="1920"/>
    <div class="absolute inset-0 bg-gradient-to-b from-black/70 via-black/50 to-black/70 flex flex-col justify-center items-center px-6 text-center">
     <h2 class="text-4xl sm:text-6xl font-extrabold text-cyan-400 drop-shadow-lg mb-4">
      Welcome to B.T.H
     </h2>
     <p class="max-w-3xl text-gray-300 text-lg sm:text-xl">
      The ultimate hacking resource hub. Explore, learn, and innovate with the best tools and community.
     </p>
     <a class="mt-8 inline-block bg-cyan-500 hover:bg-cyan-600 text-gray-900 font-bold py-3 px-8 rounded-lg shadow-lg transition" href="#services">
      Explore Services
      <i class="fas fa-arrow-right ml-2">
      </i>
     </a>
    </div>
   </section>
   <section aria-labelledby="about-title" class="container mx-auto px-6 py-16" id="about">
    <h2 class="text-4xl font-extrabold text-cyan-400 mb-8 text-center" id="about-title">
     About B.T.H
    </h2>
    <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
     <img alt="Hacker working on multiple computer screens displaying code and cyber security icons in a dark room with neon blue lighting" class="rounded-lg shadow-lg" height="400" src="https://storage.googleapis.com/a1aa/image/a82f05d4-6145-48b3-93ce-79617fdf2afb.jpg" width="600"/>
     <div class="text-gray-300 text-lg space-y-6">
      <p>
       B.T.H (Break The Hack) is a cutting-edge platform dedicated to
            hackers, cybersecurity enthusiasts, and developers. We provide
            comprehensive resources, tutorials, and tools to empower you to
            push the boundaries of technology and security.
      </p>
      <p>
       Our mission is to foster a community where knowledge is shared
            openly and responsibly, helping you stay ahead in the fast-paced
            world of cybersecurity and hacking.
      </p>
      <p>
       Join us to access exclusive content, participate in challenges,
            and connect with like-minded innovators.
      </p>
     </div>
    </div>
   </section>
   <section aria-labelledby="services-title" class="bg-gray-800 py-16" id="services">
    <div class="container mx-auto px-6">
     <h2 class="text-4xl font-extrabold text-cyan-400 mb-12 text-center" id="services-title">
      Our Services
     </h2>
     <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 max-w-7xl mx-auto">
      <div class="bg-gray-900 rounded-lg p-6 flex flex-col items-center text-center shadow-lg hover:shadow-cyan-500/50 transition">
       <i class="fas fa-laptop-code fa-4x text-cyan-400 mb-6">
       </i>
       <h3 class="text-2xl font-bold mb-3">
        Penetration Testing
       </h3>
       <p class="text-gray-300">
        Comprehensive penetration testing services to identify and
              mitigate vulnerabilities in your systems.
       </p>
      </div>
      <div class="bg-gray-900 rounded-lg p-6 flex flex-col items-center text-center shadow-lg hover:shadow-cyan-500/50 transition">
       <i class="fas fa-book-reader fa-4x text-cyan-400 mb-6">
       </i>
       <h3 class="text-2xl font-bold mb-3">
        Tutorials &amp; Guides
       </h3>
       <p class="text-gray-300">
        Step-by-step tutorials and guides covering hacking techniques,
              cybersecurity fundamentals, and advanced topics.
       </p>
      </div>
      <div class="bg-gray-900 rounded-lg p-6 flex flex-col items-center text-center shadow-lg hover:shadow-cyan-500/50 transition">
       <i class="fas fa-network-wired fa-4x text-cyan-400 mb-6">
       </i>
       <h3 class="text-2xl font-bold mb-3">
        Network Security
       </h3>
       <p class="text-gray-300">
        Tools and consulting to secure your network infrastructure from
              attacks and unauthorized access.
       </p>
      </div>
      <div class="bg-gray-900 rounded-lg p-6 flex flex-col items-center text-center shadow-lg hover:shadow-cyan-500/50 transition">
       <i class="fas fa-users-cog fa-4x text-cyan-400 mb-6">
       </i>
       <h3 class="text-2xl font-bold mb-3">
        Community &amp; Forums
       </h3>
       <p class="text-gray-300">
        Join our active community forums to discuss, share, and learn
              from fellow hackers and security experts.
       </p>
      </div>
     </div>
    </div>
   </section>
   <section aria-labelledby="news-title" class="container mx-auto px-6 py-16" id="news">
    <h2 class="text-4xl font-extrabold text-cyan-400 mb-12 text-center" id="news-title">
     Latest News
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-10 max-w-7xl mx-auto">
     <article class="bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
      <img alt="Cybersecurity conference 2024 banner with futuristic digital globe and network lines" class="w-full h-48 object-cover" height="350" src="https://storage.googleapis.com/a1aa/image/deab6225-f159-40be-ac4f-359c97977dfa.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-bold text-cyan-400 mb-2">
        Cybersecurity Conference 2024 Announced
       </h3>
       <p class="text-gray-300 flex-grow">
        Join industry leaders and experts at the biggest cybersecurity
              conference of the year. Learn about the latest trends and tools.
       </p>
       <time class="mt-4 text-sm text-gray-500" datetime="2024-06-15">
        June 15, 2024
       </time>
      </div>
     </article>
     <article class="bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
      <img alt="New penetration testing tool interface screenshot with dark theme and code snippets" class="w-full h-48 object-cover" height="350" src="https://storage.googleapis.com/a1aa/image/66f2bd00-250e-42ae-2812-0dc2a94ec3d2.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-bold text-cyan-400 mb-2">
        New Penetration Testing Tool Released
       </h3>
       <p class="text-gray-300 flex-grow">
        We launched a powerful new tool to help security professionals
              automate vulnerability assessments with ease.
       </p>
       <time class="mt-4 text-sm text-gray-500" datetime="2024-05-30">
        May 30, 2024
       </time>
      </div>
     </article>
     <article class="bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
      <img alt="Group of diverse hackers celebrating at a community hackathon event with trophies and laptops" class="w-full h-48 object-cover" height="350" src="https://storage.googleapis.com/a1aa/image/00cf4acd-373d-4a63-9ad3-a2b7780b5956.jpg" width="600"/>
      <div class="p-6 flex flex-col flex-grow">
       <h3 class="text-xl font-bold text-cyan-400 mb-2">
        Community Hackathon Winners Announced
       </h3>
       <p class="text-gray-300 flex-grow">
        Congratulations to the winners of our latest hackathon! See their
              innovative projects and ideas that impressed the judges.
       </p>
       <time class="mt-4 text-sm text-gray-500" datetime="2024-05-10">
        May 10, 2024
       </time>
      </div>
     </article>
    </div>
   </section>
   <section aria-labelledby="contact-title" class="bg-gray-800 py-16" id="contact">
    <div class="container mx-auto px-6 max-w-3xl">
     <h2 class="text-4xl font-extrabold text-cyan-400 mb-10 text-center" id="contact-title">
      Contact Us
     </h2>
     <form action="#" aria-label="Contact form for B.T.H" class="bg-gray-900 rounded-lg p-8 shadow-lg space-y-6" method="POST">
      <div>
       <label class="block mb-2 font-semibold text-gray-300" for="name">
        Name
       </label>
       <input class="w-full rounded-md bg-gray-700 border border-gray-600 text-gray-100 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-cyan-400" id="name" name="name" placeholder="Your full name" required="" type="text"/>
      </div>
      <div>
       <label class="block mb-2 font-semibold text-gray-300" for="email">
        Email
       </label>
       <input class="w-full rounded-md bg-gray-700 border border-gray-600 text-gray-100 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-cyan-400" id="email" name="email" placeholder="you@example.com" required="" type="email"/>
      </div>
      <div>
       <label class="block mb-2 font-semibold text-gray-300" for="message">
        Message
       </label>
       <textarea class="w-full rounded-md bg-gray-700 border border-gray-600 text-gray-100 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-cyan-400" id="message" name="message" placeholder="Write your message here..." required="" rows="5"></textarea>
      </div>
      <button class="w-full bg-cyan-500 hover:bg-cyan-600 text-gray-900 font-bold py-3 rounded-lg transition" type="submit">
       Send Message
      </button>
     </form>
     <div class="mt-12 text-center text-gray-400 space-y-4">
      <p>
       <i class="fas fa-map-marker-alt mr-2 text-cyan-400">
       </i>
       123 Cyber
            Lane, Tech City, TX 75001
      </p>
      <p>
       <i class="fas fa-phone-alt mr-2 text-cyan-400">
       </i>
       +1 (555) 123-4567
      </p>
      <p>
       <i class="fas fa-envelope mr-2 text-cyan-400">
       </i>
       contact@bthhackres.com
      </p>
      <div class="flex justify-center space-x-6 mt-4">
       <a aria-label="Twitter" class="text-gray-400 hover:text-cyan-400 transition" href="https://twitter.com" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-twitter fa-lg">
        </i>
       </a>
       <a aria-label="GitHub" class="text-gray-400 hover:text-cyan-400 transition" href="https://github.com" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-github fa-lg">
        </i>
       </a>
       <a aria-label="LinkedIn" class="text-gray-400 hover:text-cyan-400 transition" href="https://linkedin.com" rel="noopener noreferrer" target="_blank">
        <i class="fab fa-linkedin fa-lg">
        </i>
       </a>
      </div>
     </div>
    </div>
   </section>
  </main>
  <footer class="bg-gray-800 py-6 text-center text-gray-500 text-sm">
   © 2024 B.T.H Hackres. All rights reserved.
  </footer>
  <script>
   const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
