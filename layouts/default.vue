<template>
    <div>
        <header class="header">
            <nav class="nav">
                <NuxtLink to="/" class="logo">Udemy</NuxtLink>
                <ul class="menu">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/courses">Courses</NuxtLink></li>
                    <li><NuxtLink to="/login">Login</NuxtLink></li>
                    <li><NuxtLink to="/signup">Signup</NuxtLink></li>
                </ul>
                <div class="auth-buttons">
                    <NuxtLink to="/login" class="button login">Oturum aç</NuxtLink>
                    <NuxtLink to="/signup" class="button signup">Kaydol</NuxtLink>
                  </div>
            </nav>
        </header>
        <div>
            <slot />
        </div>
    </div>
    </template>

<style scoped>
    .router-link-exact-active {
        color: #12b488;
    }
</style>