# Notes-Vue-Js
Membuat aplikasi web notes sederhana menggunakan vue js
![Document](https://user-images.githubusercontent.com/55887819/75626208-8dfaca00-5c00-11ea-8220-ebc9fc00a1c2.png)


# How to use:
  - jalankan web server & database (xamapp)
  - buka file vue.config.js, ubah publicPath: "dist/" menjadi publicPath: "./"
  - open with cmd lokasi folder notes vue js
  - cd resources
  - npm install
  - npm run serve
  
# How to use API :
  - buka file listNotes & formNotes (resources/src/component)
  - ubah isi dari 
    - formNotes :
      -getData() {
      axios.get("Lokasi penyimpanan/server ex:http://localhost/Project/belajar_vue/note").then(response => {
      ....
      
    - listNotes :
      - axios
        .post("Lokasi penyimpanan/server ex:http://localhost/Project/belajar_vue/note", params) ....
    
# Database :
  - Buat database notes_vue & table note (id , title , description)
  - atau export database yang saya berikan

# NOTES!!
  - Agar bisa deploy, ubah isi dari vue.config.js, publicPath: "./" menjadi publicPath: "dist/"
  - open with cmd lokasi folder notes vue js
  - cd resources
  - npm run build
