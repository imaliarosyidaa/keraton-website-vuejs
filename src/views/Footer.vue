<template>
    <div class="footer">
    <div class="rigth-container">
        <p>
            Subscribes your email for updates!
        </p>
    </div>
      <div class="div">
        <div class="text-wrapper-2">Quick Links</div>
        <div class="text-wrapper-3">Beranda</div>
        <div class="text-wrapper-4">Sejarah</div>
        <div class="text-wrapper-5">Event</div>
        <div class="text-wrapper-6">Objek Wisata</div>
      </div>
      <div class="div-2">
        <div class="text-wrapper-2">Company</div>
        <div class="text-wrapper-3">About us</div>
        <div class="text-wrapper-4">Partners</div>
        <div class="text-wrapper-5">Contact</div>
      </div>
      <p class="jalan-kasepuhan">
        Jalan Kasepuhan 43
        <br />
        Cirebon, Jawa Barat
        <br />
        45114
      </p>
      <div class="div-3">
        <p class="p">@ 2024 Keraton Kasepuhan Cirebon</p>
        <p class="text-wrapper-7">In collaboration with PT Curaweda Palagan Simbiotech</p>
      </div>
      <div class="logo">
        <div class="KERATON-KASEPUHAN">
          KERATON <br />
          KASEPUHAN <br />
          CIREBON
        </div>
        <img class="logo-keraton" alt="Logo keraton" src="../assets/logo_keraton-3.png" />
      </div>
      <div class="overlap-group">
        <div class="text-wrapper-8">Enter your email</div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Footer",
  };
  </script>
  
  <style>
  .footer {
    height: 796px;
    position: relative;
    width: 100%;
  }

  .rigth-container p{
    color: var(--secondary, #212121);
    /* Raleway/regular/h4 */
    font-family: Raleway;
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px; /* 133.333% */
    left: 738px;
    position: absolute;
    top: 212px;
    width: 434px;
  }
  
  .footer .div {
    height: 196px;
    left: 88px;
    position: absolute;
    top: 293px;
    width: 169px;
  }
  
  .footer .text-wrapper-2 {
    left: 0;
    position: absolute;
    top: 0;
    white-space: nowrap;
    color: var(--secondary, #212121);
    /* Raleway/regular/h4 */
    font-family: Raleway;
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 40px; /* 133.333% */
  }
  
  .footer .text-wrapper-3 {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 0;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 51px;
    white-space: nowrap;
  }
  
  .footer .text-wrapper-4 {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 0;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 90px;
    white-space: nowrap;
  }
  
  .footer .text-wrapper-5 {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 0;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 129px;
    white-space: nowrap;
  }
  
  .footer .text-wrapper-6 {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 0;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 168px;
    white-space: nowrap;
  }
  
  .footer .div-2 {
    height: 157px;
    left: 325px;
    position: absolute;
    top: 293px;
    width: 143px;
  }
  
  .footer .jalan-kasepuhan {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 88px;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 550px;
  }
  
  .footer .div-3 {
    height: 24px;
    left: 88px;
    position: absolute;
    top: 734px;
    width: 1108px;
  }
  
  .footer .p {
    color: var(--secondary);
    font-family: var(--raleway-regular-p-font-family);
    font-size: var(--raleway-regular-p-font-size);
    font-style: var(--raleway-regular-p-font-style);
    font-weight: var(--raleway-regular-p-font-weight);
    left: 0;
    letter-spacing: var(--raleway-regular-p-letter-spacing);
    line-height: var(--raleway-regular-p-line-height);
    position: absolute;
    top: 0;
    white-space: nowrap;
  }
  
  .footer .text-wrapper-7 {
    color: var(--secondary);
    font-family: var(--raleway-regular-p-font-family);
    font-size: var(--raleway-regular-p-font-size);
    font-style: var(--raleway-regular-p-font-style);
    font-weight: var(--raleway-regular-p-font-weight);
    left: 701px;
    letter-spacing: var(--raleway-regular-p-letter-spacing);
    line-height: var(--raleway-regular-p-line-height);
    position: absolute;
    top: 0;
    white-space: nowrap;
  }
  
  .footer .logo {
    height: 84px;
    left: 88px;
    position: absolute;
    top: 133px;
    width: 218px;
  }
  
  .footer .KERATON-KASEPUHAN {
    color: var(--secondary);
    font-family: var(--raleway-regular-h6-font-family);
    font-size: var(--raleway-regular-h6-font-size);
    font-style: var(--raleway-regular-h6-font-style);
    font-weight: var(--raleway-regular-h6-font-weight);
    left: 77px;
    letter-spacing: var(--raleway-regular-h6-letter-spacing);
    line-height: var(--raleway-regular-h6-line-height);
    position: absolute;
    top: 0;
    width: 139px;
  }
  
  .footer .logo-keraton {
    height: 71px;
    left: 0;
    object-fit: cover;
    position: absolute;
    top: 7px;
    width: 68px;
  }
  
  .footer .overlap-group {
    background-color: #daa520;
    border-radius: 10px;
    height: 58px;
    left: 738px;
    position: absolute;
    top: 315px;
    width: 431px;
  }
  
  .footer .text-wrapper-8 {
    color: var(--variable-collection-white);
    font-family: "Raleway-ExtraBold", Helvetica;
    font-size: 20px;
    font-weight: 800;
    left: 29px;
    letter-spacing: 0;
    line-height: 28px;
    position: absolute;
    top: 14px;
    white-space: nowrap;
    color: var(--white, #FFF);
  }
  </style>
  