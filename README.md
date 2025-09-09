<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>◆MOTIVLAB◆ Authentic Local Cuisine</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            color: #1a202c;
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Hero Section -->
    <header class="relative h-96 md:h-[500px] flex items-center justify-center text-center text-white p-4" style="background-image: url('https://placehold.co/1200x800/2f3640/FFFFFF?text=Delicious+Food'); background-size: cover; background-position: center;">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        <div class="relative z-10 max-w-2xl mx-auto">
            <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold leading-tight">Evening Sun</h1>
            <h2 class="mt-2 text-2xl sm:text-3xl font-semibold">Authentic Nigerian Flavors, Served Fresh.</h2>
            <p class="mt-4 text-lg md:text-xl">Enjoy a warm atmosphere, delicious food, and great company.</p>
            <a href="https://wa.me/234XXXXXXXXXX" class="mt-6 inline-block px-8 py-4 bg-green-500 text-white font-bold rounded-full shadow-lg hover:bg-green-600 transition-colors duration-200">
                Book a Table on WhatsApp
            </a>
        </div>
    </header>

    <!-- Services Section -->
    <section id="services" class="my-16 container mx-auto px-4">
        <h2 class="text-3xl font-semibold text-center text-gray-800 mb-8">Service Options</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
            <div class="bg-white p-6 rounded-xl shadow-md border border-gray-200">
                <div class="text-4xl text-gray-700 mb-4">🍽️</div>
                <h3 class="text-xl font-semibold text-gray-900 mb-2">Dine-in</h3>
                <p class="text-gray-600">Enjoy our full menu and a comfortable dining experience with table service.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-md border border-gray-200">
                <div class="text-4xl text-gray-700 mb-4">🚗</div>
                <h3 class="text-xl font-semibold text-gray-900 mb-2">Takeaway</h3>
                <p class="text-gray-600">Order your favorite dishes and pick them up to enjoy at home or on the go.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-md border border-gray-200">
                <div class="text-4xl text-gray-700 mb-4">☎️</div>
                <h3 class="text-xl font-semibold text-gray-900 mb-2">Table Service</h3>
                <p class="text-gray-600">Our friendly staff is ready to assist you and make your dining experience special.</p>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="my-16 bg-white py-12 px-4 rounded-xl shadow-md container mx-auto">
        <h2 class="text-3xl font-semibold text-center text-gray-800 mb-8">Our Signature Dishes</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Dish 1 -->
            <div class="flex flex-col items-center">
                <img src="https://placehold.co/400x300/F2F2F2/333333?text=Dish+1" alt="Dish 1" class="rounded-lg shadow-sm w-full mb-4">
                <h3 class="text-xl font-semibold text-gray-900">Jollof Rice with Chicken</h3>
                <p class="text-gray-600 text-center">Smoky, rich jollof rice served with grilled chicken.</p>
            </div>
            <!-- Dish 2 -->
            <div class="flex flex-col items-center">
                <img src="https://placehold.co/400x300/F2F2F2/333333?text=Dish+2" alt="Dish 2" class="rounded-lg shadow-sm w-full mb-4">
                <h3 class="text-xl font-semibold text-gray-900">Efo Riro and Pounded Yam</h3>
                <p class="text-gray-600 text-center">Classic Nigerian spinach stew with tender pounded yam.</p>
            </div>
            <!-- Dish 3 -->
            <div class="flex flex-col items-center">
                <img src="https://placehold.co/400x300/F2F2F2/333333?text=Dish+3" alt="Dish 3" class="rounded-lg shadow-sm w-full mb-4">
                <h3 class="text-xl font-semibold text-gray-900">Suya Skewers</h3>
                <p class="text-gray-600 text-center">Spicy grilled beef skewers, a perfect appetizer.</p>
            </div>
        </div>
        <div class="text-center mt-8">
            <a href="#" class="inline-block px-8 py-4 bg-gray-200 text-gray-700 font-semibold rounded-full hover:bg-gray-300 transition-colors duration-200">
                View Full Menu (PDF)
            </a>
        </div>
    </section>

    <!-- Contact & Location Section -->
    <section id="contact" class="my-16 container mx-auto px-4">
        <h2 class="text-3xl font-semibold text-center text-gray-800 mb-8">Visit Us</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 bg-white p-8 rounded-xl shadow-md">
            <!-- Contact Info -->
            <div class="flex flex-col space-y-4">
                <div>
                    <h3 class="text-xl font-semibold text-gray-900">Opening Hours</h3>
                    <p class="text-gray-600">Monday - Friday: 12 PM - 10 PM</p>
                    <p class="text-gray-600">Saturday: 2 PM - 11 PM</p>
                    <p class="text-gray-600">Sunday: Closed</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold text-gray-900">Location</h3>
                    <p class="text-gray-600">123 Local Street, Lagos, Nigeria</p>
                    <a href="#" class="text-green-500 font-medium hover:underline">Get Directions</a>
                </div>
                <div>
                    <h3 class="text-xl font-semibold text-gray-900">Contact</h3>
                    <p class="text-gray-600">Phone: +234 123 456 7890</p>
                    <p class="text-gray-600">Email: info@eveningsun.com</p>
                </div>
            </div>
            <!-- Map Placeholder -->
            <div>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3964.128704258169!2d3.3762413147701784!3d6.529759795267154!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x103b8b9b4f9a0c2f%3A0x6b8c9d4b4e3a8b4b!2sLagos%2C%20Nigeria!5e0!3m2!1sen!2sus!4v1628173570081!5m2!1sen!2sus" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 text-center text-gray-500 bg-white shadow-inner">
        <p>&copy; 2025 Evening Sun. All rights reserved.</p>
    </footer>

</body>
</html>
