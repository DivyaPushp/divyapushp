<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   News Portal
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Roboto', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-50 text-gray-900">
  <header class="bg-white shadow">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center py-4">
     <a class="text-2xl font-bold text-indigo-600 flex items-center" href="#">
      <img alt="Logo of News Portal, stylized letter N in blue and white" class="mr-2" height="40" src="https://storage.googleapis.com/a1aa/image/86a60128-d60c-4991-dc20-ee0697db1c42.jpg" width="40"/>
      NewsPortal
     </a>
     <nav class="hidden md:flex space-x-8 text-gray-700 font-semibold">
      <a class="hover:text-indigo-600 transition" href="#">
       Home
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       World
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Politics
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Business
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Technology
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Health
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Sports
      </a>
      <a class="hover:text-indigo-600 transition" href="#">
       Entertainment
      </a>
     </nav>
     <div class="md:hidden">
      <button aria-label="Toggle menu" class="text-gray-700 focus:outline-none focus:ring-2 focus:ring-indigo-600" id="menu-btn">
       <i class="fas fa-bars fa-lg">
       </i>
      </button>
     </div>
    </div>
   </div>
   <nav class="hidden md:hidden bg-white border-t border-gray-200" id="mobile-menu">
    <div class="px-4 pt-2 pb-4 space-y-1">
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Home
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      World
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Politics
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Business
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Technology
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Health
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Sports
     </a>
     <a class="block px-3 py-2 rounded-md text-base font-semibold text-gray-700 hover:bg-indigo-50 hover:text-indigo-600 transition" href="#">
      Entertainment
     </a>
    </div>
   </nav>
  </header>
  <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
   <section aria-label="Top news articles" class="grid grid-cols-1 md:grid-cols-3 gap-8">
    <article class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col">
     <img alt="Breaking news headline 1: A bustling city skyline at sunset with skyscrapers and busy streets" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/82e41ea0-3c97-41e8-f1bd-66c31615201f.jpg" width="600"/>
     <div class="p-4 flex flex-col flex-grow">
      <h2 class="text-xl font-bold mb-2">
       Global Markets Rally Amid Economic Optimism
      </h2>
      <p class="text-gray-700 flex-grow">
       Stock markets around the world surged today as investors reacted positively to new economic data suggesting a strong recovery.
      </p>
      <time class="mt-4 text-sm text-gray-500" datetime="2024-06-01">
       June 1, 2024
      </time>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col">
     <img alt="Breaking news headline 2: A group of scientists in a laboratory examining a new vaccine under bright lights" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/cd3d22f2-355d-4cdb-597b-aa28f375ced2.jpg" width="600"/>
     <div class="p-4 flex flex-col flex-grow">
      <h2 class="text-xl font-bold mb-2">
       New Vaccine Shows Promise in Early Trials
      </h2>
      <p class="text-gray-700 flex-grow">
       Researchers announced promising results from early-stage trials of a vaccine aimed at combating a newly emerging virus strain.
      </p>
      <time class="mt-4 text-sm text-gray-500" datetime="2024-06-02">
       June 2, 2024
      </time>
     </div>
    </article>
    <article class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col">
     <img alt="Breaking news headline 3: A political rally with a large crowd waving flags and banners in a city square" class="w-full h-48 object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/7775ee67-5197-4c95-ed65-9dc23697d41c.jpg" width="600"/>
     <div class="p-4 flex flex-col flex-grow">
      <h2 class="text-xl font-bold mb-2">
       Historic Peace Agreement Signed
      </h2>
      <p class="text-gray-700 flex-grow">
       Leaders from conflicting nations have signed a landmark peace agreement, ending decades of hostilities and opening a new chapter of cooperation.
      </p>
      <time class="mt-4 text-sm text-gray-500" datetime="2024-06-03">
       June 3, 2024
      </time>
     </div>
    </article>
   </section>
   <section aria-label="Latest news" class="mt-12">
    <h3 class="text-2xl font-bold mb-6 border-b border-indigo-600 pb-2">
     Latest News
    </h3>
    <ul class="space-y-6">
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 4: A close-up of a smartphone displaying a social media app with notifications" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/d8002f6a-0072-49b7-4a1e-65643b53559e.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Social Media Platforms Face New Regulations
       </h4>
       <p class="text-gray-700 mb-2">
        Governments worldwide are proposing new regulations aimed at increasing transparency and user privacy on social media platforms.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-04">
        June 4, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 5: A solar farm with rows of solar panels under a bright blue sky" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/72578dfc-fdae-4f09-5bb5-2014e8d45f17.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Renewable Energy Investments Reach New Highs
       </h4>
       <p class="text-gray-700 mb-2">
        Investment in renewable energy projects has surged, driven by global efforts to combat climate change and reduce carbon emissions.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-05">
        June 5, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 6: A professional chef preparing a gourmet dish in a modern kitchen" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/36c9615a-a723-4430-5c57-b02f7a839a2d.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Culinary Trends: Fusion Cuisine on the Rise
       </h4>
       <p class="text-gray-700 mb-2">
        Chefs around the world are blending traditional flavors with modern techniques to create exciting new fusion dishes.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-06">
        June 6, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 7: A crowded marathon race with runners crossing the finish line in a city park" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/3a1af6dc-9d6d-450b-aa5f-b5f078f4fe29.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        City Marathon Draws Record Number of Participants
       </h4>
       <p class="text-gray-700 mb-2">
        The annual city marathon saw a record turnout this year, with runners from over 50 countries competing.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-07">
        June 7, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 8: A futuristic electric car charging at a public charging station" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/9b40a3e5-63d6-46b7-0574-ffbcbf26b44a.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Electric Vehicles Gain Popularity Worldwide
       </h4>
       <p class="text-gray-700 mb-2">
        Sales of electric vehicles continue to rise as governments and consumers push for greener transportation options.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-08">
        June 8, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 9: A group of volunteers planting trees in a community park" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/2c4e0ef8-4623-4179-3c20-382ebdd506a6.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Community Initiatives Focus on Urban Greening
       </h4>
       <p class="text-gray-700 mb-2">
        Local communities are launching projects to increase green spaces and improve urban environments.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-09">
        June 9, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 10: A young artist painting a colorful mural on a city wall" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/48f09238-1032-489c-78ef-dc09a30faf3a.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Street Art Festival Celebrates Local Talent
       </h4>
       <p class="text-gray-700 mb-2">
        The annual street art festival showcased vibrant murals and installations by emerging and established artists.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-10">
        June 10, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 11: A scientist working with a microscope in a high-tech laboratory" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/479e8201-e037-4403-52c0-17c593d62792.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Breakthrough in Cancer Research Announced
       </h4>
       <p class="text-gray-700 mb-2">
        Scientists have discovered a new method to target cancer cells more effectively, potentially improving treatment outcomes.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-11">
        June 11, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 12: A crowded farmers market with fresh fruits and vegetables on display" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/81954a75-f52a-45eb-a1ea-57a7d6d509b6.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Farmers Markets Boost Local Economies
       </h4>
       <p class="text-gray-700 mb-2">
        Local farmers markets are thriving, providing fresh produce and supporting small-scale farmers and artisans.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-12">
        June 12, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 13: A group of children learning coding on laptops in a classroom" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/58ae7fcd-af5e-457e-e9e9-111e83edebda.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        STEM Education Programs Expand in Schools
       </h4>
       <p class="text-gray-700 mb-2">
        Schools are increasing their focus on STEM education to prepare students for future technology-driven careers.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-13">
        June 13, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 14: A scenic mountain trail with hikers enjoying a sunny day" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/3d9a4714-7064-4b35-8739-c0f0533352a8.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Outdoor Recreation Sees Increased Participation
       </h4>
       <p class="text-gray-700 mb-2">
        More people are taking to hiking, biking, and other outdoor activities as interest in healthy lifestyles grows.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-14">
        June 14, 2024
       </time>
      </div>
     </li>
     <li class="bg-white rounded-lg shadow-md overflow-hidden flex flex-col md:flex-row">
      <img alt="News article 15: A modern office space with diverse employees collaborating around a table" class="w-full md:w-48 h-36 object-cover" height="140" src="https://storage.googleapis.com/a1aa/image/01a8543f-b823-47df-b3eb-ed65cd936e8b.jpg" width="200"/>
      <div class="p-4 flex flex-col justify-between">
       <h4 class="text-lg font-semibold mb-1">
        Workplace Diversity Initiatives Gain Momentum
       </h4>
       <p class="text-gray-700 mb-2">
        Companies are implementing new diversity and inclusion programs to foster more equitable work environments.
       </p>
       <time class="text-sm text-gray-500" datetime="2024-06-15">
        June 15, 2024
       </time>
      </div>
     </li>
    </ul>
   </section>
  </main>
  <footer class="bg-white border-t border-gray-200 mt-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 flex flex-col md:flex-row justify-between items-center text-gray-600 text-sm">
    <p>
     © 2024 NewsPortal. All rights reserved.
    </p>
    <div class="flex space-x-6 mt-4 md:mt-0">
     <a aria-label="Facebook" class="hover:text-indigo-600 transition" href="#">
      <i class="fab fa-facebook fa-lg">
      </i>
     </a>
     <a aria-label="Twitter" class="hover:text-indigo-600 transition" href="#">
      <i class="fab fa-twitter fa-lg">
      </i>
     </a>
     <a aria-label="Instagram" class="hover:text-indigo-600 transition" href="#">
      <i class="fab fa-instagram fa-lg">
      </i>
     </a>
     <a aria-label="LinkedIn" class="hover:text-indigo-600 transition" href="#">
      <i class="fab fa-linkedin fa-lg">
      </i>
     </a>
    </div>
   </div>
  </footer>
  <script>
   const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
