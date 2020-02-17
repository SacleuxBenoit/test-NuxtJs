<template>
    <div>
        <header>
            <nuxt-link to="/">Nuxty</nuxt-link>
            <nav>
                <ul>
                    <li><nuxt-link to="/">Home</nuxt-link></li>
                    <li><nuxt-link to="about">About</nuxt-link></li>
                    <li><nuxt-link to="services">Services</nuxt-link></li>
                    <li><nuxt-link to="contact">Contact</nuxt-link></li>
                </ul>
            </nav>
        </header>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
header{
    background:rgb(0, 219, 410);
    display:grid;
    grid-template-columns: repeat(2,auto);
}
</style>