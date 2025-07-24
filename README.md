<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Start From Scratch Cleaning, LLC - Professional Cleaning Services</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light blue-gray background */
            color: #334155; /* Dark slate gray for text */
        }
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%; /* Adjust width as needed */
            height: 3px;
            background-color: #0d9488; /* Teal underline */
            border-radius: 9999px; /* Rounded corners for the underline */
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md py-4 px-6 md:px-12 flex flex-col md:flex-row justify-between items-center rounded-b-lg">
        <a href="#" class="text-2xl font-bold text-teal-600 mb-4 md:mb-0">Start From Scratch Cleaning, LLC</a>
        <div class="flex flex-wrap justify-center gap-4 md:gap-8">
            <a href="#home" class="text-gray-700 hover:text-teal-600 font-medium transition duration-300">Home</a>
            <a href="#services" class="text-gray-700 hover:text-teal-600 font-medium transition duration-300">Services</a>
            <a href="#about" class="text-gray-700 hover:text-teal-600 font-medium transition duration-300">About Us</a>
            <a href="#testimonials" class="text-gray-700 hover:text-teal-600 font-medium transition duration-300">Testimonials</a>
            <a href="#contact" class="text-gray-700 hover:text-teal-600 font-medium transition duration-300">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative bg-gradient-to-r from-teal-500 to-cyan-600 text-white py-20 md:py-32 px-6 md:px-12 flex items-center justify-center rounded-lg m-4">
        <!-- Background overlay for better text readability -->
        <div class="absolute inset-0 bg-black opacity-30 rounded-lg"></div>
        <div class="relative z-10 text-center max-w-4xl">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">Sparkling Clean, Every Time.</h1>
            <p class="text-lg md:text-xl mb-8 opacity-90">
                Professional cleaning services tailored to your home or business needs. Experience the difference with Start From Scrach Cleaning, LLC.
            </p>
            <a href="#contact" class="inline-block bg-white text-teal-700 hover:bg-teal-100 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 transform hover:scale-105">
                Get a Free Quote Today!
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-24 px-6 md:px-12 bg-white m-4 rounded-lg shadow-md">
        <div class="max-w-6xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 section-heading mx-auto">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">🏠</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Residential Cleaning</h3>
                    <p class="text-gray-600">
                        From regular tidying to deep cleaning, we keep your home spotless and comfortable. Enjoy a fresh living space without the hassle.
                    </p>
                </div>
                <!-- Service Card 2 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">🏢</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Commercial Cleaning</h3>
                    <p class="text-gray-600">
                        Maintain a professional and hygienic environment for your business. We offer flexible schedules to minimize disruption.
                    </p>
                </div>
                <!-- Service Card 3 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">✨</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Deep Cleaning</h3>
                    <p class="text-gray-600">
                        Thorough and comprehensive cleaning for those times your space needs extra attention. Perfect for seasonal clean-ups.
                    </p>
                </div>
                <!-- Service Card 4 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">📦</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Move-in/Move-out Cleaning</h3>
                    <p class="text-gray-600">
                        Ensure a smooth transition with our meticulous move-in/move-out cleaning services, leaving the property pristine.
                    </p>
                </div>
                <!-- Service Card 5 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">🌿</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Eco-Friendly Cleaning</h3>
                    <p class="text-gray-600">
                        Environmentally conscious cleaning solutions that are safe for your family, pets, and the planet.
                    </p>
                </div>
                <!-- Service Card 6 -->
                <div class="bg-gray-50 p-8 rounded-xl shadow-sm hover:shadow-lg transition duration-300 transform hover:-translate-y-1">
                    <div class="text-5xl mb-4 text-teal-500">🧹</div> <!-- Emoji icon -->
                    <h3 class="text-xl font-semibold mb-3 text-gray-800">Custom Cleaning Plans</h3>
                    <p class="text-gray-600">
                        We work with you to create a personalized cleaning plan that fits your specific needs and schedule.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 md:py-24 px-6 md:px-12 bg-gray-100 m-4 rounded-lg shadow-md">
        <div class="max-w-6xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 section-heading mx-auto">About Cleaning, LLC</h2>
            <div class="text-lg text-gray-700 leading-relaxed max-w-3xl mx-auto">
                <p class="mb-6">
                    At Start From Scratch Cleaning, LLC, we are passionate about creating clean and healthy environments for our clients. Founded with a commitment to excellence and customer satisfaction, we strive to deliver unparalleled cleaning services that exceed expectations.
                </p>
                <p class="mb-6">
                    Our team of highly trained and trustworthy professionals uses industry-leading techniques and eco-friendly products to ensure every corner sparkles. We believe a clean space contributes to a better quality of life, and we are dedicated to making that a reality for you.
                </p>
                <p>
                    Choose Cleaning, LLC for reliable, efficient, and thorough cleaning services. Let us handle the dirt, so you can focus on what matters most.
                </p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-16 md:py-24 px-6 md:px-12 bg-white m-4 rounded-lg shadow-md">
        <div class="max-w-6xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 section-heading mx-auto">What Our Clients Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-teal-50 p-8 rounded-xl shadow-sm">
                    <p class="text-lg italic text-gray-700 mb-6">
                        "Cleaning, LLC transformed my home! It's never been so clean. The team was professional, efficient, and incredibly thorough. Highly recommend!"
                    </p>
                    <p class="font-semibold text-teal-700">- Jane Doe, Residential Client</p>
                </div>
                <!-- Testimonial 2 -->
                <div class="bg-teal-50 p-8 rounded-xl shadow-sm">
                    <p class="text-lg italic text-gray-700 mb-6">
                        "Our office space looks fantastic after Cleaning, LLC started their service. They are reliable and always do an amazing job. A true partner for our business."
                    </p>
                    <p class="font-semibold text-teal-700">- John Smith, Business Owner</p>
                </div>
                <!-- Testimonial 3 -->
                <div class="bg-teal-50 p-8 rounded-xl shadow-sm">
                    <p class="text-lg italic text-gray-700 mb-6">
                        "I used Cleaning, LLC for a deep clean before moving in, and they exceeded all my expectations. The house was spotless! Excellent service."
                    </p>
                    <p class="font-semibold text-teal-700">- Emily White, New Homeowner</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 px-6 md:px-12 bg-gray-100 m-4 rounded-lg shadow-md">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-12 section-heading mx-auto">Contact Us</h2>
            <p class="text-lg text-gray-700 mb-8">
                Ready for a cleaner space? Get in touch with us today for a free quote or to learn more about our services.
            </p>
            <div class="flex flex-col md:flex-row justify-center items-center gap-8 mb-12">
                <div class="flex items-center text-gray-700">
                    <span class="text-2xl mr-3 text-teal-600">📞</span>
                    <a href="tel:+19542579349" class="hover:text-teal-600 transition duration-300">(954) 257-9349</a>
                </div>
                <div class="flex items-center text-gray-700">
                    <span class="text-2xl mr-3 text-teal-600">📧</span>
                    <a href="mailto:sfsc@sfscproperties.com" class="hover:text-teal-600 transition duration-300">sfsc@sfscproperties.com</a>
                </div>
            </div>

            <!-- Contact Form -->
            <form class="bg-white p-8 rounded-xl shadow-lg max-w-xl mx-auto">
                <div class="mb-6 text-left">
                    <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Name</label>
                    <input type="text" id="name" name="name" class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-teal-500 focus:border-transparent" placeholder="Your Name">
                </div>
                <div class="mb-6 text-left">
                    <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email</label>
                    <input type="email" id="email" name="email" class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-teal-500 focus:border-transparent" placeholder="your@email.com">
                </div>
                <div class="mb-6 text-left">
                    <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Message</label>
                    <textarea id="message" name="message" rows="5" class="shadow appearance-none border rounded-lg w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-teal-500 focus:border-transparent" placeholder="Tell us about your cleaning needs..."></textarea>
                </div>
                <button type="submit" class="bg-teal-600 hover:bg-teal-700 text-white font-bold py-3 px-8 rounded-full shadow-md transition duration-300 transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-teal-500 focus:ring-offset-2">
                    Send Message
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 px-6 md:px-12 text-center rounded-t-lg m-4">
        <p class="mb-4">&copy; 2025 Start From Scratch Cleaning, LLC. All rights reserved.</p>
        <div class="flex justify-center space-x-6">
            <a href="https://www.ussbchamber.org/start-from-scratch/" class="text-gray-400 hover:text-white transition duration-300" target="_blank" rel="noopener noreferrer">US Small Business Chamber</a>
        </div>
    </footer>

</body>
</html>
