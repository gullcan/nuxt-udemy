<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/courses">Courses</NuxtLink>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/courses">Courses</NuxtLink></li>
                    <li><NuxtLink to="/login">Login</NuxtLink></li>
                    <li><NuxtLink to="/signup">Signup</NuxtLink></li>
                </ul>
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