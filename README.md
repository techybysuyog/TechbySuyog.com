<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HP Victus Gaming Laptop Promo</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      background: radial-gradient(circle at top right, #0f172a, #000);
      color: #fff;
      font-family: 'Poppins', sans-serif;
      background-size: 200% 200%;
      animation: moveBg 10s ease infinite alternate;
      scroll-behavior: smooth;
    }
    @keyframes moveBg {
      from { background-position: 0% 50%; }
      to { background-position: 100% 50%; }
    }

    .glass-card {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(16px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: all 0.3s ease;
    }
    .glass-card:hover {
      transform: translateY(-5px);
      border-color: rgba(255, 255, 255, 0.4);
      box-shadow: 0 0 25px rgba(59, 130, 246, 0.3);
    }

    .insta-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.4);
      transition: transform 0.3s ease;
      z-index: 50;
    }
    .insta-btn:hover {
      transform: scale(1.1) rotate(8deg);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .fade-in { animation: fadeIn 1s ease-in-out; }
  </style>
</head>
<body class="min-h-full flex flex-col items-center p-6">

  <!-- ===== HEADER ===== -->
  <header class="text-center mb-10 fade-in">
    <h1 class="text-4xl font-extrabold text-blue-400 drop-shadow-lg">
      💻 HP Victus Gaming Laptop
    </h1>
    <p class="text-gray-300 mt-2 text-lg">Power. Performance. Precision. All in One Machine.</p>
  </header>

  <!-- ===== MAIN CONTENT ===== -->
  <main class="max-w-5xl w-full flex flex-col items-center space-y-12">

    <!-- ===== LAPTOP CARD ===== -->
    <div class="grid md:grid-cols-2 gap-8 glass-card p-6 rounded-2xl fade-in w-full">
      <img src="https://github.com/techybysuyog/TechbySuyog.com/blob/main/Screenshot%202025-10-02%20211742.png?raw=true" 
           alt="HP Victus Gaming Laptop" 
           class="rounded-2xl shadow-lg w-full object-cover">
      
      <div class="flex flex-col justify-center">
        <h2 class="text-2xl font-bold mb-3 text-blue-400">HP Smartchoice Victus</h2>
        <ul class="list-disc list-inside text-gray-300 space-y-2">
          <li><strong>Processor:</strong> Intel Core i5 13th Gen</li>
          <li><strong>Graphics:</strong> NVIDIA RTX 4050 6GB</li>
          <li><strong>Display:</strong> 15.6" FHD 144Hz</li>
          <li><strong>Storage:</strong> 512GB SSD</li>
          <li><strong>RAM:</strong> 16GB DDR5</li>
          <li><strong>OS:</strong> Windows 11 Home</li>
          <li><strong>Battery:</strong> 70 Wh – Up to 8 hrs</li>
        </ul>
      </div>
    </div>

    <!-- ===== WHY CHOOSE SECTION ===== -->
    <section class="glass-card p-6 rounded-2xl w-full fade-in">
      <h2 class="text-2xl font-bold mb-4 text-blue-400">Why Choose HP Victus?</h2>
      <p class="text-gray-300 mb-4">
        The <strong>HP Smartchoice Victus</strong> is designed for gamers, creators, and professionals who demand performance and reliability. 
        Equipped with the latest 13th Gen Intel processor and RTX 4050 GPU, it delivers seamless multitasking and ultra-smooth gaming visuals.
      </p>
      <ul class="list-disc pl-6 text-gray-400 space-y-2">
        <li>✅ Advanced cooling for longer gaming sessions</li>
        <li>✅ Easy RAM and storage upgrades</li>
        <li>✅ 144Hz FHD display for fluid motion</li>
        <li>✅ Elegant silver design with backlit keyboard</li>
        <li>✅ Backed by HP reliability and premium support</li>
      </ul>
    </section>

  </main>

  <!-- ===== FOOTER ===== -->
  <footer class="mt-12 text-center text-gray-400 text-sm fade-in">
    <p>© 2025 Designed & Developed by <span class="text-blue-400 font-semibold">Suyog Deore</span></p>
  </footer>

  <!-- ===== INSTAGRAM FLOAT BUTTON ===== -->
  <a href="https://www.instagram.com/suyog_deore/" target="_blank" class="insta-btn" aria-label="Instagram">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-7 h-7">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M7.75 2h8.5A5.75 5.75 0 0 1 22 7.75v8.5A5.75 5.75 0 0 1 16.25 22h-8.5A5.75 5.75 0 0 1 2 16.25v-8.5A5.75 5.75 0 0 1 7.75 2z" />
      <circle cx="12" cy="12" r="3.5" />
      <circle cx="17" cy="7" r="1" />
    </svg>
  </a>

</body>
</html>
