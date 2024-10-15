# lux<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

<body class="bg-gray-100 text-gray-800">

<header class="flex justify-between items-center p-5 bg-white shadow-md">
    <div class="text-lg font-bold">Sell Websites</div>
    <nav class="space-x-4">
        <a href="#" class="hover:text-blue-500">Home</a>
        <a href="#services" class="hover:text-blue-500">Services</a>
        <a href="#contact" class="hover:text-blue-500">Contact</a>
    </nav>
</header>

<section class="flex flex-col items-center justify-center min-h-screen bg-gradient-to-r from-blue-500 to-teal-500 text-white">
    <h1 class="text-5xl font-bold mb-4">Welcome to Sell Your Website</h1>
    <p class="text-lg mb-8">Your one-stop solution for buying and selling websites.</p>
    <a href="#services" class="bg-white text-blue-500 rounded-full px-6 py-3 hover:bg-gray-200 transition duration-300">Explore Services</a>
</section>

<section id="services" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4">
        <h2 class="text-3xl font-semibold text-center mb-12">Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-gray-100 p-5 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-2">Website Development</h3>
                <p>Custom websites built to suit your business needs.</p>
            </div>
            <div class="bg-gray-100 p-5 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-2">SEO Optimization</h3>
                <p>Improve your website's visibility on search engines.</p>
            </div>
            <div class="bg-gray-100 p-5 rounded-lg shadow-md">
                <h3 class="text-xl font-bold mb-2">Consulting Services</h3>
                <p>Get expert advice on your website strategies.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="py-20 bg-gray-100">
    <div class="max-w-lg mx-auto px-4">
        <h2 class="text-3xl font-semibold text-center mb-6">Get in Touch</h2>
        <form class="bg-white p-6 rounded-lg shadow-md">
            <div class="mb-4">
                <label for="name" class="block text-sm font-medium mb-1">Name</label>
                <input type="text" id="name" class="block w-full border border-gray-300 rounded-lg px-4 py-2" required>
            </div>
            <div class="mb-4">
                <label for="email" class="block text-sm font-medium mb-1">Email</label>
                <input type="email" id="email" class="block w-full border border-gray-300 rounded-lg px-4 py-2" required>
            </div>
            <div class="mb-4">
                <label for="message" class="block text-sm font-medium mb-1">Message</label>
                <textarea id="message" class="block w-full border border-gray-300 rounded-lg px-4 py-2" rows="4" required></textarea>
            </div>
            <button type="submit" class="bg-blue-500 text-white rounded-full px-6 py-3 hover:bg-blue-600 transition duration-300">Send Message</button>
        </form>
    </div>
</section>

<footer class="bg-white py-4 text-center">
    <p>&copy; 2023 Sell Your Website. All rights reserved.</p>
</footer>

</body>
