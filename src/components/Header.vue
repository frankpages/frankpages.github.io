<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
    <nav class="navbar navbar-expand-lg" style="background-color: #ffffff;">
        <div class="container"> 
            <RouterLink to="/" class="navbar-brand">Franklin Ramos</RouterLink><small class="text-muted">Graphic designer & Motion graphic animator</small>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
            <!-- <ul class="navbar-nav mr-auto">
            </ul> -->
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <RouterLink to="/about" class="nav-link">About me</RouterLink>
                </li>
                <li class="nav-item">
                    <RouterLink to="/about" class="nav-link">Resume</RouterLink>
                </li>
                <li class="nav-item">
                    <RouterLink to="/about" class="nav-link">Portfolio</RouterLink>
                </li>
                <li class="nav-item">
                    <RouterLink to="/about" class="nav-link">Contacts</RouterLink>
                </li>
            </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
/* nav {
    display: flex;
    gap: 2rem;
    background-color: white;
    padding: 1rem;
} */
</style>