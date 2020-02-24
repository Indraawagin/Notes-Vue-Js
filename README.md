# Notes-Vue-Js
Membuat aplikasi web notes sederhana menggunakan vue js

# How to use:
  - buka file vue.config.js, ubah publicPath: "dist/" menjadi publicPath: "./"
  - git bash lokasi folder notes vue js
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
