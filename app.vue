<template>
  <div class="bg-gray-100 text-gray-900">
    <header class="bg-white py-4 shadow">
        <div class="container mx-auto flex justify-between items-center px-6">
            <div class="text-lg font-bold">Phongkhamquanhday</div>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#" class="hover:text-blue-500">Home</a></li>
                    <li><a href="#" class="hover:text-blue-500">About Us</a></li>
                    <li><a href="#" class="hover:text-blue-500">Services</a></li>
                    <li><a href="#" class="hover:text-blue-500">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container mx-auto mt-10 px-6">
        <div class="bg-white p-6 rounded-lg shadow-lg">
            <h1 class="text-xl font-bold mb-2">Find Nearby Medical Centers</h1>
            <p class="mb-4">Quickly find open medical centers near you!</p>
            <input type="text" placeholder="Enter your location" class="border p-2 w-full mb-4">
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                Search
            </button>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-6">
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h2 class="font-bold mb-2">Real-Time Updates</h2>
                <p>Up-to-the-minute open status of medical centers.</p>
            </div>
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h2 class="font-bold mb-2">User Reviews</h2>
                <p>Read what others have said about local medical facilities.</p>
            </div>
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h2 class="font-bold mb-2">24/7 Service</h2>
                <p>Access medical information any time, day or night.</p>
            </div>
        </div>
    </div>

    <footer class="bg-white mt-10 py-4 shadow">
        <div class="container mx-auto px-6 text-center">
            © 2024 Phongkhamquanhday. All rights reserved.
        </div>
    </footer>
  </div>
</template>
