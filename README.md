# Spring Boot WebSocket Chat Application

A real-time chat application built with Spring Boot and WebSocket that enables multiple users to chat in a common room.

## Features

- Real-time messaging using WebSocket
- User join/leave notifications
- Unique avatar colors for each user
- Clean and responsive UI
- Connection status handling
- Message broadcasting to all connected users

## Technologies

- Java 17
- Spring Boot 3.4.5
- WebSocket (STOMP)
- SockJS (WebSocket fallback)
- Maven
- Lombok
- HTML/CSS/JavaScript
  
## How It Works
1. The application uses Spring Boot's WebSocket support with the STOMP protocol
2. Users can enter their username to join the chat room
3. Messages are broadcast to all connected users
4. The server notifies when users join or leave the chat
5. Each user gets a unique avatar color based on their username
   
## WebSocket Endpoints
- /ws - WebSocket connection endpoint
- /app/chat.sendMessage - Send message endpoint
- /app/chat.addUser - User join endpoint
- /topic/public - Message broadcast topic

## Screenshots

### Real-time Chat Demonstration

The following screenshots demonstrate a live chat session with three users (Youssef Tarek, Ahmed Shokr, and Ahmed Khaled) interacting in real-time:

#### Active Chat Session
![Chat Session](https://github.com/user-attachments/assets/d26f1171-1336-4be6-bc4e-e05bbf2c5f35)
*Screenshot shows three users actively participating in the chat. Each user has a unique avatar with their initial letter (Y, A) in a blue circle. The chat displays join notifications and messages exchanged between users, demonstrating the real-time messaging capability.*

Key features visible:
- User join notifications ("Youssef Tarek joined!", "Ahmed Shokr joined!", "Ahmed Khaled joined!")
- Real-time messages with user avatars
- Clean message layout with sender names and content
- Message input field with Send button
- Responsive chat interface

#### User Departure Notification
![User Left Notification](https://github.com/user-attachments/assets/c5d95a85-dfa7-4abb-9272-4daaf998b285)
*Screenshot demonstrates the user departure notification feature, showing the "Youssef Tarek left!" message, indicating when users disconnect from the chat.*

Features demonstrated:
- Automatic user departure detection
- System notifications for user disconnection
- Persistent chat history
- Maintained message formatting

The screenshots effectively showcase:
1. Real-time message delivery
2. User join/leave notifications
3. Unique user avatars
4. Clean and intuitive UI
5. Message persistence
6. System notifications
7. Multiple user interaction

These images were captured from a local development environment (localhost:8080) and demonstrate the application running successfully with multiple active users.
