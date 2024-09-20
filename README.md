# WorkDuty

**WorkDuty** is an app designed to help housemates coordinate household tasks efficiently and receive timely notifications about their assigned chores.

### Inspiration
WorkDuty is inspired by PagerDuty's approach to organizing and managing tasks, with a focus on household duties.

### User Functionalities:

- **Create Tasks**: Set up common household chores like dishes, cooking, cleaning, etc.
- **Assignment Options**: 
  - Assign tasks using different methods like Round Robin or selecting a specific day for a specific person.
  - Allow for task cancellation or reassignment.
- **Override Tasks**: Override assigned tasks on specific days as needed.
- **Reassign Round Robin**: Reset or restart Round Robin assignments from a specific day onward.
- **Task Notifications**: 
  - Receive reminders via WhatsApp the day before the assigned task.
  - Get a follow-up notification on the day of the task.

### Workflow

1. **Set Up Tasks**:
   - Users can create recurring household tasks (e.g., dishes, cooking, cleaning).
   - Tasks can be categorized and customized based on frequency (daily, weekly, etc.).

2. **Assign Tasks**:
   - Tasks can be assigned using the Round Robin method or manually assigned to specific people for specific days.
   - Users have the option to override task assignments when necessary.

3. **Task Management**:
   - Users can cancel or modify assignments as needed.
   - Round Robin assignments can be reset or restarted from a specific day.

4. **Notifications**:
   - A WhatsApp notification will be sent to housemates the day before a task is due.
   - A reminder will be sent again on the day of the task to ensure it’s completed.

5. **Track and Reassign**:
   - Track completed or overdue tasks.
   - Reassign tasks automatically if not completed, or manually by another user.


### Tech Stack:
- Backend: Node.js + Express
- Database: MongoDB
- Notifications: Twilio
- Frontend: React 
- Deployment: Heroku