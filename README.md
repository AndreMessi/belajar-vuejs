# belajar-vuejs
seri belajar vuejs untuk pemula
Logika Program

Sebelum mulai menggunakan Vuejs, saya memikirkan dulu apa yang akan dilakukan program ini.

    Paste URL
    Ambil lebar dan tinggi dari URL
    Ambil nama file gambar untuk teks alternatif
    Buat tag amp-img

Declarative Rendering Vuejs

Berdasarkan panduan yang diberikan di dokumentasi Vuejs, saya diberikan contoh kode berikut.

html: <div id="app">
  {{ message }}
</div>

javascript : var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
