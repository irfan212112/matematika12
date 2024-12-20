<html lang="id">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ruang Belajar Matematika</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
   body {
       font-family: 'Roboto', sans-serif;
   }
   nav {
       position: sticky;
       top: 0;
       background-color: aliceblue;
       z-index: 1;
       border-bottom: 1px solid rgb(3, 3, 3);
   }
   nav a {
       color: #ffffff;
       transition: color 0.3s;
   }
   nav a:hover {
       color: #d1fae5;
   }
   .btn-primary {
       background-color: #22c55e;
       color: white;
       padding: 10px 20px;
       border-radius: 50px;
       transition: transform 0.2s, background-color 0.3s;
   }
   .btn-primary:hover {
       background-color: #15803d;
       transform: scale(1.1);
   }
   header {
       position: relative;
       text-align: center;
   }
   header img {
       filter: brightness(75%);
   }
   header h1 {
       animation: fadeInDown 2s ease-in-out;
   }
   @keyframes fadeInDown {
       0% { opacity: 0; transform: translateY(-50px); }
       100% { opacity: 1; transform: translateY(0); }
   }
   ul.list-disc li {
       padding-left: 1rem;
   }
   .footer-link {
       color: #4b5563;
       transition: color 0.3s;
   }
   .footer-link:hover {
       color: #22c55e;
   }
  </style>
 </head>
 <body class="bg-gray-100">
  <!-- Navigasi -->
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-4 py-2 flex justify-between items-center">
     <a class="text-2xl font-bold text-green-500" href="#">
      MATEMATIKA
     </a>
     <ul class="flex space-x-6">
      <li><a class="text-gray-700 hover:text-green-600" href="pendahuluan.html">Beranda</a></li>
      <li><a class="text-gray-700 hover:text-green-600" href="materi1.html">Materi</a></li>
      <li><a class="text-gray-700 hover:text-green-600" href="latihan.html">latihan</a></li>
      <li><a class="text-gray-700 hover:text-green-600" href="kalkulator.html">kalkulator</a></li>
     </ul>
     <a class="bg-green-500 text-white px-4 py-2 rounded" href="">
      Mulai
     </a>
    </div>
   </nav>
   
   <!-- Header dengan gambar -->
   <header class="relative">
    <img alt="unram" class="w-full h-96 object-cover" src="unram.jpg" />
    <div class="absolute inset-0 bg-black opacity-50"></div>
    <div class="absolute inset-0 flex flex-col justify-center items-center text-center text-white px-4">
     <h1 class="text-4xl md:text-5xl font-bold animate__animated animate__fadeIn animate__delay-1s">
      Selamat Datang di Ruang Belajar Matematika
     </h1>
     <p class="mt-4 text-lg md:text-xl">Pendidikan Matematika FKIP Universitas Mataram</p>
     <a class="mt-6 bg-white text-black px-6 py-3 rounded-full" href="#">Mulai</a>
    </div>
   </header>

   <!-- Konten Utama -->
   <main class="container mx-auto px-4 py-16">
    <div class="flex flex-col md:flex-row items-center">
     <div class="md:w-2/3">
      <h2 class="text-2xl font-bold mb-4">Ruang Belajar Matematika</h2>
      <p class="mb-4">
       Situs ini dirancang untuk membantu siswa belajar dan memahami konsep matematika secara interaktif. Platform ini menawarkan berbagai materi, soal latihan, video pembelajaran, dan fitur evaluasi diri, memungkinkan pengguna untuk belajar secara mandiri. Dengan teknologi digital, ruang belajar ini dapat diakses kapan saja, memberikan fleksibilitas serta pengalaman belajar yang lebih menarik melalui visualisasi dan alat bantu interaktif. Berikut adalah beberapa fungsi dari platform ini:
      </p>
      <ul class="list-disc list-inside mb-4">
       <li class="flex items-center mb-2">
        <i class="fas fa-check-circle text-green-600 mr-2"></i>
        Akses Materi yang Beragam
       </li>
       <p>Platform ini menyediakan berbagai materi, mulai dari teori dasar hingga tingkat lanjut. Ini termasuk video tutorial, modul interaktif, soal latihan, dan e-book yang dapat diakses kapan saja.</p>
       <li class="flex items-center mb-2">
        <i class="fas fa-check-circle text-green-600 mr-2"></i>
        Latihan Soal Interaktif
       </li>
       <p>Berbagai platform menawarkan latihan soal interaktif dengan penjelasan langsung. Siswa dapat segera mengetahui jawaban mereka serta cara penyelesaiannya, yang membantu mereka belajar dari kesalahan.</p>
       <li class="flex items-center mb-2">
        <i class="fas fa-check-circle text-green-600 mr-2"></i>
        Pembelajaran yang Disesuaikan
       </li>
       <p>Beberapa platform dilengkapi sistem adaptif yang menyesuaikan materi sesuai kebutuhan siswa. Ini memungkinkan proses belajar yang lebih pribadi dan efektif.</p>
       <li class="flex items-center mb-2">
        <i class="fas fa-check-circle text-green-600 mr-2"></i>
        Visualisasi dan Simulasi
       </li>
       <p>Beberapa konsep matematika yang abstrak sering kali sulit dipahami tanpa visualisasi. Platform digital biasanya menyediakan alat untuk visualisasi grafik dan diagram.</p>
      </ul>
     </div>
     <div class="md:w-1/3 mt-8 md:mt-0 md:ml-8">
    
     </div>
    </div>
   </main>

   <!-- Footer -->
   <footer class="bg-white py-8">
    <div class="container mx-auto px-4">
     <div class="flex flex-col md:flex-row justify-between">
      <div class="mb-8 md:mb-0">
       <h3 class="text-lg font-bold mb-2">UNRAM</h3>
       <p>Jln. Majapahit No.62<br/>Universitas Mataram</p>
       <p>Telepon: 083132552592<br/>Email: irfanzidni619@gmail.com</p>
      </div>
      <div class="mb-8 md:mb-0">
       <h3 class="text-lg font-bold mb-2">Mitra</h3>
       <ul>
        <li><a class="footer-link" href="#">UNRAM</a></li>
        <li><a class="footer-link" href="#">FKIP UNRAM</a></li>
        <li><a class="footer-link" href="#">Pendidikan Mipa</a></li>
        <li><a class="footer-link" href="#">Pendidikan Matematika</a></li>
       </ul>
      </div>
      <div class="mb-8 md:mb-0">
       <h3 class="text-lg font-bold mb-2">Layanan Kami</h3>
       <ul>
        <li><a class="footer-link" href="#">Layanan 1</a></li>
        <li><a class="footer-link" href="#">Layanan 2</a></li>
        <li><a class="footer-link" href="#">Layanan 3</a></li>
       </ul>
      </div>
      <div>
       <h3 class="text-lg font-bold mb-2">Dukung Program Ini</h3>
       <p class="mb-4">Kirimkan Saran dan Komentar Anda Serta Berlangganan</p>
       <form class="flex">
        <input class="px-4 py-2 border border-gray-300 rounded-l focus:outline-none" placeholder="Email" type="email" required />
        <button class="bg-green-600 text-white px-4 py-2 rounded-r" type="submit">Kirim</button>
       </form>
      </div>
     </div>
    </div>
   </footer>
 </body>
</html>
<div class="container">
    
