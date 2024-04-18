<template>
  <div>
    <div class="wrapper">
      <div class="sidebar">
        <div class="profile">
          <img src="../assets/Profil.jpg" alt="">
          <h3>Abdul Wahid</h3>
          <p>122312456</p>
          <p>Dosen Pembimbing</p>
        </div>
      </div>
    </div>
    <div class="Bagian3">
      <h2>Input Nilai KP/TA</h2>
      <div class="box-container">
        <div class="box">
          <p>Daftar Mahasiswa Kerja Praktik (KP)</p>
          <router-link to="/DaftarKp" class="btn btn-lihat">Lihat</router-link>
        </div>
        <div class="box">
          <p>Daftar Mahasiswa Tugas Akhir (TA)</p>
          <router-link to="DaftarTa" class="btn btn-lihat">Lihat</router-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InputNilai'
}
</script>

<style scoped>
/* Your CSS styles here */

:root {
  --primary-color: #f9fafc;
  --primary-color-dark: #fdfdff;
  --secondary-color: #fafafd;
  --text-dark: #ffffff;
  --extra-light: #edf0f3;
  --max-width: 1200px;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style: none;
  font-family: 'Open Sans', sans-serif;
}

a {
  text-decoration: none;
}

.wrapper .sidebar {
  background: #363636;
  position: fixed;
  top: 0;
  left: 0;
  width: 250px;
  height: 100%;
  padding: 100px 0;
}

.wrapper .sidebar .profile {
  margin-bottom: 30px;
  text-align: center;
}

.wrapper .sidebar .profile img {
  display: block;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  margin: auto;
}

.wrapper .sidebar .profile h3 {
  color: #fdfcfc;
  margin: 30px 0 5px;
}

.wrapper .sidebar .profile p {
  color: rgb(250, 248, 248);
  font-size: 14px;
  margin: 10px;
}

.Bagian3 {
  width: 100%;
  max-width: 700px;
  margin: auto;
}

h2 {
  margin-bottom: 80px;
  font-size: 1.6rem;
}

.box-container {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

.box {
  background-color: #f0f0f0;
  padding: 40px;
  border-radius: 5px;
  text-align: center;
  width: 45%;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.box p {
  margin-bottom: 30px;
  font-size: 1.2rem;
}

.btn-lihat {
  background-color: #3498db;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
}

.btn-lihat:hover {
  background-color: #2980b9;
}
</style>
