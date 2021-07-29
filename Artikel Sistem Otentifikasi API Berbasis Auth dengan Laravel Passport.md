 ## Mengenal Sistem Otentikasi API berbasis Auth dengan Laravel Passport
 Laravel merupakan salah satu framework atau kerangka kerja yang dapat membantu programmer dalam pengembangan website berbasis PHP.
 
 **API** (Application Programming Interface) atau biasa juga dikenal dengan Web Service digunakan untuk menghubungkan atau mengintegrasikan dua bagian aplikasi yang berbeda secara bersamaan, biasanya digunakan untuk pengembangan aplikasi yang berbasis mobile.
 
 **Passport** merupakan salah satu proyek laravel yang dikembangkan untuk melakukan otentikasi berbasis token.
 
 Apabila di Laravel Passport harus menginstall package lagi, namun jika menggunakan metode API Token, tidak perlu menginstall package lain karena fitur ini sudah ada pada Laravel secara Out of the box.

 Cara kerja dari Autentikasi ini adalah dengan memeriksa identitas pengguna. Jika pengguna sudah terdaftar dan tervalidasi pada saat login, maka akan pengguna tersebut dapat login. akan tetapi jika pengguna tersebut belum terdaftar datanya, maka diharuskan register terlebih dahulu (seperti sosial media)
