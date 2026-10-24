
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Mehta's Store - Navbar</title>

    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-slate-100 min-h-screen">

    <!-- Header -->
    <header class="bg-gradient-to-r from-slate-900 via-blue-900 to-teal-800 text-white px-4 sm:px-8 py-4 shadow-xl">

        <div class="max-w-screen-2xl mx-auto flex flex-wrap justify-between items-center gap-4">

            <!-- Logo -->
            <h1 class="text-2xl sm:text-3xl font-extrabold tracking-wide">
                Mehta's
                <span class="text-teal-300">Store.</span>
            </h1>

            <!-- Navigation -->
            <nav class="flex flex-wrap items-center gap-1 sm:gap-3 text-sm sm:text-base">

                <a href="#"
                   class="px-3 py-2 rounded-full hover:bg-white/15 hover:text-teal-300 transition duration-300">
                    Home
                </a>

                <a href="#"
                   class="px-3 py-2 rounded-full hover:bg-white/15 hover:text-teal-300 transition duration-300">
                    About
                </a>

                <!-- Products Dropdown -->
                <div class="relative group">

                    <button type="button"
                            class="px-3 py-2 rounded-full hover:bg-white/15 hover:text-teal-300 transition duration-300">

                        Products

                        <span class="inline-block transition-transform duration-300 group-hover:rotate-180">
                            ▼
                        </span>

                    </button>

                    <!-- Dropdown Menu -->
                    <div class="invisible opacity-0 translate-y-2
                                group-hover:visible group-hover:opacity-100
                                group-hover:translate-y-0
                                group-focus-within:visible
                                group-focus-within:opacity-100
                                group-focus-within:translate-y-0
                                transition-all duration-300
                                absolute right-0 top-full pt-3 w-44 z-50">

                        <div class="bg-white text-slate-800 rounded-xl shadow-xl p-2 border border-slate-200">

                            <a href="#"
                               class="block px-3 py-3 rounded-lg hover:bg-teal-50 hover:text-teal-800 transition duration-200">
                                💻 Laptop
                            </a>

                            <a href="#"
                               class="block px-3 py-3 rounded-lg hover:bg-teal-50 hover:text-teal-800 transition duration-200">
                                📱 Mobile
                            </a>

                            <a href="#"
                               class="block px-3 py-3 rounded-lg hover:bg-teal-50 hover:text-teal-800 transition duration-200">
                                👟 Shoes
                            </a>

                            <a href="#"
                               class="block px-3 py-3 rounded-lg hover:bg-teal-50 hover:text-teal-800 transition duration-200">
                                ⌚ Watches
                            </a>

                        </div>

                    </div>

                </div>

                <a href="#"
                   class="px-3 py-2 rounded-full hover:bg-white/15 hover:text-teal-300 transition duration-300">
                    Contact
                </a>

                <!-- Login Button -->
                <a href="#"
                   class="ml-1 bg-teal-300 text-slate-900 font-bold px-5 py-2 rounded-full shadow-md hover:bg-teal-200 hover:scale-105 transition duration-300">
                    Login
                </a>

            </nav>

        </div>

    </header>

    <!-- Main Content Area -->
    <main class="min-h-[calc(100vh-80px)] bg-slate-100">

        <!-- Empty content area, matching the lab reference -->

    </main>

</body>
</html>
