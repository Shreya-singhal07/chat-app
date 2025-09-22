# MERN stack Chat Application - Chat App

Chit-Chat App is a real-time messaging application built using the MERN stack (MongoDB, Express, React, Node.js) and Material-UI (MUI), leveraging Socket.IO for real-time messaging. It supports both individual and group chat functionalities with full user authentication and profile management.

## Features

- Real-time messaging with Socket.IO
- Individual and group chat functionality with admin access functionalities.
- User authentication and authorization using JWT
- Responsive design using Material-UI
- User profile management
- Real-time Typing indicators to show when a user is typing.

## Technologies Used

- **Frontend:** React, Material-UI (MUI)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-time Communication:** Socket.IO
- **Authentication:** JWT (JSON Web Tokens)

## Challenges Faced:

- Scaling Issues: Handling multiple concurrent users without losing performance, especially in larger groups.
- JWT Expiry & Token Refreshing: Dealing with token expiry and ensuring a smooth experience for users when tokens expired, including implementing a refresh token mechanism.

## Solution :

SCALING : 
- Implemented Socket.IO rooms to manage connections and group-specific messaging more effectively.
- Used load balancing on the backend to handle traffic spikes.

JWT AUTH:
- Added JWT refresh tokens and automatic session renewal to ensure that users stayed authenticated without interruption.

<img width="1430" alt="Screenshot 2025-04-18 at 4 07 20 PM" src="https://github.com/user-attachments/assets/17b6bb12-5cf8-4dd6-a264-b3745120e432" />
<img width="1430" alt="Screenshot 2025-04-18 at 4 31 09 PM" src="https://github.com/user-attachments/assets/d882c412-bcc3-4046-9ea4-51f13a571afd" />

<img width="430" alt="Screenshot 2025-04-18 at 4 31 24 PM" src="https://github.com/user-attachments/assets/ef7faaf3-ac9a-48c6-85ce-2678a3f1a0b6" /> <img width="430" alt="Screenshot 2025-04-18 at 4 31 36 PM" src="https://github.com/user-attachments/assets/01c7f89b-fd43-4229-872b-562c5da6e9ee" />

<img width="1440" alt="Screenshot 2025-04-18 at 4 32 00 PM" src="https://github.com/user-attachments/assets/b4283c77-9196-4cdd-811a-dd2394579ecf" />

<img width="454" alt="Screenshot 2025-04-18 at 4 31 44 PM" src="https://github.com/user-attachments/assets/5b9ee814-4549-49c3-911e-1e79593c1ebe" />



