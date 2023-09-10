<script setup>
import Toggle from './toggleswitch.vue'
</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

    <nav id="navigation">
        <img src="src/assets/logo.jpg"/>
        <ul>
            <Toggle />
            <li><a href="#">Home</a></li>
            <li><a href="#">To-Do List</a></li>
            <li><a href="#">Journal Entries</a></li>
            <li><a href="#">Schedule</a></li>
        </ul>
    </nav>
</template>

<style>

#navigation {
    position: absolute;
    width: 98.2%;
    border: 1px solid black;
    display: flex;
    padding: 1em;
}

#navigation img {
    /* 17% left */
    margin: 0 0 0 17%;
    width: 3%;
    height: 3%;
    display: inline-block;
    border: 1px solid yellow;
}

#navigation ul {
    display: inline-block;
    width: 50em;
    height: 2.1em;
    margin: 0 0 0 35%;
    padding: 0;

    list-style: none;
    border: 1px solid orange;
}

#navigation ul li {
    display: inline-block;
    width: 10em;

    margin: 0 0.35em;
    padding: .5em;
    
    /* Center the text vertically */
    text-align: center;
    vertical-align: middle;
    border: 1px solid red;

    font-family: 'Poppins', sans-serif;
    font-size: 1em;
    text-transform: uppercase;
}

#navigation ul li:first-child {
    margin: 0 0.35em 0 0;
}

#navigation ul li:last-child {
    margin: 0 0 0 0.35em;
}

a {
    color: #C8D2E4;
    text-decoration: none;
}

</style>