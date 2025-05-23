<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peter Ogbonna - Junior Frontend Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Custom CSS for smooth scrolling behavior */
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light gray background */
            color: #334155; /* Darker text color */
        }
        /* Style for active navigation link (optional, can be added with JS) */
        .nav-link.active {
            font-weight: 600;
            color: #1e40af; /* A darker blue for active state */
        }
        /* Custom scrollbar for better aesthetics */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #e2e8f0;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #94a3b8;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #64748b;
        }
    </style>
</head>
<body class="antialiased">

    <header class="bg-white shadow-md fixed w-full z-10 py-4">
        <nav class="container mx-auto px-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-800 rounded-md p-2 hover:bg-gray-100 transition duration-300">Peter Ogbonna</a>
            
            <div class="space-x-6">
                <a href="#about" class="nav-link text-gray-600 hover:text-blue-700 transition duration-300 rounded-md p-2 hover:bg-blue-50">About</a>
                <a href="#skills" class="nav-link text-gray-600 hover:text-blue-700 transition duration-300 rounded-md p-2 hover:bg-blue-50">Skills</a>
                <a href="#projects" class="nav-link text-gray-600 hover:text-blue-700 transition duration-300 rounded-md p-2 hover:bg-blue-50">Projects</a>
                <a href="#contact" class="nav-link text-gray-600 hover:text-blue-700 transition duration-300 rounded-md p-2 hover:bg-blue-50">Contact</a>
            </div>
        </nav>
    </header>

    <section id="hero" class="relative bg-gradient-to-r from-blue-600 to-blue-800 text-white py-32 flex items-center justify-center min-h-screen-75">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-5xl md:text-6xl font-bold mb-4 leading-tight">
                Hi, I'm <span class="text-yellow-300">Peter Ogbonna</span>
            </h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">
                A Junior Frontend Web Developer passionate about building user-friendly and efficient web experiences.
            </p>
            <a href="#projects" class="bg-white text-blue-700 hover:bg-blue-100 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105">
                View My Work
            </a>
        </div>
    </section>

    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">About Me</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="w-48 h-48 rounded-full overflow-hidden shadow-lg mb-8 md:mb-0 flex-shrink-0">
                    <img src="https://placehold.co/200x200/a0aec0/ffffff?text=Your+Photo" alt="Peter Ogbonna" class="w-full h-full object-cover">
                </div>
                <div class="text-lg text-gray-700 leading-relaxed">
                    <p class="mb-4">
                        Detail-oriented and tech-savvy, I'm Peter Ogbonna, currently undergoing exciting training in Software Engineering. My background as a Virtual Assistant has equipped me with valuable skills in problem-solving, logical thinking, and efficient workflow management, which I believe are directly applicable to software development.
                    </p>
                    <p>
                        I'm keen to leverage my aptitude for technology and my growing knowledge in programming (e.g., HTML, CSS, JavaScript, React) to build innovative and impactful software solutions. I'm a quick learner, passionate about creating efficient and user-friendly applications, and eager to contribute my skills to the world of software development.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-blue-700 mb-3">Frontend Core</h3>
                    <ul class="list-disc list-inside text-gray-700">
                        <li>HTML5</li>
                        <li>CSS3</li>
                        <li>JavaScript (ES6+)</li>
                        <li>Responsive Design</li>
                    </ul>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-blue-700 mb-3">Frameworks & Libraries</h3>
                    <ul class="list-disc list-inside text-gray-700">
                        <li>Tailwind CSS</li>
                        <li>React (Basic)</li>
                        <li>Bootstrap</li>
                    </ul>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-blue-700 mb-3">Tools & Version Control</h3>
                    <ul class="list-disc list-inside text-gray-700">
                        <li>Git & GitHub</li>
                        <li>VS Code</li>
                        <li>Figma (Basic UI/UX)</li>
                    </ul>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-blue-700 mb-3">Transferable Skills</h3>
                    <ul class="list-disc list-inside text-gray-700">
                        <li>Problem-Solving</li>
                        <li>Logical Thinking</li>
                        <li>Workflow Optimization</li>
                        <li>Attention to Detail</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-5xl">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x350/e0e7ff/3f51b5?text=Project+1+Image" alt="Project 1" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Project Title One</h3>
                        <p class="text-gray-600 mb-4">
                            A responsive web application built with HTML, CSS, and JavaScript, demonstrating dynamic content loading and user interaction.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-200 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-blue-200 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded-full">CSS</span>
                            <span class="bg-blue-200 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded-full">JavaScript</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium transition duration-300">Live Demo &rarr;</a>
                            <a href="#" class="text-gray-600 hover:text-gray-800 font-medium transition duration-300">GitHub &rarr;</a>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x350/d1d5db/4b5563?text=Project+2+Image" alt="Project 2" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Project Title Two</h3>
                        <p class="text-gray-600 mb-4">
                            A simple landing page showcasing responsive design principles and modern CSS frameworks like Tailwind CSS.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-green-200 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-green-200 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded-full">Tailwind CSS</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium transition duration-300">Live Demo &rarr;</a>
                            <a href="#" class="text-gray-600 hover:text-gray-800 font-medium transition duration-300">GitHub &rarr;</a>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x350/fecaca/dc2626?text=Project+3+Image" alt="Project 3" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Project Title Three</h3>
                        <p class="text-gray-600 mb-4">
                            A small interactive component or mini-game, demonstrating fundamental JavaScript logic and DOM manipulation.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-red-200 text-red-800 text-xs font-medium px-2.5 py-0.5 rounded-full">HTML</span>
                            <span class="bg-red-200 text-red-800 text-xs font-medium px-2.5 py-0.5 rounded-full">CSS</span>
                            <span class="bg-red-200 text-red-800 text-xs font-medium px-2.5 py-0.5 rounded-full">JavaScript</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium transition duration-300">Live Demo &rarr;</a>
                            <a href="#" class="text-gray-600 hover:text-gray-800 font-medium transition duration-300">GitHub &rarr;</a>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 rounded-lg shadow-lg overflow-hidden border border-gray-200">
                    <img src="https://placehold.co/600x350/bfdbfe/1d4ed8?text=Project+4+Image" alt="Project 4" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-2">Project Title Four</h3>
                        <p class="text-gray-600 mb-4">
                            (Description of your next project, perhaps using a new library or concept you learned.)
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-indigo-200 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded-full">React</span>
                            <span class="bg-indigo-200 text-indigo-800 text-xs font-medium px-2.5 py-0.5 rounded-full">API Integration</span>
                        </div>
                        <div class="flex space-x-4">
                            <a href="#" class="text-blue-600 hover:text-blue-800 font-medium transition duration-300">Live Demo &rarr;</a>
                            <a href="#" class="text-gray-600 hover:text-gray-800 font-medium transition duration-300">GitHub &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4 max-w-3xl">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Get in Touch</h2>
            <div class="bg-white p-8 rounded-lg shadow-lg">
                <p class="text-lg text-gray-700 text-center mb-6">
                    I'm currently seeking new opportunities and would love to connect! Feel free to reach out.
                </p>
                <div class="flex flex-col items-center space-y-4">
                    <a href="mailto:peterogb067@gmail.com" class="text-blue-600 hover:text-blue-800 text-lg font-medium">
                        peterogb067@gmail.com
                    </a>
                    <a href="https://www.linkedin.com/in/peter-ogbonna-3169b5283" target="_blank" class="text-blue-600 hover:text-blue-800 text-lg font-medium">
                        LinkedIn Profile
                    </a>
                    <a href="https://github.com/your-github-username" target="_blank" class="text-blue-600 hover:text-blue-800 text-lg font-medium">
                        GitHub Profile
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-8 text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 Peter Ogbonna. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // JavaScript for smooth scrolling (already handled by scroll-behavior: smooth; in CSS, but good for older browsers)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Optional: Highlight active navigation link based on scroll position
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('.nav-link');

        window.addEventListener('scroll', () => {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 80; // Adjust for fixed header height
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= sectionTop && pageYOffset < sectionTop + sectionHeight) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('active');
                if (link.href.includes(current)) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>
