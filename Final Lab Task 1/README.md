# 📑𝐅𝐢𝐧𝐚𝐥 𝐓𝐚𝐬𝐤 1: 𝐄𝐯𝐞𝐧𝐭𝐬 𝐌𝐚𝐧𝐚𝐠𝐞𝐦𝐞𝐧𝐭 𝐃𝐁

## ***Create an events table with fields***

- event_id (int, auto-increment, primary key)

- event_name (VARCHAR, up to 255 characters, not null)


![image](https://github.com/user-attachments/assets/e336df5d-2410-4aaa-8d69-7e6aaa8d690d)

## ***Create an attendees table with fields***

- attendee_id (int, auto-increment, primary key)

- attendee_name (VARCHAR, up to 255 characters, not null)


![image](https://github.com/user-attachments/assets/ba7b67ba-c6db-46b7-897c-60b92a29c8f8)



## ***Create an event attendees table with fields***

- event_id (int, foreign key to events.event_id)

- attendee_id (int, foreign key to attendees.attendee_id)

- Composite primary key on (event_id, attendee_id)
  

![image](https://github.com/user-attachments/assets/2fad3ad2-08a4-4f64-a58c-21617ec5ddc2)


## ***Create an event sponsors table with fields***

- sponsor_id (int, auto-increment, primary key)

- event_id (int, foreign key to events.event_id)

- sponsor_name (VARCHAR, up to 255 characters, not null)


  ![image](https://github.com/user-attachments/assets/00eadb0f-0b6d-4725-96e5-0a7d979da3bc)

## ***ER Diagram***

  ![image](https://github.com/user-attachments/assets/506c00e1-8469-420e-a7c4-b222ed70950c)


## ***SQL Copy of Database and Table Structures***

- [**SQL Copy of my Database**](https://github.com/AeroB2/EDM-PROJECTS-AeroB2/blob/main/Final%20Lab%20Task%201/SQL%20COPY)


