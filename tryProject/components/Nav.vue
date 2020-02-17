<template>
    <div>
        <header>
            <nuxt-link to="/" class="logo">Nuxty</nuxt-link>
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

.logo, li a {
    padding : 1em 2em;
    display:block;
    text-transform: uppercase;
    text-decoration: none;
    font-weight: bold;
    color : white;
    font-size: .9rem;
}
nav{
    justify-self: right;
}
ul{
    list-style-type: none;
}
li{
    display: inline;
}
li a {
    padding : 1em 2em;
    display: inline-block;
    background: rgba(0, 0, 0, 0.1)
}
</style>