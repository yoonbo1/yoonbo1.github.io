<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoonbo Cho - AI Application Developer</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .header-gradient {
            background: linear-gradient(90deg, #1a73e8 0%, #4285f4 100%);
        }
        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            font-size: 2.5rem;
            font-weight: bold;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%;
            height: 3px;
            background-color: #1a73e8;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
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
<body class="bg-gray-50 text-gray-800">
    <!-- Header Section -->
    <header class="header-gradient text-white p-16 text-center">
        <div class="container mx-auto">
            <h1 class="text-6xl font-bold">Yoonbo Cho</h1>
            <p class="text-2xl mt-4">AI Application Developer</p>
        </div>
    </header>

    <!-- About Me Section -->
    <section class="py-20 bg-white text-center">
        <div class="container mx-auto">
            <h2 class="section-title text-4xl">About Me</h2>
            <p class="text-xl leading-relaxed mt-8 mx-auto max-w-2xl">I am an AI Application Developer with a passion for creating innovative solutions that leverage artificial intelligence to solve real-world problems. My expertise includes machine learning, deep learning, and natural language processing. I enjoy working on projects that challenge me to grow and improve my skills.</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-20 bg-gray-100 text-center">
        <div class="container mx-auto">
            <h2 class="section-title text-4xl">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12 mt-12">
                <!-- Project 1 -->
                <div class="project-card bg-white p-8 rounded-lg shadow-lg transition-transform duration-300">
                    <h3 class="text-2xl font-bold mb-4">Project 1</h3>
                    <p class="text-gray-700">Description of project 1...</p>
                </div>
                <!-- Project 2 -->
                <div class="project-card bg-white p-8 rounded-lg shadow-lg transition-transform duration-300">
                    <h3 class="text-2xl font-bold mb-4">Project 2</h3>
                    <p class="text-gray-700">Description of project 2...</p>
                </div>
                <!-- Project 3 -->
                <div class="project-card bg-white p-8 rounded-lg shadow-lg transition-transform duration-300">
                    <h3 class="text-2xl font-bold mb-4">Project 3</h3>
                    <p class="text-gray-700">Description of project 3...</p>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-20 bg-white text-center">
        <div class="container mx-auto contact">
            <h2 class="section-title text-4xl">Contact</h2>
            <p class="text-xl leading-relaxed mt-8">Feel free to reach out to me at <a href="mailto:example@example.com">example@example.com</a></p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white p-8 text-center">
        <div class="container mx-auto">
            <p>&copy; 2024 Yoonbo Cho. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
