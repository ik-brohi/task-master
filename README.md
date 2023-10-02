# Task Master - Quiz 1 EAD

## Functional Requirements

Here is a list of functional requirements for the task management application:

1. Users can create a new task with the following details:
   - Task Name
   - Task Description
   - Urgency (Urgent, Medium, Low)
   - Size (Large, Medium, Small)
   - Developer Name
   - Developer Email

2. Users must fill out all the required fields to create a task.

3. Upon submitting the form, a new task card is generated and displayed on the page with the entered task details.

4. Task cards are displayed in a responsive grid layout on the page.

5. Each task card includes the following information:
   - Task Number (auto-generated)
   - Task Name
   - Task Description
   - Urgency (color-coded)
   - Size (color-coded)
   - Assigned Developer Name
   - Developer Email
   - Edit Button (to edit task details)
   - Delete Button (to delete the task)

6. Users can edit an existing task by clicking the "Edit" button on the task card.

7. When editing, a modal window opens with the task details pre-filled in the form.

8. Users can modify the task details in the modal and save the changes.

9. Upon saving, the task card is updated with the new details.

10. Users can delete an existing task by clicking the "Delete" button on the task card.

11. Upon deletion, the task card is removed from the page.

12. Task data is persisted using `sessionStorage`.

13. When the page is reloaded, previously created tasks are loaded from `sessionStorage` and displayed on the page.

14. Tasks created by the user are stored in `sessionStorage` to ensure they are not lost upon page refresh.

15. Input validation ensures that all required fields are filled out when creating a task.

16. The user interface is designed with Bootstrap to provide a clean and responsive layout.

## Design Links

- Figma Design: [Task Master Figma Design](https://www.figma.com/file/qKrpegGnA5zNUdqp2qfbvm/Untitled?type=design&node-id=0%3A1&mode=design&t=jYTArW6mvD7npqLJ-1)

- Miro Board: [Task Master Miro Board](https://miro.com/app/board/uXjVPgPDMrI=/?share_link_id=517267533366)

## Live Link

Check out the live version of Task Master: [Task Master Live](https://task-master-app-quiz-one.netlify.app/)
