<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultimate Tic-Tac-Toe Landing</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles to ensure the background covers the whole page and for smooth transitions */
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #f0f4f8 0%, #d9e2ec 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .hero-card {
            backdrop-filter: blur(10px);
            background-color: rgba(255, 255, 255, 0.85); /* Slightly transparent white */
        }
        .play-button {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08);
        }
        .play-button:hover {
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.15), 0 4px 6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <!-- Main Landing Page Container -->
    <div class="w-full max-w-2xl hero-card rounded-3xl p-8 md:p-12 text-center border border-gray-200">

        <!-- Header and Icon -->
        <div class="mb-8">
            <span class="text-6xl mb-4 inline-block transform rotate-[-5deg] transition-transform duration-500 hover:rotate-[5deg]">
                ❌⭕️
            </span>
            <h1 class="text-5xl md:text-6xl font-extrabold text-gray-900 leading-tight">
                The Ultimate Tic-Tac-Toe Challenge
            </h1>
        </div>

        <!-- Description -->
        <p class="text-xl text-gray-700 mb-10 max-w-lg mx-auto">
            Ready to test your strategic skills? Click the button below to be taken to the full game experience and play against friends or AI.
        </p>

        <!-- Play Button linking to the external game -->
        <a href="https://super-muffin-2550fa.netlify.app/" target="_blank"
            class="play-button inline-flex items-center justify-center
                   px-12 py-4 bg-blue-600 text-white font-bold text-xl rounded-full
                   hover:bg-blue-700 active:bg-blue-800
                   transform hover:scale-105 active:scale-95
                   focus:outline-none focus:ring-4 focus:ring-blue-300">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-3" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z" clip-rule="evenodd" />
            </svg>
            Play the Game
        </a>

        <!-- Footer Note -->
        <p class="mt-10 text-sm text-gray-500">
            You will be redirected to an external site to start the challenge.
        </p>

    </div>

</body>
</html>
