<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoonbo Cho's Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-100 text-gray-900">

    <!-- Header -->
    <header class="bg-blue-900 text-white shadow-lg">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold">Yoonbo Cho</div>
            <nav class="flex space-x-4">
                <a href="#introduction" class="hover:text-yellow-400">Introduction</a>
                <a href="#projects" class="hover:text-yellow-400">Projects</a>
                <a href="#skills" class="hover:text-yellow-400">Skills</a>
                <a href="#contact" class="hover:text-yellow-400">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">

        <!-- Introduction Section -->
        <section id="introduction" class="py-12">
            <h2 class="text-4xl font-bold mb-4 text-blue-900">Introduction</h2>
            <p class="text-lg text-gray-700">Hi, I'm Yoonbo Cho, a passionate software developer with experience in building web applications, developing software solutions, and working with various programming languages and technologies.</p>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-12 bg-white shadow-lg rounded-lg">
            <h2 class="text-4xl font-bold mb-4 text-blue-900">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-100 p-6 rounded-lg shadow">
                    <h3 class="text-2xl font-semibold mb-2 text-blue-800">Project 1</h3>
                    <p class="text-gray-700">Description of Project 1...</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow">
                    <h3 class="text-2xl font-semibold mb-2 text-blue-800">Project 2</h3>
                    <p class="text-gray-700">Description of Project 2...</p>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-12">
            <h2 class="text-4xl font-bold mb-4 text-blue-900">Skills</h2>
            <ul class="list-disc list-inside text-lg text-gray-700">
                <li>Skill 1</li>
                <li>Skill 2</li>
                <li>Skill 3</li>
                <!-- Add more skills as needed -->
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-12 bg-white shadow-lg rounded-lg">
            <h2 class="text-4xl font-bold mb-4 text-blue-900">Contact</h2>
            <form class="bg-gray-100 p-6 rounded-lg shadow-md">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700 text-lg font-semibold">Name</label>
                    <input type="text" id="name" class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700 text-lg font-semibold">Email</label>
                    <input type="email" id="email" class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700 text-lg font-semibold">Message</label>
                    <textarea id="message" class="w-full mt-2 p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
                </div>
                <button type="submit" class="bg-blue-900 text-white px-4 py-2 rounded-lg hover:bg-blue-700">Send</button>
            </form>
        </section>

    </main>

</body>

</html>
