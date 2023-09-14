<script setup>
import Toggle from '../components/toggleswitch.vue'
</script>

<template>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
        <nav id="navigation">
            <img src="src/assets/logo.jpg"/>
            <div class="toggle"><Toggle /></div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">To-Do List</a></li>
                <li><a href="#">Journal Entries</a></li>
                <li><a href="#">Schedule</a></li>
                <li><a href="#">Login</a></li>
            </ul>
        </nav>
</template>

<style>

#navigation {
    position: absolute;
    width: 98.2%;
    display: flex;
    padding: 1em;
}

#navigation img {
    position: relative;
    left: 17%;
    width: 3%;
    height: 3%;
    display: inline-block;
}

.toggle {
    position: relative;
    left: 48%;
    width: 7%;
    height: 2.1em;
    display: inline-block;
}

#navigation ul {
    display: inline-block;
    width: 43%;
    height: 2.1em;
    position: relative;
    left: 46%;
    padding: 0;

    list-style: none;
}

#navigation ul li {
    display: inline-block;
    width: 10em;
    
    margin: 0 0.35em;
    padding: .5em;

    text-align: center;
    vertical-align: middle;

    font-family: 'Poppins', sans-serif;
    font-size: .85em;
    text-transform: uppercase;
}

#navigation ul li:nth-child(3) {
    margin: 0 0.5em;
}

#navigation ul li:first-child {
    position: relative;
}

#navigation ul li:last-child {
    position: relative;
}

#navigation a {
    color: #C8D2E4;
    text-decoration: none;
    transition: all .25s ease-in-out;
}

#navigation a:hover {
    color: white;
    transition: all .25s ease-in-out;
}
</style>