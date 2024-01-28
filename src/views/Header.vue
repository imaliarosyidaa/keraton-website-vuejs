<script setup>
    import '../assets/main.css'
</script>

<template>
  <div class="hero">
    <div class="overlap-group">
      <div class="group">
        <div class="rectangle" />
      </div>
      <div class="navbar">
        <div class="div">
          <img class="logo-keraton" alt="Logo keraton" src="../assets/logo_keraton-3.png" />
          <div class="KERATON-KASEPUHAN">
            KERATON <br />
            KASEPUHAN <br />
            CIREBON
          </div>
        </div>
        <div class="navbar-2">
          <div class="text-wrapper">Beranda</div>
          <div class="text-wrapper">Sejarah</div>
          <div class="text-wrapper">Event</div>
          <div class="text-wrapper">Objek Wisata</div>
          <div class="btn-component">
            <div class="text-wrapper-2">Dapatkan tiket</div>
          </div>
        </div>
      </div>
      <div class="text-wrapper-3">
        <div class="text-wrapper-4">Warisan Leluhur Cirebon</div>
        <p class="bersama-lestarikan">
          Bersama Lestarikan <br />
          Keraton Tertua di Kota Cirebon
        </p>
        <div class="btn-component-2">
          <img class="frame" alt="Frame" src="../assets/frame.png" />
        </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
    name : 'Header'
}
</script>

<style>
.hero {
  width: 100%;
}

.hero .overlap-group {
  position: relative;
}

.hero .group {
  background-image: url(../assets/maharanita-nugradianti-mybgf-opmo4-unsplash-2.png);
  background-size: 100% 100vh;
  object-fit: cover;
  background-repeat: no-repeat;
}

.hero .rectangle {
  background-color: #21212166;
  height: 100vh;
}

.hero .navbar {
  align-items: center;
  display: flex;
  gap: 345px;
  justify-content: center;
  left: 0;
  padding: 10px 0px;
  position: absolute;
  top: 0;
  width: 100%;
}

.hero .div {
  height: 84px;
  position: relative;
  width: 219px;
}

.hero .logo-keraton {
  height: 71px;
  left: 0;
  object-fit: cover;
  position: absolute;
  top: 7px;
  width: 68px;
}

.hero .KERATON-KASEPUHAN {
  color: var(--variable-collection-white);
  font-family: var(--raleway-regular-h6-font-family);
  font-size: var(--raleway-regular-h6-font-size);
  font-style: var(--raleway-regular-h6-font-style);
  font-weight: var(--raleway-regular-h6-font-weight);
  left: 78px;
  letter-spacing: var(--raleway-regular-h6-letter-spacing);
  line-height: var(--raleway-regular-h6-line-height);
  position: absolute;
  top: 0;
  width: 139px;
  color:white;
}

.hero .navbar-2 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 30px;
  position: relative;
}

.hero .text-wrapper {
  color: var(--variable-collection-white);
  font-family: var(--raleway-regular-p-font-family);
  font-size: var(--raleway-regular-p-font-size);
  font-style: var(--raleway-regular-p-font-style);
  font-weight: var(--raleway-regular-p-font-weight);
  letter-spacing: var(--raleway-regular-p-letter-spacing);
  line-height: var(--raleway-regular-p-line-height);
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
  color:white;
}

.hero .btn-component {
  align-items: flex-start;
  background-color: var(--primary);
  border-radius: 5px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 10px;
  padding: 5px 25px;
  position: relative;
}

.hero .text-wrapper-2 {
  color: var(--secondary);
  font-family: "Raleway-Bold", Helvetica;
  font-size: 16px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 24px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
  border-radius: 5px;
background: var(--primary, #DAA520);
padding: 5px 25px 5px 25px;
}

.text-wrapper-3{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: center;
  align-items: center;
}

.hero .bersama-lestarikan {
  position: absolute;
  text-align: center;
  top: 233px;
  color: var(--yellow_title, #FFF6E0);
  /* Raleway/regular/display */
  font-family: Raleway;
  font-size: 64px;
  font-style: normal;
  font-weight: 400;
  line-height: 72px;
}

.hero .btn-component-2 {
  align-items: center;
  background-color: var(--primary);
  border-radius: 12.52px;
  display: flex;
  gap: 12.52px;
  padding: 6.26px;
  position: absolute;
  top: 394px;
}

.hero .frame {
  height: 42.48px;
  position: relative;
  width: 42.48px;
  padding: 6.26px;
  border-radius: 12.517px;
background: var(--primary, #DAA520);
}
</style>