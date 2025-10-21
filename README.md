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
      color: #e5e7eb;
      font-family: 'Poppins', sans-serif;
      overflow-x: hidden;
      overflow-y: auto;
      scroll-behavior: smooth;
    }
    h1, h2 {
      color: #2aff12;
      text-shadow: 0 0 15px #ff6600, 0 0 30px #54ff00;
    }
    .glass-card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      transition: transform 0.5s ease, box-shadow 0.5s ease;
    }
    .glass-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #54ff00;
    }
    .buy-btn {
      position: relative;
      background: linear-gradient(90deg, #a3ff12, #00ff88);
      color: #000;
      font-weight: bold;
      border-radius: 9999px;
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .buy-btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #00ff88;
    }
    .username {
      position: fixed;
      top: 50%;
      right: 10px;
      transform: rotate(90deg) translateY(-50%);
      font-size: 14px;
      font-weight: bold;
      letter-spacing: 2px;
      color: rgba(163, 255, 18, 0.6);
      animation: float 6s ease-in-out infinite;
      z-index: 10;
    }
    @keyframes float {
      0%, 100% { transform: rotate(90deg) translateY(-50%) translateX(0); }
      50% { transform: rotate(90deg) translateY(-50%) translateX(10px); }
    }
    .discount {
      background: #00ff88;
      color: #000;
      font-weight: bold;
      padding: 8px 16px;
      border-radius: 9999px;
      position: absolute;
      top: 10px;
      right: 10px;
      box-shadow: 0 0 15px #00ff88;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%, 100% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.1); opacity: 0.8; }
    }
    .insta-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
      color: white;
      padding: 12px 20px;
      border-radius: 50px;
      font-weight: bold;
      font-size: 14px;
      display: flex;
      align-items: center;
      gap: 8px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.6);
      animation: glow 2s infinite alternate;
      transition: all 0.3s ease;
      z-index: 50;
    }
    .insta-float:hover {
      transform: scale(1.1) rotate(-3deg);
    }
    @keyframes glow {
      0% { box-shadow: 0 0 10px #f09433, 0 0 20px #dc2743; }
      100% { box-shadow: 0 0 20px #bc1888, 0 0 40px #e6683c; }
    }
    .insta-icon {
      width: 20px;
      height: 20px;
      fill: white;
    }
  </style>
</head>

<body class="min-h-screen flex flex-col items-center p-6 relative">
  <!-- Floating Username -->
  <div class="username">suyog_deore7</div>

  <!-- Header -->
  <header class="text-center mb-8">
    <h1 class="text-4xl font-bold mb-2">🚀 Build Your Gaming Powerhouse</h1>
    <p class="text-gray-400 text-lg">HP Victus – performance and design, made for gamers and creators</p>
  </header>

  <!-- Combined Product + Why Choose Section -->
  <div class="relative max-w-6xl glass-card rounded-2xl p-6 grid md:grid-cols-3 gap-6 items-center">
    <div class="discount">18% OFF</div>

    <!-- Laptop Image -->
    <div class="flex justify-center md:col-span-1">
      <img src="https://github.com/techybysuyog/TechbySuyog.com/blob/main/Screenshot%202025-10-02%20211742.png?raw=true"
           alt="HP Smartchoice Victus Gaming Laptop"
           class="rounded-xl shadow-lg w-80" />
    </div>

    <!-- Product Info -->
    <div class="md:col-span-1">
      <h2 class="text-2xl font-semibold mb-3 text-white">HP Smartchoice Victus Gaming Laptop</h2>
      <ul class="text-gray-300 space-y-1 mb-4 text-sm">
        <li>💻 13th Gen Intel Core i7-13620H</li>
        <li>🎮 6GB NVIDIA RTX 4050 GPU</li>
        <li>⚡ 16GB DDR4 RAM (Upgradeable)</li>
        <li>💾 512GB SSD Storage</li>
        <li>🖥️ 15.6" FHD, 144Hz, 300 nits Display</li>
        <li>🎨 Mica Silver, Sleek 2.3kg Design</li>
        <li>📦 Windows 11 + MS Office 2024</li>
      </ul>
      <p class="text-xl font-semibold text-gray-500 line-through">₹ 1,00,594</p>
      <p class="text-2xl font-bold text-[#00ff88] mb-4">₹ 81,990 (After 18% OFF)</p>
      <a href="https://amzn.to/3J8Icm2" target="_blank" class="buy-btn block w-full text-center py-3 text-lg">
        Buy Now on Amazon
      </a>
    </div>

    <!-- Why Choose Section (Now Inside Same Box) -->
    <div class="md:col-span-1">
      <h2 class="text-2xl font-bold mb-4">Why Choose HP Victus?</h2>
      <p class="text-gray-300 mb-4">
        The <strong>HP Smartchoice Victus</strong> is designed for gamers, creators, and professionals who demand high performance.
        With the latest 13th Gen Intel processor and RTX 4050 GPU, you can enjoy seamless multitasking, smooth gameplay, and immersive visuals.
      </p>
      <ul class="list-disc pl-6 text-gray-400 space-y-2 text-sm">
        <li>✅ Excellent cooling system for longer gaming sessions</li>
        <li>✅ Upgrade-friendly design with RAM & storage expansion</li>
        <li>✅ 144Hz FHD display for fluid motion</li>
        <li>✅ Premium build with a sleek silver finish</li>
        <li>✅ Backed by HP reliability and support</li>
      </ul>
    </div>
  </div>

  <!-- Floating Instagram Button -->
  <a href="https://www.instagram.com/techby_suyog?igsh=MmtzMWlxdmY5MzRh" target="_blank" class="insta-float">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="insta-icon">
      <path d="M12 2.2c3.2 0 3.6 0 4.9.1 1.2.1 2 .2 2.5.4.6.2 1 .5 1.5 1 .4.4.8.9 1 1.5.2.5.3 1.3.4 2.5.1 1.3.1 1.7.1 4.9s0 3.6-.1 4.9c-.1 1.2-.2 2-.4 2.5-.2.6-.5 1-1 1.5-.4.4-.9.8-1.5 1-.5.2-1.3.3-2.5.4-1.3.1-1.7.1-4.9.1s-3.6 0-4.9-.1c-1.2-.1-2-.2-2.5-.4-.6-.2-1-.5-1.5-1-.4-.4-.8-.9-1-1.5-.2-.5-.3-1.3-.4-2.5-.1-1.3-.1-1.7-.1-4.9s0-3.6.1-4.9c.1-1.2.2-2 .4-2.5.2-.6.5-1 1-1.5.4-.4.9-.8 1.5-1 .5-.2 1.3-.3 2.5-.4 1.3-.1 1.7-.1 4.9-.1M12 0C8.7 0 8.3 0 7 .1 5.6.2 4.6.4 3.8.7c-.9.3-1.6.8-2.3 1.5-.7.7-1.2 1.4-1.5 2.3C-.2 5.3 0 6.3.1 7.7.1 9 .1 9.4.1 12s0 3 .1 4.3c.1 1.4.3 2.4.7 3.2.3.9.8 1.6 1.5 2.3.7.7 1.4 1.2 2.3 1.5.8.4 1.8.6 3.2.7 1.3.1 1.7.1 4.3.1s3 0 4.3-.1c1.4-.1 2.4-.3 3.2-.7.9-.3 1.6-.8 2.3-1.5.7-.7 1.2-1.4 1.5-2.3.4-.8.6-1.8.7-3.2.1-1.3.1-1.7.1-4.3s0-3-.1-4.3c-.1-1.4-.3-2.4-.7-3.2-.3-.9-.8-1.6-1.5-2.3-.7-.7-1.4-1.2-2.3-1.5-.8-.4-1.8-.6-3.2-.7C15 0 14.6 0 12 0Zm0 5.8A6.2 6.2 0 1 0 18.2 12 6.2 6.2 0 0 0 12 5.8Zm0 10.2A4 4 0 1 1 16 12a4 4 0 0 1-4 4Zm6.4-10.8a1.4 1.4 0 1 0 1.4 1.4 1.4 1.4 0 0 0-1.4-1.4Z"/>
    </svg>
    @techby_suyog
  </a>

 
<!-- Second Product: WZATCO Yuva Go Smart Projector -->
<div class="relative max-w-6xl glass-card rounded-2xl p-6 grid md:grid-cols-3 gap-6 items-center mt-10">
  <div class="discount">77% OFF</div>

  <!-- Product Image -->
  <div class="flex justify-center md:col-span-1">
    <img src="c:\Users\Suyog\Downloads\projectora a.jpg"
         alt="WZATCO Yuva Go Smart Projector"
         class="rounded-xl shadow-lg w-80" />
  </div>

  <!-- Product Details -->
  <div class="md:col-span-1">
    <h2 class="text-2xl font-semibold mb-3 text-white">WZATCO Yuva Go Smart Projector</h2>
    <ul class="text-gray-300 space-y-1 mb-4 text-sm">
      <li>🎥 Android 13.0 Smart Projector with built-in Netflix, Prime Video & YouTube</li>
      <li>🖥️ 1080P & 4K Supported (Native 720p)</li>
      <li>🔄 Rotatable Compact Design</li>
      <li>📐 Auto & 4D Keystone Correction</li>
      <li>📶 WiFi 6 + Bluetooth Connectivity</li>
      <li>🔊 HDMI ARC, Screen Mirroring & USB Playback</li>
      <li>⚪ Sleek White Finish</li>
    </ul>

    <p class="text-xl font-semibold text-gray-500 line-through">₹ 21,990</p>
    <p class="text-2xl font-bold text-[#00ff88] mb-4">₹ 4,999 (After 77% OFF)</p>

    <a href="https://amzn.to/4oonlKi" target="_blank"
       class="buy-btn block w-full text-center py-3 text-lg">
       Buy Now on Amazon
    </a>
  </div>

  <!-- Why Choose Section -->
  <div class="md:col-span-1">
    <h2 class="text-2xl font-bold mb-4">Why Choose WZATCO Yuva Go?</h2>
    <ul class="list-disc pl-6 text-gray-400 space-y-2 text-sm">
      <li>✅ Android 13.0 with full OTT app support</li>
      <li>✅ Crisp 1080p visuals with 4K decoding</li>
      <li>✅ Auto + 4D Keystone for easy setup</li>
      <li>✅ Compact & rotatable modern design</li>
      <li>✅ WiFi 6 ensures lag-free streaming</li>
      <li>✅ Best Seller in Home Cinema Projectors</li>
      <li>✅ Trusted by 3,500+ happy customers</li>
    </ul>
  </div>
</div>
 <!-- Footer -->
  <footer class="mt-10 text-gray-500 text-sm">
<li>_           Suyog Sunil Deore             _</li>
   © 2025 GameOn Tech Store. All Rights Reserved.
  </footer>
</body>
</html>
