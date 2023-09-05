<script setup>

</script>

<template>
  <div id="app">
    <nav id="navigation">
      <li>Home</li>
      <li>To-Do List</li>
      <li>Journal Entries</li>
      <li>Schedule</li>
    </nav>

    <div id="welcome-login">
      <h1> Welcome _insert user's name_!</h1>
      <button>Sign up?</button>
      <p>If you already have an account, <a href="#">log in</a></p>
    </div>

    <div id="to-do-list">
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

    <div id="journal-entry">
      <h2>Journal Entries</h2>
      <input type="text" id="entry-title" placeholder="Title of Entry...">
      <input type="date" id="entry-date">
      <p><a href="#">Previous Entries?</a></p>
      <input type="text" id="entry-desc" placeholder="Whatchu thinking?">
    </div>

    <div id="schedule">
      <h2>Schedule</h2>
      <!--Follow this guide : https://www.educative.io/answers/how-to-create-an-animated-calendar-with-html-and-css -->
    </div>
  </div>
</template>

<script>

export default {

}
</script>

<style scoped>
@media (min-width: 1024px) {}
</style>
