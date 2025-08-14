<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanmay Bindal</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts for 'Inter' -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom scrollbar styling */
        ::-webkit-scrollbar {
            width: 12px;
        }
        ::-webkit-scrollbar-track {
            background: #111827; /* Dark background */
        }
        ::-webkit-scrollbar-thumb {
            background-color: #4b5563; /* Gray thumb */
            border-radius: 6px;
            border: 3px solid #111827;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100">

    <!-- Header / Hero Section -->
    <header id="home" class="min-h-screen flex flex-col justify-center items-center text-center p-8 bg-gradient-to-br from-indigo-900 to-purple-900">
        <div class="max-w-2xl">
            <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight text-white mb-4">
                Tanmay Bindal
            </h1>
            <p class="text-2xl md:text-3xl font-semibold text-purple-200 mb-6">
                Full Stack Developer | AI Enthusiast
            </p>
            <p class="text-lg md:text-xl text-gray-200 mb-8">
                Crafting elegant and scalable web applications with a focus on modern technologies and clean code.
            </p>
            <a href="#projects" class="inline-block bg-white text-indigo-900 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-200 transition duration-300 transform hover:scale-105">
                View My Work
            </a>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="container mx-auto p-8 lg:p-16">

        <!-- About Me Section -->
        <section id="about" class="mb-24">
            <h2 class="text-4xl font-bold mb-8 text-center text-white">About Me</h2>
            <div class="bg-gray-800 p-8 rounded-xl shadow-lg border border-gray-700 max-w-4xl mx-auto">
                <p class="text-gray-300 leading-relaxed text-lg text-center">
                    Hello! I'm Tanmay, a passionate developer with expertise in building robust and responsive web solutions. My journey in tech has led me to work with a variety of technologies, from front-end frameworks like React to back-end systems with Node.js and databases like MongoDB. I'm always eager to learn new things and am particularly fascinated by the potential of artificial intelligence to solve complex problems.
                </p>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="mb-24">
            <h2 class="text-4xl font-bold mb-12 text-center text-white">My Skills</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8 text-center max-w-6xl mx-auto">
                <!-- Individual Skill Card -->
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-react text-5xl text-blue-400 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">React</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-node-js text-5xl text-green-500 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">Node.js</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-js text-5xl text-yellow-400 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">JavaScript</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-html5 text-5xl text-orange-500 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">HTML5</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-css3-alt text-5xl text-blue-600 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">CSS3</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fas fa-database text-5xl text-gray-400 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">MongoDB</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-git-alt text-5xl text-red-600 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">Git</p>
                </div>
                <div class="flex flex-col items-center p-4 bg-gray-800 rounded-lg shadow-md border border-gray-700 transform hover:scale-105 transition duration-300">
                    <i class="fab fa-python text-5xl text-blue-500 mb-2"></i>
                    <p class="text-lg font-semibold text-gray-200">Python</p>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="mb-24">
            <h2 class="text-4xl font-bold mb-12 text-center text-white">My Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12 max-w-6xl mx-auto">

                <!-- Project Card 1 -->
                <div class="bg-gray-800 rounded-xl shadow-lg overflow-hidden border border-gray-700 transform hover:scale-105 transition duration-300">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-100 mb-2">Project Title One</h3>
                        <p class="text-gray-400 text-sm mb-4">A brief description of the project. Explain what it does and the technologies used. You can be more detailed here.</p>
                        <div class="flex gap-4">
                            <a href="#" class="inline-block bg-purple-600 text-white font-semibold py-2 px-4 rounded-lg hover:bg-purple-700 transition duration-300">
                                <i class="fab fa-github mr-2"></i> GitHub
                            </a>
                            <a href="#" class="inline-block border border-purple-600 text-purple-300 font-semibold py-2 px-4 rounded-lg hover:bg-purple-600 hover:text-white transition duration-300">
                                Live Demo
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Project Card 2 -->
                <div class="bg-gray-800 rounded-xl shadow-lg overflow-hidden border border-gray-700 transform hover:scale-105 transition duration-300">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-100 mb-2">Project Title Two</h3>
                        <p class="text-gray-400 text-sm mb-4">A brief description of the project. Explain what it does and the technologies used. You can be more detailed here.</p>
                        <div class="flex gap-4">
                            <a href="#" class="inline-block bg-purple-600 text-white font-semibold py-2 px-4 rounded-lg hover:bg-purple-700 transition duration-300">
                                <i class="fab fa-github mr-2"></i> GitHub
                            </a>
                            <a href="#" class="inline-block border border-purple-600 text-purple-300 font-semibold py-2 px-4 rounded-lg hover:bg-purple-600 hover:text-white transition duration-300">
                                Live Demo
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Project Card 3 -->
                <div class="bg-gray-800 rounded-xl shadow-lg overflow-hidden border border-gray-700 transform hover:scale-105 transition duration-300">
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-100 mb-2">Project Title Three</h3>
                        <p class="text-gray-400 text-sm mb-4">A brief description of the project. Explain what it does and the technologies used. You can be more detailed here.</p>
                        <div class="flex gap-4">
                            <a href="#" class="inline-block bg-purple-600 text-white font-semibold py-2 px-4 rounded-lg hover:bg-purple-700 transition duration-300">
                                <i class="fab fa-github mr-2"></i> GitHub
                            </a>
                            <a href="#" class="inline-block border border-purple-600 text-purple-300 font-semibold py-2 px-4 rounded-lg hover:bg-purple-600 hover:text-white transition duration-300">
                                Live Demo
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="mb-24">
            <h2 class="text-4xl font-bold mb-8 text-center text-white">Get In Touch</h2>
            <div class="bg-gray-800 p-8 rounded-xl shadow-lg border border-gray-700 max-w-2xl mx-auto text-center">
                <p class="text-gray-300 text-lg mb-6">
                    I'm currently open to new opportunities. Feel free to connect with me!
                </p>
                <div class="flex justify-center gap-6 text-3xl">
                    <a href="https://github.com/your-username" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-github-square"></i>
                    </a>
                    <a href="https://linkedin.com/in/your-profile" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="https://twitter.com/your-handle" target="_blank" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fab fa-twitter-square"></i>
                    </a>
                    <a href="mailto:your.email@example.com" class="text-gray-400 hover:text-white transition duration-300">
                        <i class="fas fa-envelope-square"></i>
                    </a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-950 text-center p-6 text-gray-500">
        <p>&copy; <span id="year"></span> Tanmay Bindal. All rights reserved.</p>
    </footer>

    <script>
        // Dynamically set the current year for the footer
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>

</body>
</html>
