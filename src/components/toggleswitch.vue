<!--https://webomnizz.com/create-toggle-switch-button-with-vue-js/-->

<script>

</script>

<template>
    <div class="container">
        <label for="checkbox">
            <input type="checkbox" name="" id="checkbox">
            <div class="toggle"></div>
        </label>
    </div>
</template>

<style scoped>
    .container {
        height: 100%;
        width: 100%;
    }

    #checkbox {
        opacity: 0;
        width: 0;
        height: 0;
    }

    .toggle {
        height: 30px;
        width: 60px;
        position: relative;
        left: 30%;
        border-radius: 9999px;
              
        background-color: #f5f5fc;
        position: relative;
        cursor: pointer;
        transition: all 0.05s ease;
    }

    #checkbox:checked + .toggle::before {
        background-image: url(src/assets/moon.svg);
        background-size: cover;
    }

    #checkbox:checked + .toggle {
        background-color: #0f172a;
    }
    
    .toggle::before {
        content: "";
        height: 25px;
        width: 25px;
        position: absolute;
        left: 7%;
        top: 7%;

        border-radius: 50%;
        box-shadow: 6px 6px 10px #0000006d;
        transition: all 0.25s ease-in-out;

        background-image: url(src/assets/sun.svg);
        background-size: cover;
    }

    #checkbox:checked + .toggle::before {
        position: absolute;
        left: calc(100% - 28px);
    }
</style>
 