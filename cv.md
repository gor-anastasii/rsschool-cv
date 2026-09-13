# ANASTASIA GORODILINA

## Full-Stack Developer | JavaScript | TypeScript

### Contact Information

- **Email:** nastenas714@gmail.com
- **Telegram:** [@gor_anastasii](https://t.me/gor_anastasii)

---

## About Me

Frontend Developer with commercial experience building web applications using React and Vue.js.

I have experience developing frontend functionality, integrating REST APIs, creating responsive and cross-browser interfaces, and redesigning existing applications. I independently designed and built three company landing pages from scratch and completely redesigned the UI of two internal web applications.

I am comfortable working with React, TypeScript, JavaScript, Redux, Axios, Git, Docker, and Figma. I also have backend development experience with Node.js, Express, PostgreSQL, and MongoDB.

My goal is to continue developing as a Frontend Developer, improve my technical skills, work on complex web applications, and gain experience with modern frontend development practices and technologies.

---

## Skills

### Frontend

- React
- Vue.js
- Redux
- JavaScript
- TypeScript
- HTML5
- CSS3

### API & Data

- REST API
- Axios
- WebSocket

### Backend

- Node.js
- Express
- PostgreSQL
- MongoDB
- Sequelize
- JWT Authentication

### Tools

- Git
- Docker
- Figma

### UI/UX

- UI design from scratch
- Product redesign
- Responsive interfaces
- Cross-browser development

---

## Code Examples

### React + TypeScript

```tsx
import { useEffect, useState } from "react";

interface User {
  id: number;
  name: string;
  email: string;
}

const UserList = () => {
  const [users, setUsers] = useState<User[]>([]);
  const [loading, setLoading] = useState(true);

  useEffect(() => {
    fetch("/api/users")
      .then((response) => response.json())
      .then((data: User[]) => setUsers(data))
      .finally(() => setLoading(false));
  }, []);

  if (loading) {
    return <p>Loading...</p>;
  }

  return (
    <ul>
      {users.map((user) => (
        <li key={user.id}>
          <strong>{user.name}</strong>
          <span> — {user.email}</span>
        </li>
      ))}
    </ul>
  );
};

export default UserList;
```

## Work Experience

### Frontend Developer — ООО «MeraSoft»

**Apr 2025 – Present**

Web applications for a residential care facility and rehabilitation center, as well as company landing pages.

#### Responsibilities and Achievements

- Developed new frontend functionality in React for a rehabilitation center application and integrated it with backend REST APIs.
- Developed new frontend functionality in Vue.js for a personnel and patient management application and integrated it with backend REST APIs.
- Completely redesigned the UI of two internal web applications for the care facility and rehabilitation center.
- Independently designed and built three company landing pages from scratch using HTML5, CSS3, and JavaScript.
- Created responsive and cross-browser interfaces for desktop and mobile devices.
- Worked with Docker for containerization and local execution of frontend and backend applications.
- Used Git for development and implementation of project changes.

**Tech Stack:** React, Vue.js, TypeScript, JavaScript, HTML5, CSS3, REST API, Figma, Git, Docker

### Additional Responsibility

**~3 months — during the employee search period**

- Assigned and distributed development tasks according to project requirements.
- Monitored task deadlines and checked completed work.
- Tested the application after changes.
- Reviewed results delivered by other developers.

---

## Projects

### Graduation Project — AI-powered Educational Web Platform

Web platform for creating and publishing educational content with AI-assisted content generation.

#### Responsibilities and Achievements

- Integrated Grok AI for AI-assisted content generation.
- Integrated Cloudinary for file storage.
- Built the frontend using React and Redux.
- Used Axios for API communication.
- Implemented WebSocket communication for real-time interaction.
- Developed backend functionality using Node.js and Express.
- Implemented JWT authentication.
- Used PostgreSQL for data storage with Sequelize.
- Used Docker for development and application execution.

**Tech Stack:** React, Redux, Axios, WebSocket, Node.js, Express, JWT, Sequelize, PostgreSQL, Docker

---

## Education

### Bachelor of Science in Software Engineering

**Belarusian State Technological University**  
Major: Information Technology Software

**Sep 2022 – Jun 2026**

---

### ITGen.io — Software Development Training

**Sep 2018 – Jun 2022**

Software development training with a focus on programming and web development.

---

## English

**English — A2+/B1**

I can read and understand technical documentation, communicate about development tasks, and work with English-language programming resources.

**Russian — Native**
