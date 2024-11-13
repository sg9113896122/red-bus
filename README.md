<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   RedBus Clone
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
  </style>
 </head>
 <body class="bg-gray-100">
  <header class="bg-red-600 text-white p-4">
   <div class="container mx-auto flex justify-between items-center">
    <div class="text-2xl font-bold">
     RedBus Clone
    </div>
    <nav>
     <ul class="flex space-x-4">
      <li>
       <a class="hover:underline" href="#">
        Home
       </a>
      </li>
      <li>
       <a class="hover:underline" href="#">
        Bus Tickets
       </a>
      </li>
      <li>
       <a class="hover:underline" href="#">
        Hotels
       </a>
      </li>
      <li>
       <a class="hover:underline" href="#">
        Offers
       </a>
      </li>
      <li>
       <a class="hover:underline" href="#">
        Help
       </a>
      </li>
     </ul>
    </nav>
   </div>
  </header>
  <main class="container mx-auto mt-8">
   <section class="bg-white p-6 rounded-lg shadow-md">
    <h2 class="text-2xl font-bold mb-4">
     Book Bus Tickets
    </h2>
    <form class="space-y-4">
     <div class="flex space-x-4">
      <div class="flex-1">
       <label class="block text-sm font-medium text-gray-700" for="from">
        From
       </label>
       <input class="mt-1 block w-full p-2 border border-gray-300 rounded-md" id="from" placeholder="Enter departure city" type="text"/>
      </div>
      <div class="flex-1">
       <label class="block text-sm font-medium text-gray-700" for="to">
        To
       </label>
       <input class="mt-1 block w-full p-2 border border-gray-300 rounded-md" id="to" placeholder="Enter destination city" type="text"/>
      </div>
     </div>
     <div class="flex space-x-4">
      <div class="flex-1">
       <label class="block text-sm font-medium text-gray-700" for="departure-date">
        Departure Date
       </label>
       <input class="mt-1 block w-full p-2 border border-gray-300 rounded-md" id="departure-date" type="date"/>
      </div>
      <div class="flex-1">
       <label class="block text-sm font-medium text-gray-700" for="return-date">
        Return Date
       </label>
       <input class="mt-1 block w-full p-2 border border-gray-300 rounded-md" id="return-date" type="date"/>
      </div>
     </div>
     <button class="w-full bg-red-600 text-white p-2 rounded-md" type="submit">
      Search Buses
     </button>
    </form>
   </section>
   <section class="mt-8">
    <h2 class="text-2xl font-bold mb-4">
     Popular Routes
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City Bangalore to City Bijapur" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/saxBfJI1E2VwaCOrfEHDTr451pBE7MxsiLfp3CK2idfMEYCPB.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City Bangalore to City Bijapur
      </h3>
      <p class="text-gray-600">                                                                                                                Bangalore                         Bijapur
       Starting from  Rs.750
      </p>
     </div>
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City C to City D" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/VDvognwtqJ76OBBKeOsQGVpB0LhM5u87Ff98wfNgGGUKCMhnA.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City  Bangalore  to City Hubballi
      </h3>
      <p class="text-gray-600">
       Starting from Rs.550
      </p>
     </div>
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City E to City F" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/fbqS64enfndjbJycwMwfRfI7rf7ZWXWOGS8JwVnDlV7hQgJ8E.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City Bangalore to City Chitradurga
      </h3>
      <p class="text-gray-600">
       Starting from Rs.600
      </p>
     </div>
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City G to City H" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/GuqpLddbct6gChYgpI6tFxnmuQeA7gwEE5KOy0D0mTcjAT4JA.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City Bangalore to City Bagalkot
      </h3>
      <p class="text-gray-600">
       Starting from Rs.725
      </p>
     </div>
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City I to City J" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/0lZ7FkXAuvZjJhFH5Li9zIenx4Njx3EDDf0NYIfLrH49BMhnA.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City Bangalore to City Davangere
      </h3>
      <p class="text-gray-600">
       Starting from Rs.550
      </p>
     </div>
     <div class="bg-white p-4 rounded-lg shadow-md">
      <img alt="Image of a bus traveling from City K to City L" class="w-full h-40 object-cover rounded-md mb-4" height="200" src="https://storage.googleapis.com/a1aa/image/17LlNvc1eVx3b6oDKFA6LeEuK5WfEVtbSQMl4xJvoROfDYCPB.jpg" width="300"/>
      <h3 class="text-xl font-bold">
       City Bangalore to City Dharwad
      </h3>
      <p class="text-gray-600">
       Starting from Rs.700
      </p>
     </div>
    </div>
   </section>
  </main>
  <footer class="bg-gray-800 text-white p-4 mt-8">
   <div class="container mx-auto text-center">
    <p>
     © 2023 RedBus Clone. All rights reserved.
    </p>
   </div>
  </footer>
 </body>
</html>
