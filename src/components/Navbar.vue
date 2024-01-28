<template>
    <div class="navbar">
      <div class="group">
        <img class="logo-keraton" alt="Logo keraton" src="./assest/logo-keraton-3.png" />
        <div class="KERATON-KASEPUHAN">
          KERATON <br />
          KASEPUHAN <br />
          CIREBON
        </div>
      </div>
      <div class="div">
        <div class="text-wrapper">Beranda</div>
        <div class="text-wrapper">Sejarah</div>
        <div class="text-wrapper">Event</div>
        <div class="text-wrapper">Objek Wisata</div>
        <div class="btn-component">
          <div class="text-wrapper-2">Dapatkan tiket</div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Navbar",
  };
  </script>
  
  <style>
  .navbar {
    align-items: center;
    display: flex;
    gap: 345px;
    justify-content: center;
    padding: 10px 0px;
    position: relative;
    width: 1280px;
  }
  
  .navbar .group {
    height: 84px;
    position: relative;
    width: 219px;
  }
  
  .navbar .logo-keraton {
    height: 71px;
    left: 0;
    object-fit: cover;
    position: absolute;
    top: 7px;
    width: 68px;
  }
  
  .navbar .KERATON-KASEPUHAN {
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
  }
  
  .navbar .div {
    align-items: center;
    display: inline-flex;
    flex: 0 0 auto;
    gap: 30px;
    position: relative;
  }
  
  .navbar .text-wrapper {
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
  }
  
  .navbar .btn-component {
    align-items: flex-start;
    background-color: var(--primary);
    border-radius: 5px;
    display: inline-flex;
    flex: 0 0 auto;
    gap: 10px;
    padding: 5px 25px;
    position: relative;
  }
  
  .navbar .text-wrapper-2 {
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
  }
  </style>
  