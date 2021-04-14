<template>
  <div id="app">
    <div id="nav">
      <span id="title">Mélodie Ly</span>
        <div id="nav-link">
          <router-link to="/">Accueil</router-link>
          <router-link to="/skills">Compétences</router-link>
          <router-link to="/projects">Réalisations</router-link>
          <router-link to="/contact">Contact</router-link>
        </div>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url('./assets/styles.css');
</style>
