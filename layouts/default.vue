<template>
    <header>
        <nav>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink :to="`/pokemon/${1}`" >Pokemon</NuxtLink ></li>
            </ul>
        </nav>
    </header>  
    <slot />
</template>

<script></script>

<style></style>