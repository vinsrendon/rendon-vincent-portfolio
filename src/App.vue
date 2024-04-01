<script setup>
import { RouterLink, RouterView } from 'vue-router'

function showSidebar(){
    const sidebar = document.querySelector('.sidebar');
    sidebar.style.display = 'flex';
}

function hideSidebar(){
    const sidebar = document.querySelector('.sidebar');
    sidebar.style.display = 'none';
    unlockScroll();
}
function lockScroll() {
  document.body.classList.remove('unlock-scroll');
  document.body.classList.toggle('lock-scroll');
}
function unlockScroll(){
  document.body.classList.remove('lock-scroll');
  document.body.classList.toggle('unlock-scroll');
}
</script>

<template>
  <header>
      <nav>
        <ul class="sidebar">
          <li @click="hideSidebar()"><a href="#"><img class="icon" src="@/assets/x-icon.svg" alt="close sidebar icon"></a></li>
          <li @click="hideSidebar()"><a href="#home">Home</a></li>
          <li @click="hideSidebar()"><a href="#works">Works</a></li>
          <li @click="hideSidebar()"><a href="#skills">Skills</a></li>
          <li @click="hideSidebar()"><a href="#about">About</a></li>
          <li @click="hideSidebar()"><a href="#contact">Contacts</a></li>
        </ul>
        <ul>
          <li><a href="" class="name">Vincent</a></li>
          <li><a class="hideOnMobile" href="#home">Home</a></li>
          <li><a class="hideOnMobile" href="#works">Works</a></li>
          <li><a class="hideOnMobile" href="#skills">Skills</a></li>
          <li><a class="hideOnMobile" href="#about">About</a></li>
          <li><a class="hideOnMobile" href="#contact">Contacts</a></li>
          <li class="menuButton" @click="lockScroll(),showSidebar()"><a><img class="icon" src="@/assets/menu-icon.svg" alt="open sidebar icon"></a></li>
        </ul>
      </nav>
  </header>
  <RouterView />  
</template>

