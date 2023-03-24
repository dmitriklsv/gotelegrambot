### Task
Create a scheduler telegram bot that can save the user and his tasks in the database and return them when requested

**Telegram bot requirements:**
1) Writing user data when calling the /start command
2) Recording a task when calling the /addTask command
3) Issuing all user tasks when calling the /tasks command
4) Deleting a task by id when calling the /deleteTask {id} command

**Model parameters User**
- name
- telegram_id
- first_name
- last_name
- chat_id
- 
**Model parameters Task**
1) title
2) description
3) end_date

### Additional requirements
1) Tasks must be associated with a user in the database using the foreignKey key.
2) Getting tasks should be implemented using has Many in the gorm package

Optionally, you can connect a Sqlite or Mysql database

## useful links
- [Telegram API Documentation](https://core.telegram.org/bots/api)
- [BotFather](https://t.me/BotFather)
- [gorm documentation](https://gorm.io/docs/query.html)
