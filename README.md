# Real-Chat-Board
Smart Chat-Board 🚀
A real-time chat application enabling seamless, low-latency conversations with a clean, responsive UI.

Tech Stack: Java 11, Spring Boot, Spring WebSocket, HTML, CSS, JavaScript

Overview
Smart Chat-Board is a real-time chat application built with Spring Boot and Spring WebSocket, allowing users to exchange messages instantly with a bidirectional communication channel. The frontend is designed with HTML, CSS, and JavaScript, ensuring a responsive layout across devices for an intuitive user experience.

Key Features:
✅ Real-Time Messaging: Uses Spring WebSocket to deliver low-latency, bidirectional message updates without manual page refresh.
✅ Clean, Responsive UI: Custom-designed chat interface with smooth animations, clear message bubbles, and user-friendly layouts for better readability and engagement.
✅ Scalable Backend: Spring Boot architecture with WebSocket endpoints for handling multiple concurrent chat sessions efficiently.
✅ Custom Styling: Integrated custom backgrounds, color themes, and layouts to enhance user engagement.
✅ Seamless User Interactions: Supports real-time user join/leave notifications and instant message delivery for a lively chat environment.

How It Works
WebSocket Integration: Establishes persistent connections for message exchange.

Message Controller: Handles incoming messages, broadcasts to connected clients instantly.

Frontend Event Handling: JavaScript captures user input, sends messages via WebSocket, and dynamically updates the chat window in real time.
