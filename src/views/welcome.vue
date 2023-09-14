<template>
    <div id="welcome-login">
        <h4>{ Insert a compelling introduction of product }</h4>
        <h1>{ Insert Name of App }</h1>
        <div class="button"><a href="">Sign up?</a></div>
    </div>
</template>

<style>
#welcome-login {
    position: absolute;
    top: 30%;

    height: 55%;
    width: 100%;
    /*border: 1px solid white;*/
}

#welcome-login h1 {
    font-size: 5em;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: white;

    text-align: center;
}

#welcome-login h4 {
    font-size: 1.5em;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: #C8D2E4;
    
    text-align: center;
}

#welcome-login a {
    color: black;
    text-decoration: none;

    position: absolute;
    top: 50%;
    left: 44.5%;

    background-color: #C8D2E4;
    padding: 1% 3%;
    transition: all .25s ease-in-out;
}

#welcome-login a:hover {
    color: black;
    background-color: white;
    transition: all .25s ease-in-out;
}

</style>