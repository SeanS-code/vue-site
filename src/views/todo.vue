<template>
    <div id="todo">
        <h2>To-Do List</h2>
        <div id="add-to-list">
            <h4>Add to To-Do</h4>
            <input type="text" id="add-item" placeholder="Insert new task...">
            <button onclick="" class="addBtn">Add</button>
        </div>
        <div id="task-list">
            <ul>
            <li>Finish HTML & CSS</li>
            <li>Add the JS and Vue</li>
            </ul>
        </div>
    </div>
</template>

<style>
#todo {
    position: absolute;
    top: 100%;

    width: 100%;
    height: 60%;

    background-color: aqua;
}

</style>