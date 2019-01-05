# TokenERC20
Token ERC20

Disini saya akan memberitahukan cara membuat Cryptocurrency dari turunan Ethereum (Token ERC20).

Ikuti langkah - langkah berikut :
1. Download NodeJs terlebih dahulu di https://nodejs.org/en/download/ .
2. Setelah NodeJs diinstal kita menuju ke terminal (Linux) atau Command Prompt (Windows).
3. Instal Ganache terlebih dahulu dengan cara mengetikkan pada aplikasi tersebut seperti dibawah ini :
   npm install -g ganache-cli
4. Setelah selesai terinstall hingga akhir, ketikkan seperti dibawah ini :
   ganache-cli
5. Jika sudah berhasil, selanjutnya kita buka browser kita dan masuk ke remix.ethereum.org (IDE untuk program Solidity).
6. Klik tulisan Run pada kanan-atas tampilan website, lalu ubah Environment-nya menjadi "Web3 Provider" dan klik Ok. Masukkan pada form text yang telah disediakan dengan menggantikannya "http://127.0.0.1:8545" dan klik Ok.
7. Copy dan Paste program yang telah disediakan pada format .sol pada repositori ini kedalam IDE tersebut dan CTRL+C untuk menyimpan program.
8. Setelahnya akan muncul hasil yang berjalan pada arah kanan tampilan dengan tulisan Token ERC20 yang artinya program sukses dijalankan.
9. Sekarang dapat dilakukan pengisian Supply token, nama token, dan simbol token pada form yang disediakan dari hasil program tersebut.
10. Hasil akhir akan muncul pada Debug console dibawah dan itulah Token ERC20 yang kita buat.
