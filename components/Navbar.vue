<template>
  <b-navbar centered spaced>
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <h1 class="is-size-4">Lilitha Mdlalana</h1>
      </b-navbar-item>
    </template>
    <template #end>
      <b-navbar-item href="#"> Home </b-navbar-item>
      <b-navbar-item href="#services">Services</b-navbar-item>
      <b-navbar-item href="#projects"> Projects</b-navbar-item>
      <b-navbar-item href="#skills"> Skills</b-navbar-item>
      <b-navbar-item href="#contact"> Contact</b-navbar-item>
    </template>
  </b-navbar>
</template>
