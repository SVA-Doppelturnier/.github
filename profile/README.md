# SVA Arnum Doppelturnier

The official web application for the **SVA Arnum Doppelturnier**, an annual doubles tennis tournament organized by **SV Arnum**.

## About the Tournament

The Arnumer Doppelturnier was established as a club tournament combining competitive doubles tennis with social activities and community life. Over the years, it has become a recurring event for members of the tennis division.

The tournament traditionally features **Men's Doubles, Women's Doubles and Mixed Doubles**, complemented by social activities such as the Players' Night, barbecue and club events.

In 2025, the tournament celebrated its **fifth edition**, continuing the established format while further expanding the digital organization of the event.

## 📚 Project History

The tournament platform has evolved through several iterations over the years. This repository reflects the current generation of the project, while the GitHub organization also contains the previous versions of the application.

The repository history currently includes:

- **V1** – the original backend and frontend, now deprecated
- **V2** – the first major redesign of the platform
- **V3** – the current backend and frontend generation
- **Mail templates** – email templates used by the V3 backend
- **Filestorage** – the dedicated file storage service used by the current infrastructure

The older repositories are kept primarily for historical and reference purposes. The **current application repositories and their source code are private** and are therefore not publicly accessible. Only older versions of the application are publicly available.

## 🎯 Purpose of the Application

The application is designed to centralize and simplify the organizational work required to run the tournament.

Its main responsibilities include:

- participant registration and account management
- participant and contact data management
- creation and management of doubles teams
- competition registration
- tournament-related communication and notifications
- organization of the Players' Night and buffet
- planning and coordination of volunteer services
- management and publication of tournament information

The goal is to provide participants with a straightforward interface while giving the tournament organization a central system for managing the event and its participants.

## 🛠️ Technology

The project consists of a web frontend and a central backend API.

### Backend

- **Spring Boot**
- **Java / Kotlin**
- **PostgreSQL**
- REST API
- Authentifizierung und Autorisierung
- Persistente Verwaltung von Teilnehmern, Teams und Turnierdaten

### Frontend

- **React**
- **TypeScript**
- **Vite**
- **Tailwind CSS**
- **shadcn/ui**

### Infrastruktur

The application is containerized and designed to run on modern container infrastructure.

Depending on the deployment environment, the infrastructure may include:

- Docker
- PostgreSQL
- Redis
- Reverse Proxy
- persistenter File Storage

---

## 🔐 Privacy and Security

As the application processes personal data of tournament participants, secure handling of this data is an important part of the application design.

Non-public information is accessible only to authorized users. Authentication and authorization are handled by the backend, while sensitive data is not unnecessarily exposed through the frontend or publicly accessible endpoints.

---  

## 🚀 Development

The frontend and backend can be developed and run independently.

A local development environment requires, among other things:

- Java / Kotlin
- Node.js
- PostgreSQL
- Docker

Required environment variables and further setup instructions are documented in the respective project directories.

## About the Organization

The application is intended to reduce the administrative effort involved in organizing the tournament while providing participants with a central platform for the entire event. It brings together participant management, competition registration, communication and the organization of the supporting activities required throughout the tournament weekend.
