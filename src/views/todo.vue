<template>
    <div id="todo">
        <h2 class="heading">To-Do List</h2>
        <div id="add-to-list">
            <h4>Add to To-Do</h4>
            <input type="text" id="add-item" placeholder="Insert new task...">
            <button onclick="" class="addBtn">Add</button>
        </div>
        <div id="task-list">
            <h2>Daily</h2>
            <ul class="daily">
                <li>Filler</li>
                <li>Filler</li>
                <li>Filler</li>
                <li>Filler</li>
            </ul>
            
            <h2>Long-Term Goals</h2>
            <ul class="long">
                <li>Filler</li>
                <li>Filler</li>
                <li>Filler</li>
                <li>Filler</li>
            </ul>
        </div>
    </div>
</template>

<style scoped>
#todo {
    position: absolute;
    top: 100%;

    width: 100%;
    height: 80%;

    background-color: #0F172A;
}

.heading {
    font-size: 2em;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    text-transform: uppercase;
    color: #60a5fa;

    position: absolute;
    top: 3%;
    left: 1.8%;

    display: inline-block;
}

#add-to-list {
    position: relative;
    top: 2.1%;

    display: inline-block;
    width: 12%;
    padding: 0 2%;
}

#add-to-list h4 {
    margin-bottom: 5%;
}

#todo h4 {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: white;
}

#task-list {
    position: relative;
    top: 12%;
    left: 1%;
    
    display: inline-block;
    width: 65%;
    height: 80%;

    padding: 0 5%;
    border-left: 2px solid white;
}

#task-list h2 {
    font-size: 1.5em;
    position: absolute;
    top: 0;
    left: 6.5%;

    display: inline-block;

    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-weight: bold;
    text-transform: uppercase;
    color: white;
}

.daily {
    position: relative;

    display: inline-block;
    height: 60%;
    width: 40%;
}

.daily li {
    cursor: pointer;
    position: relative;
    top: 10%;

    display: flex;
    padding: 1.5% 10%;

    background: #eee;
    font-size: 1.1em;
}

.daily li:nth-child(odd) {
  background: #f9f9f9;
}

.long {
    position: relative;
    left: 15%;

    display: inline-block;
    height: 60%;
    width: 40%;
}

.long li {
    cursor: pointer;
    position: relative;
    top: 10%;
    
    padding: 1.5% 10%;

    background: #eee;
    font-size: 1.1em;
}

.long li:nth-child(odd) {
  background: #f9f9f9;
}

</style>