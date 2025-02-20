## Laporan Praktikum

|       | Pemrograman Berbasis Framework 2024 |
| ----- | ----------------------------------- |
| NIM   | 123244107027018                     |
| Nama  | Muhamad Hafiidh Afandi              |
| Kelas | TI - 4K RPL                         |

### Jawaban Soal 1

1.  Git
    Git adalah version control system yang digunakan untuk melacak perubahan kode, berkolaborasi dengan tim, dan mengelola repositori di platform seperti GitHub, GitLab, atau Bitbucket.

    VS Code (Visual Studio Code)
    VS Code adalah text editor atau IDE ringan yang digunakan untuk menulis, mengedit, dan menjalankan kode dengan fitur seperti debugging, ekstensi, dan terminal bawaan.

    Node.js
    Node.js adalah runtime JavaScript yang memungkinkan kita menjalankan JavaScript di luar browser. Digunakan untuk membangun aplikasi backend, menjalankan server, dan mengelola package manager (npm/yarn).

2.  ![screenshot](/image1.png)

### Jawaban Soal 2

1.  TypeScript
    TypeScript adalah superset dari JavaScript yang menambahkan fitur static typing untuk membantu mendeteksi kesalahan saat coding, meningkatkan keamanan, dan mempermudah pengelolaan kode dalam proyek besar.

    ESLint
    ESLint adalah linter untuk JavaScript dan TypeScript yang membantu mendeteksi dan memperbaiki kesalahan dalam kode berdasarkan aturan yang sudah ditentukan. Ini memastikan konsistensi dan kualitas kode.

    Tailwind CSS
    Tailwind CSS adalah framework CSS utility-first yang memungkinkan pengembang membuat desain langsung di HTML atau JSX tanpa perlu menulis banyak CSS custom.

    App Router
    App Router adalah sistem routing baru di Next.js (mulai Next.js 13) yang menggunakan folder app/ dan memanfaatkan fitur React Server Components, server actions, serta layout yang lebih fleksibel.

    Import Alias
    Import alias memungkinkan kita mengimpor file dengan jalur pendek, sehingga lebih mudah dikelola. Misalnya, daripada:

    Turbopack
    Turbopack adalah bundler baru di Next.js yang dibuat untuk menggantikan Webpack. Ini jauh lebih cepat dalam development dan hot module replacement (HMR), sehingga meningkatkan produktivitas pengembang.

2.  .next/ → Folder build otomatis yang dibuat oleh Next.js saat proyek dijalankan atau di-build. Ini berisi file hasil kompilasi untuk server-side rendering (SSR) dan static site generation (SSG).
    node_modules/ → Berisi semua dependency yang diinstal menggunakan npm install atau yarn install.
    public/ → Folder untuk menyimpan aset statis, seperti gambar, favicon, atau file lain yang bisa diakses langsung dari URL (/nama-file).
    src/app/ → Struktur App Router Next.js, di mana folder ini digunakan untuk mengatur halaman dan komponen utama aplikasi.
    favicon.ico → Ikon yang muncul di tab browser saat halaman website dibuka.
    globals.css → File CSS global yang diterapkan ke seluruh aplikasi.
    layout.tsx → Komponen utama yang membungkus seluruh halaman, biasanya berisi header, footer, atau tema yang konsisten.
    page.tsx → File yang bertindak sebagai halaman utama dari aplikasi. Dalam sistem App Router, file page.tsx di dalam folder app/ otomatis dianggap sebagai halaman utama (/).
    .gitignore → Berisi daftar file/folder yang tidak boleh di-track oleh Git (misalnya node_modules, .next, dll.).
    eslint.config.mjs → Konfigurasi untuk ESLint, digunakan untuk memastikan kualitas kode dengan standar tertentu.
    next-env.d.ts → File deklarasi TypeScript untuk Next.js, memastikan bahwa TypeScript mengenali fitur bawaan Next.js.
    next.config.ts → File konfigurasi utama Next.js, digunakan untuk mengatur custom settings seperti redirect, rewrites, optimasi gambar, dll.
    package-lock.json & package.json →
    package.json → Berisi daftar dependency proyek serta skrip perintah yang bisa dijalankan (npm run dev, npm run build, dll.).
    package-lock.json → File yang mengunci versi dependency agar tetap konsisten di semua lingkungan.
    postcss.config.mjs → Konfigurasi PostCSS, sering digunakan bersama Tailwind CSS untuk pemrosesan CSS yang lebih optimal.
    README.md → File dokumentasi proyek, biasanya berisi petunjuk instalasi dan penggunaan aplikasi.
    tailwind.config.ts → File konfigurasi untuk Tailwind CSS, digunakan untuk menyesuaikan warna, font, spacing, dll.
    tsconfig.json → Konfigurasi untuk TypeScript, menentukan aturan kompilasi dan fitur TypeScript yang digunakan dalam proyek.

3.  ![screenshot](/assets/image2.png)

### Jawaban Soal 3

1.  ![screenshot](/assets/image3.png)

### Jawaban Soal 4

1.  Sintaks user.imageUrl berarti bahwa kita mengakses properti imageUrl dari objek user. Properti ini biasanya digunakan untuk menyimpan URL gambar profil pengguna.

Mengakses URL gambar pengguna – Digunakan untuk mendapatkan atau menampilkan gambar profil pengguna.
Menyimpan URL gambar dalam basis data – Mempermudah penyimpanan dan pengelolaan gambar pengguna.
Menampilkan gambar dalam antarmuka pengguna – Digunakan dalam frontend untuk menampilkan foto profil atau avatar pengguna.
Mengirim data gambar melalui API – Digunakan dalam respons API untuk menyediakan informasi gambar pengguna.
Menentukan gambar default jika tidak tersedia – Digunakan untuk menampilkan gambar pengganti jika pengguna belum mengunggah foto.
Memproses atau mengubah gambar pengguna – Bisa digunakan dalam fitur pengeditan gambar atau pemrosesan gambar dinamis.

2.  ![screenshot](assets/image3.png)
