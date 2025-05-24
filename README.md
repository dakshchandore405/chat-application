# Spring boot chat application
# Real-Time Chat Application

A real-time chat application built using **Spring Boot**, **WebSocket**, and **STOMP** protocol, providing instant messaging capabilities with a lightweight and responsive JSP-based frontend.

## 🚀 Features

- Real-time messaging using WebSocket
- STOMP protocol for message routing
- Simple, responsive user interface using JSP
- Publish-Subscribe messaging model
- Room-based chat functionality (optional)
- Scalable and lightweight Spring Boot backend

## 🛠️ Tech Stack

- **Backend:** Spring Boot, Spring WebSocket, STOMP
- **Frontend:** JSP, HTML, CSS
- **Build Tool:** Maven
- **Protocol:** WebSocket
- **Security:** Spring Security (optional)
- **Database:** MySQL (optional, for login and message persistence)

## 📂 Project Structure

src/
└── main/
├── java/
│ └── com.example.chat/ # Backend logic and config
├── resources/
│ ├── static/ # Static assets (CSS, JS)
│ ├── templates/ # JSP files
│ └── application.properties
└── webapp/
└── WEB-INF/
└── views/ # JSP Views

markdown
Copy
Edit

## 🧑‍💻 Getting Started

1. Clone the repository
2. Run the Spring Boot app (`ChatApplication.java`)
3. Visit `http://localhost:8080/` in your browser
4. Start chatting!

## 📄 License & Credits

The base structure of this project is inspired by [Ali Bouali](https://github.com/ali-bouali)’s work on WebSocket chat applications. Licensed under the MIT License.

