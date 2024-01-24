# testground
Pratikum Jobsheet 1

#Deskripsi Proyek
Proyek ini adalah contoh sederhana dari server Node.js yang menyajikan pesan "Hello World!" pada port tertentu.

#Instalasi
1)	Pastikan Anda telah menginstal Node.js. Jika belum, [unduh dan instal Node.js](https://nodejs.org/).
2)	Salin kode di bawah ini ke dalam file dengan ekstensi `.js` (misalnya, `app.js`).
console.log('Welcome to Node.js!')
const http = require('http');
const server = http.createServer((req, res) => {
res.writeHead(200, {'Content-Type': 'text/plain'});
res.end('Hello World!\n');
});
const PORT = 3000;
server.listen(PORT, '127.0.0.1');
console.log(`Server running at http://127.0.0.1:${PORT}/`);
3)	Buka terminal dan arahkan ke direktori tempat Anda menyimpan file.
4)	Jalankan perintah node app.js untuk menjalankan server.
5)	Buka browser dan akses http://127.0.0.1:3000/ untuk melihat pesan "Hello World!".

