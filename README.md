# Nama aplikasi dan deskripsi
Nama Aplikasi : Gigih Playlist Music
Deskripsi : Gigih Playlist Music adalah sebuah aplikasi berbasis website yang dibuat menggunakan Library React Js. Aplikasi ini merupakan aplikasi yang berepresentasi pada aplikasi Spotify dimana API yang digunakan adalah API yang disediakan pada Spotify melalui https://developer.spotify.com/. Awasome Playlist Music GIGIH mendukung penggunanya membuat playlist musik yang mereka sukai dan mencari musik yang ingin mereka masukkan kedalam Playlist lagu yang telah dibuat, namun untuk dapat melakukan hal tersebut pengguna harus terlebih dahulu melakukan login dengan menggunakan akun Spotify agar dapat masuk kedalam aplikasi. 



# Fitur yang kamu implementasi
Adapun fitur yang terdapat pada Gigih Playlist Music adalah:
1. Login in using their Spotify Account
2. Search for artists or songs
3. Create Playlist
4. Display List of song

# Cara install dan cara menjalankan aplikasi kamu.
Untuk dapat menjalankan aplikasi terlebih dahulu kita menginstall aplikasi dimana kita dapat clone repository
1. Akses repository {link github}, Pilih menu Code > Clone > Copy URL HTTPS
2. Buat sebuah baru didirektori anda kemudian buka Git Bash anda, buat lah perintah
    > git clone https://repo
3. Setelah Projectnya terdownload pada direktori anda selanjutnya buka menggunakan Text Editor yang anda miliki disini saya menggunakan Visual Studio Code. Pilih New Terminal pada text editor anda kemudian ketik perintah 
    > npm install
    npm install ini digunakn untuk menginstal package-package yang ada pada Aplikasi yang dibuat.
4. Buka https://developer.spotify.com/ untuk membuat API Spotify kita sendiri, dimana ini akan digunakan didalam aplikasi. Login pada https://developer.spotify.com/ kemudian pilih "CREATE AN APP" masukkan App Name dan App description, kemudian pilih "EDIT SETTING" isi Redirect URIs dengan "http://localhost:3000/" (agar url redirect untuk API kita dapat dibaca oleh aplikasi). Kemudian copy Client ID dari API yang telah kita buat.
5. Selanjutnya kita harus mengedit Client id pada Project ini dimana terletak pada "src/components/Login.jsx/. Masukkan sesuai dengan Client id yang sudah anda buat.
6. Kembali ke terminal pada text editor, jalankan perintah
    > npm start
    Maka aplikasi dapat anda jalankan pada komputer anda.
7. Aplikasi ini juga sudah di deploy dimana dapat diakses melalui link url berikut ini "".