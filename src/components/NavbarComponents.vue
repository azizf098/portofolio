<template>
    <Navbar>
      <template #logo>
        <NavbarLogo
          alt="Flowbite logo"
          image-url="https://static.vecteezy.com/system/resources/previews/000/599/745/original/vector-business-corporate-s-letter-logo.jpg"
        >
          PORTOFOLIO
        </NavbarLogo>
      </template>
      <template #default="{ isShowMenu }">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink link="#">Beranda</NavbarLink>
          <NavbarLink link="#layanan">Kontak</NavbarLink>
          <NavbarLink link="#tentang">Tentang</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
  </template>
  
  <script setup>
  import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue';
  </script>
  
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@700&display=swap');
  
  .logo-navbar {
    font-family: 'Josefin Sans', sans-serif;
  }
  </style>