# Kizuna-Social-Network

Kizuna-Social-Network is a social networking platform developed with a modern focus on privacy and real-time communication. The project uses **C# .NET 8** for the backend and **React** for the frontend, all implemented within a **Docker** environment.

## Main Features

- **Real-time chat functionality:** Implemented with **SignalR** for efficient communication.
- **Encrypted data persistence:** Chat messages are securely stored in the database using advanced encryption techniques.
- **Hidden chat mode:** Offers **end-to-end** encryption for enhanced privacy.
- **Simplified deployment:** The entire stack is packaged into Docker containers for easy implementation and maintenance.

---

## Technologies Used

- **Backend:** C# .NET 8
- **Frontend:** React (With the help of [https://v0.dev](https://v0.dev) and my head)
- **Real-time Communication:** SignalR
- **Persistence:** Relational database with encryption support
- **Containerization:** Docker

---

## Prerequisites

Make sure you have the following programs installed, which are essential for the project to run correctly:

- [Docker](https://www.docker.com/): To containerize and run the backend, frontend, and database services in isolated environments.
- [Node.js](https://nodejs.org/): Required to manage dependencies and execute scripts during frontend development.
- [.NET SDK 8](https://dotnet.microsoft.com/): Necessary for compiling and running the backend built in .NET 8.

---

## Installation Instructions

**Not yet is still cooking, when there is v1 I'll put it 💤😴**



---

## Project Architecture

- **Backend:**

  - Onion Architecture
  - REST API developed in .NET 8
  - SignalR for real-time communication
  - Data encryption middleware
  - AutoMapper for data transformation
  - Implementation of CQRS (Command Query Responsibility Segregation)

- **Frontend:**

  - User interface developed in React
  - Communication with the API via HTTP/HTTPS and WebSockets

- **Database:**

  - Messages and other sensitive data are stored in a relational database with integrated encryption.

- **Docker:**

  - Each component (frontend, backend) is packaged as an independent container.

---

## Security

1. **Data encryption:**

   - All messages are stored in the database using AES-256 encryption algorithms.

2. **Hidden chat mode:**

   - This mode ensures privacy through end-to-end encryption. Only the sender and recipient can read the messages. (Let's see how I implement it, I'm still researching and learning it but it's going 👁️)

3. **Authentication:**

   - JWT (JSON Web Tokens) is used to securely authenticate users.

---

## Contribution

Contributions are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository
2. Create a branch for your feature: `git checkout -b new-feature`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push your changes: `git push origin new-feature`
5. Create a Pull Request on the original repository

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## Contact

For questions or comments, please contact [jefferson@abreuhd.com](mailto:jefferson@abreuhd.com).

