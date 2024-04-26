<h2 align='center'>kanban - task management</h2>
<p align="center">
<a href="https://github.com/pritisingh-1"><img title="Author" src="https://img.shields.io/badge/Author-pritisingh-1--red.svg?style=for-the-badge&logo=github"></a>
</p>

<p align="center">
<a href="https://github.com/pritisingh-1"><img title="Followers" src="https://img.shields.io/github/followers/pritisingh-1?color=teal&style=flat-square"></a>

</a>

</p>

<p align="center">
   kanban - task management ( Pixel Technologies Frontend Developer Assignment )
</p>

## live-link 🔗

<a target="_blank" href="https://kanban-priti.netlify.app/"><b>https://kanban-priti.netlify.app/</b></a>

## Assignment Details:

- Set up a React.js project with TypeScript.
- Implement CRUD operations for the board.
- Utilize reusable components to enhance modularity and efficiency.
- Integrate React Hooks Forms for form handling, ensuring smooth data management.
- Additional features or enhancements are welcome to showcase your skills and creativity.

## Implemented features added

- Ensure the app adjusts to fit any screen size
- Display hover effects for all interactive elements
- Allow users to create, view, modify, and delete boards and tasks
- Provide validation messages for form errors during the creation or editing of boards and tasks
- Enable users to complete subtasks and relocate tasks across columns
- Include an option to toggle the visibility of the board sidebar
- Offer a choice to switch between light and dark themes
- Bonus: Facilitate task reordering and status updates through drag-and-drop functionality
- Bonus: Maintain persistence of user changes, using localStorage for data storage

### Expected Behaviour added

- Boards
  - Clicking different boards in the sidebar will change to the selected board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Clicking in the dropdown menu "Edit Board" opens up the "Edit Board" modal where details can be changed.
  - Columns are added and removed for the Add/Edit Board modals.
  - Deleting a board deletes all columns and tasks and requires confirmation.
- Columns
  - A board needs at least one column before tasks can be added. If no columns exist, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal where columns are added.
- Tasks
  - Adding a new task adds it to the bottom of the relevant column.
  - Updating a task's status will move the task to the relevant column. If you're taking on the drag and drop bonus, dragging a task to a different column will also update the status.

# tech stack used

- html, css, js, React, TypeScript, React Hooks Forms

## Installation

```sh

# Clone the repo
$ git clone repo-url

# Install
$ npm install


# Start
$ npm run dev

# Access your app
$ http://localhost:${PORT}

```

## Author

👤 **Priti Kumari**

- Github: [@pritisingh-1](https://github.com/pritisingh-1)
- LinkedIN: [@priti-singh90](https://www.linkedin.com/in/priti-singh90/)

---

## License

&copy; Priti Kumari | MIT
