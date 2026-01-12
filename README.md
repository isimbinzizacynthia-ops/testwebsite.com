<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Teliora Africa — Travel & M.I.C.E Services</title>

  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

  <style>
    .marquee {
      width: 100%;
      overflow: hidden;
      position: relative;
    }

    .marquee-content {
      display: flex;
      animation: marquee 18s linear infinite;
    }

    .marquee-content:hover {
      animation-play-state: paused;
    }

    @keyframes marquee {
      0% { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }
  </style>
</head>

<body class="bg-green-50 text-gray-900">

<!-- HEADER -->
<header class="shadow-sm sticky top-0 z-50 bg-white">
  <div class="max-w-7xl mx-auto px-4">
    <div class="flex justify-between py-4 items-center">

      <img src="/Images/logo.jpg" alt="Teliora Africa Logo" class="h-12 rounded-full">

      <nav class="flex items-center gap-5 text-sm font-medium">
        <a href="#know-us" class="hover:text-green-800">Get to know us</a>
        <a href="#services" class="hover:text-green-800">Services</a>
        <a href="#gallery" class="hover:text-green-800">Gallery</a>
        <a href="#contact" class="bg-green-800 text-white px-4 py-2 rounded-md">
          Contact Us
        </a>
      </nav>

    </div>
  </div>
</header>

<!-- HERO / SLIDESHOW -->
<section class="relative">
  <div class="marquee h-96">
    <div class="marquee-content items-center">

      <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1600&q=60"
           class="h-96 w-[500px] object-cover rounded-lg mx-4" alt="">

      <img src="/Images/1.png"
           class="h-96 w-[500px] object-cover rounded-lg mx-4" alt="">

      <img src="/Images/2.png"
           class="h-96 w-[500px] object-cover rounded-lg mx-4" alt="">

      <img src="/Images/3.png"
           class="h-96 w-[500px] object-cover rounded-lg mx-4" alt="">

      <!-- duplicate for smooth loop -->
      <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1600&q=60"
           class="h-96 w-[500px] object-cover rounded-lg mx-4" alt="">

    </div>
  </div>

  <div class="-mt-32 relative z-10">
    <div class="max-w-7xl mx-auto px-4">
      <div class="bg-white rounded-xl shadow-md p-10 border-t-4 border-green-800">

        <h1 class="text-4xl font-extrabold">
          Travel and M.I.C.E support you can rely on
        </h1>

        <p class="mt-4 text-gray-600 max-w-2xl">
          Teliora Africa delivers composed, reliable travel, tourism,
          and M.I.C.E solutions for individuals and organizations who
          value clarity and trust.
        </p>

        <div class="mt-6 flex gap-4">
          <a href="#contact"
             class="bg-green-800 text-white px-6 py-3 rounded-md font-medium">
            Request a Quote
          </a>
          <a href="#know-us"
             class="border border-green-700 text-green-700 px-6 py-3 rounded-md font-medium">
            Learn More
          </a>
        </div>

      </div>
    </div>
  </div>
</section>

<!-- GET TO KNOW US -->
<section id="know-us" class="mt-24 bg-green-900">
  <div class="max-w-7xl mx-auto px-4 py-20">

    <div class="bg-green-50 bg-opacity-95 rounded-xl shadow-sm p-10">

      <div class="flex justify-center gap-4">
        <button onclick="showTab(0)" class="tab-btn bg-green-800 text-white px-6 py-2 rounded-md">
          Overview
        </button>
        <button onclick="showTab(1)" class="tab-btn bg-green-200 text-green-900 px-6 py-2 rounded-md">
          Mission
        </button>
        <button onclick="showTab(2)" class="tab-btn bg-green-200 text-green-900 px-6 py-2 rounded-md">
          Vision
        </button>
      </div>

      <div class="mt-10 max-w-3xl mx-auto text-center">
        <div class="tab-content">
          <p class="text-gray-700">
            Teliora Africa is a travel, tourism, and M.I.C.E company focused on
            structured service delivery, regional expertise, and dependable
            partnerships.
          </p>
        </div>

        <div class="tab-content hidden">
          <p class="text-gray-700">
            Our mission is to deliver ethical, efficient, and well-coordinated
            travel and M.I.C.E services.
          </p>
        </div>

        <div class="tab-content hidden">
          <p class="text-gray-700">
            Our vision is to become a respected African brand with global reach.
          </p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="max-w-7xl mx-auto px-4 mt-24">
  <h2 class="text-3xl font-bold text-green-800">Our Services</h2>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8 mt-10">
    <div class="bg-green-100 p-8 rounded-xl border-l-4 border-green-800">
      <h3 class="font-semibold text-lg">Air Ticketing</h3>
      <p class="text-sm text-gray-700 mt-3">
        Professional flight booking solutions with responsive support.
      </p>
    </div>

    <div class="bg-green-100 p-8 rounded-xl border-l-4 border-green-700">
      <h3 class="font-semibold text-lg">Tourism</h3>
      <p class="text-sm text-gray-700 mt-3">
        Curated travel experiences with cultural depth.
      </p>
    </div>

    <div class="bg-green-100 p-8 rounded-xl border-l-4 border-green-600">
      <h3 class="font-semibold text-lg">M.I.C.E</h3>
      <p class="text-sm text-gray-700 mt-3">
        Meetings, incentives, conferences, and exhibitions.
      </p>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery" class="max-w-7xl mx-auto px-4 mt-24">
  <h2 class="text-3xl font-bold text-green-800">Gallery</h2>

  <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 mt-10">
    <img src="/Images/g1.png" class="w-full h-48 object-cover rounded-lg" alt="">
    <img src="/Images/g2.png" class="w-full h-48 object-cover rounded-lg" alt="">
    <img src="/Images/g3.png" class="w-full h-48 object-cover rounded-lg" alt="">
    <img src="/Images/g4.png" class="w-full h-48 object-cover rounded-lg" alt="">
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="bg-green-800 text-white mt-24">
  <div class="max-w-7xl mx-auto px-4 py-14 grid md:grid-cols-3 gap-8">

    <div>
      <img src="/Images/logo.jpg" class="h-10 rounded-full">
      <p class="text-sm mt-2">Air Ticketing | Tourism | M.I.C.E</p>
    </div>

    <div>
      <h4 class="font-semibold">Contact</h4>
      <p class="text-sm mt-2">Phone: +250 7XX XXX XXX</p>
      <p class="text-sm">Email: hello@telioraafrica.com</p>
    </div>

    <div>
      <h4 class="font-semibold">Follow Us</h4>
      <a class="text-sm hover:underline">Instagram</a>
    </div>

  </div>

  <div class="text-center text-sm text-green-200 py-4">
    © <script>document.write(new Date().getFullYear())</script> Teliora Africa
  </div>
</section>

<script>
  const tabs = document.querySelectorAll('.tab-content');
  const buttons = document.querySelectorAll('.tab-btn');

  function showTab(index) {
    tabs.forEach((tab, i) => {
      tab.classList.toggle('hidden', i !== index);
      buttons[i].classList.toggle('bg-green-800', i === index);
      buttons[i].classList.toggle('text-white', i === index);
      buttons[i].classList.toggle('bg-green-200', i !== index);
      buttons[i].classList.toggle('text-green-900', i !== index);
    });
  }
</script>

</body>
</html>
