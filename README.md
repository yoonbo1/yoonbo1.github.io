<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-100 text-gray-900">
    <!-- Header -->
    <header class="bg-white shadow">
        <div class="container mx-auto px-6 py-3">
            <div class="flex items-center justify-between">
                <div class="text-xl font-semibold text-gray-700">My Portfolio</div>
                <nav class="flex space-x-4">
                    <a href="#introduction" class="text-gray-600 hover:text-gray-800">Introduction</a>
                    <a href="#projects" class="text-gray-600 hover:text-gray-800">Projects</a>
                    <a href="#skills" class="text-gray-600 hover:text-gray-800">Skills</a>
                    <a href="#contact" class="text-gray-600 hover:text-gray-800">Contact</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-8">
        <!-- Introduction Section -->
        <section id="introduction" class="py-8">
            <h2 class="text-3xl font-semibold mb-4">Introduction</h2>
            <p class="text-gray-700">Hi, I'm Yoonbo Cho, a passionate software developer with experience in building web applications, developing software solutions, and working with various programming languages and technologies.</p>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-8">
            <h2 class="text-3xl font-semibold mb-4">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2">Project 1</h3>
                    <p class="text-gray-700">Description of Project 1...</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold mb-2">Project 2</h3>
                    <p class="text-gray-700">Description of Project 2...</p>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-8">
            <h2 class="text-3xl font-semibold mb-4">Skills</h2>
            <ul class="list-disc list-inside">
                <li class="text-gray-700">Skill 1</li>
                <li class="text-gray-700">Skill 2</li>
                <li class="text-gray-700">Skill 3</li>
                <!-- Add more skills as needed -->
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-8">
            <h2 class="text-3xl font-semibold mb-4">Contact</h2>
            <form class="bg-white p-6 rounded-lg shadow-lg">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700">Name</label>
                    <input type="text" id="name" class="w-full mt-1 p-2 border border-gray-300 rounded-lg">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700">Email</label>
                    <input type="email" id="email" class="w-full mt-1 p-2 border border-gray-300 rounded-lg">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700">Message</label>
                    <textarea id="message" class="w-full mt-1 p-2 border border-gray-300 rounded-lg"></textarea>
                </div>
                <button type="submit" class="bg-blue-500 text-white px-4 py-2 rounded-lg">Send</button>
            </form>
        </section>
    </main>
</body>

</html>
