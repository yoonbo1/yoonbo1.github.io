<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoonbo Cho - AI Application Developer</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <style>
        /* Custom Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        header {
            background: linear-gradient(90deg, #1a73e8 0%, #4285f4 100%);
        }
        header h1 {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        section {
            margin-bottom: 4rem;
        }
        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%;
            height: 2px;
            background-color: #1a73e8;
        }
        .project-card {
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
        .contact a {
            color: #1a73e8;
            text-decoration: none;
            border-bottom: 2px solid transparent;
            transition: border-color 0.3s;
        }
        .contact a:hover {
            border-color: #1a73e8;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-900">
    <!-- Header Section -->
    <header class="text-white p-6">
        <div class="container mx-auto">
            <h1 class="text-4xl font-bold">Yoonbo Cho</h1>
            <p class="text-lg">AI Application Developer</p>
        </div>
    </header>

    <!-- About Me Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto">
            <h2 class="section-title text-3xl font-bold">About Me</h2>
            <p class="text-lg leading-relaxed">I am an AI Application Developer with a passion for creating innovative solutions that leverage artificial intelligence to solve real-world problems. My expertise includes machine learning, deep learning, and natural language processing. I enjoy working on projects that challenge me to grow and improve my skills.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-12 bg-gray-100">
        <div class="container mx-auto">
            <h2 class="section-title text-3xl font-bold">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="project-card bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">Project 1</h3>
                    <p class="text-gray-700">Description of project 1...</p>
                </div>
                <!-- Project 2 -->
                <div class="project-card bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">Project 2</h3>
                    <p class="text-gray-700">Description of project 2...</p>
                </div>
                <!-- Project 3 -->
                <div class="project-card bg-white p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">Project 3</h3>
                    <p class="text-gray-700">Description of project 3...</p>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto contact">
            <h2 class="section-title text-3xl font-bold">Contact</h2>
            <p class="text-lg leading-relaxed">Feel free to reach out to me at <a href="mailto:example@example.com">example@example.com</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white p-6">
        <div class="container mx-auto">
            <p>&copy; 2024 Yoonbo Cho. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
