<template>
    <div id="welcome-login">
        <h4><span style="color: #60a5fa;">{</span> Insert a compelling introduction of product <span style="color: #60a5fa;">}</span></h4>
        <h1><span style="color: #60a5fa;">{ Ins</span>ert Name of App }</h1>
        <div class="button"><a href="">Sign up</a></div>
    </div>
</template>

<style>
#welcome-login {
    position: absolute;
    top: 30%;

    height: 55%;
    width: 100%;
}

#welcome-login h1 {
    font-size: 5em;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: white;

    text-align: center;

    position: relative;
    top: 10%;
}

#welcome-login h4 {
    font-size: 1.5em;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: #C8D2E4;
    
    text-align: center;
}

#welcome-login a {
    color: #C8D2E4;
    text-decoration: none;
    text-transform: uppercase;
    text-align: center;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;

    position: absolute;
    top: 50%;
    left: 44.5%;

    background-color: #1A2434;
    padding: 1.2% 3%;
    transition: all .25s ease-in-out;
}

#welcome-login a:hover {
    color: #60a5fa;
    text-transform: uppercase;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

    background-color: white;
    transition: all .25s ease-in-out;
}

</style>