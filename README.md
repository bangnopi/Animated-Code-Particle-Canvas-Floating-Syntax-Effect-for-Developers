# Animated-Code-Particle-Canvas-Floating-Syntax-Effect-for-Developers
Dibangun menggunakan HTML5 Canvas murni tanpa library tambahan, efek ini sangat ringan dan bisa dijadikan latar belakang tematik untuk website bertema teknologi, portfolio developer, landing page SaaS, atau dashboard proyek coding.

🎨 Deskripsi

Efek visual ringan berbasis HTML5 Canvas yang menampilkan potongan kode (code snippets) melayang di layar seperti partikel bercahaya.
Setiap partikel menampilkan sintaks acak dari berbagai bahasa pemrograman dan berjalan halus di seluruh layar dengan efek “mengetik” dinamis.

Script ini cocok dijadikan background interaktif untuk:

Halaman portfolio developer

Dashboard atau landing page SaaS

Website bertema teknologi / AI

Tampilan loading atau splash screen yang keren

Dibangun tanpa library eksternal — hanya HTML, CSS, dan JavaScript murni.

🚀 Fitur Utama

💻 Pure Vanilla JS — tanpa dependensi pihak ketiga.

🔠 Efek ngetik animasi pada setiap partikel kode.

🌈 Multi-language snippets: JavaScript, PHP, SQL, Bash, JSON, HTML, CSS, dan lainnya.

🧩 Multi-layer Canvas: lapisan partikel berbeda untuk kedalaman visual.

📱 Responsive dan mobile-safe (mendukung safe-area-inset untuk iOS).

⚙️ Auto Resize dengan ResizeObserver agar tetap proporsional saat layar berubah ukuran.

🧠 Optimized performance — animasi tetap halus dengan density adaptif terhadap ukuran layar.

🧰 Cara Penggunaan

Pastikan di HTML kamu sudah ada elemen pembungkus:

<div id="particle-zone">
  <canvas id="canvas2"></canvas>
</div>


Tambahkan kode CSS & JavaScript dari script ini ke halaman kamu (biasanya sebelum </body>).

Simpan file HTML dan buka di browser — partikel kode akan otomatis muncul dan bergerak halus di layar.

💡 Tips Tambahan

Warna partikel dapat diubah dari bagian rgba(0,255,255,opacity) → misal ke rgba(255,0,200,opacity) untuk nuansa pink/ungu.

Jumlah dan kecepatan partikel bisa diatur lewat variabel:

const DENSITY_AREA = 140000; // makin kecil makin banyak partikel
const MAX_SPEED = 0.28;      // makin besar makin cepat

🧠 Relevansi untuk Developer

Script ini terinspirasi dari suasana coding di layar terminal modern — cocok buat proyek bertema developer tools, AI, automation, atau framework seperti MeChat yang ingin menampilkan identitas teknologi kuat lewat desain visual dinamis.

🏷️ Tags

#HTML5Canvas #JavaScriptAnimation #ParticleEffect
#CodeBackground #DeveloperTheme #CyberUI #MeChat
