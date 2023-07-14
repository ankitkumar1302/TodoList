<h1>To-Do List App</h1>

<h2>Overview</h2>

<p>This is a basic Android app to create and manage a list of tasks or to-do items.</p>

<h2>Features</h2>

<ul>
  <li>Create new to-do items by entering task name</li>
  <li>Mark to-do items as completed</li> 
  <li>Delete existing to-do items</li>
  <li>Persist data using SQLite database</li>
  <li>RecyclerView to display to-do list</li>
</ul>

<h2>Code Overview</h2>

<p>The main components are:</p>

<ul>
  <li><code>MainActivity</code> - Displays RecyclerView list and adds items</li>
  <li><code>ToDoAdapter</code> - RecyclerView adapter to render each item</li>
  <li><code>ToDoModel</code> - Data class for a ToDo item </li>
  <li><code>ToDoDatabaseHelper</code> - SQLite database helper to manage data</li>
</ul>

<h2>Running the App</h2>

<p>This app is written in Java and can be built using Android Studio:</p>

<ol>
  <li>Download or clone the code</li>
  <li>Open project in Android Studio</li>
  <li>Run on an emulator or connected device</li>
</ol>

<p>Users can add, edit, and delete to-do items which are saved to a local database.</p>
