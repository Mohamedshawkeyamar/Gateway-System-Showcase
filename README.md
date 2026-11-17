# Gateway System

**A full-stack training and community management platform.**

![Gateway System project showcase](assets/cover.png)

![React](https://img.shields.io/badge/React-18-149eca?logo=react&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-11-ff2d20?logo=laravel&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-State_Management-764abc?logo=redux&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-UI_Components-007fff?logo=mui&logoColor=white)
![Source Private](https://img.shields.io/badge/Source_Code-Private-334155?logo=github&logoColor=white)

## Overview

**Gateway System** is an administrative web application designed to coordinate training and community operations. The available code includes authentication, a management dashboard, trainee records, training batches and classes, attendance, branch administration, user permissions, and status-based lists.

This **public repository is a visual project showcase**, not the application source code. The frontend and backend implementations are intentionally kept private.

## Main features

| Module | What it covers |
| --- | --- |
| **Dashboard** | Operational summaries, announcements, and shortcuts to management screens. |
| **Trainees** | Trainee record views and search/filter interfaces. |
| **Batches & Classes** | Training batch and class administration. |
| **Attendance** | Attendance-related pages, including trainer attendance. |
| **Status Workflows** | Wait list, pending tests, hold, refund, and blacklist management. |
| **People & Branches** | User administration, pending users, branch management, and role permissions. |
| **Account Access** | Login, registration, forgotten password, and password reset. |
| **Communication** | Announcements, inbox, and notifications interfaces. |

> **Screenshot note:** Images below were captured from the original React interface in an **isolated local preview**. A mock session was used for protected screens; no live server data or real user records were loaded. Empty tables, loading indicators, and zero counts reflect the preview environment, not operational results.

## Interface gallery

### Dashboard

![Dashboard overview](screenshots/dashboard.png)

[View the full dashboard image](screenshots/dashboard-full.png)

### Batches & Trainees

| Batches | Trainees |
| :---: | :---: |
| ![Batches screen](screenshots/batches.png) | ![Trainee management screen](screenshots/trainees.png) |

### Workflows & Permissions

| Wait List | Roles |
| :---: | :---: |
| ![Wait List screen](screenshots/waitlist.png) | ![Roles screen](screenshots/roles.png) |

### Authentication

| Login | Registration |
| :---: | :---: |
| ![Login screen](screenshots/login.png) | ![Registration screen](screenshots/signup.png) |

| Password recovery | Password reset |
| :---: | :---: |
| ![Forgot password screen](screenshots/forgot-password.png) | ![Reset password screen](screenshots/reset-password.png) |

## Technology stack

**Frontend:** React 18, Vite 5, JavaScript, Redux Toolkit, React Router, Material UI, Axios.

**Backend:** PHP 8.2+, Laravel 11 API, Laravel Sanctum, Laravel Reverb / WebSocket integration.

**Application structure:** React UI → Laravel API → application data storage, with authentication and permission-aware interface controls. The backend repository also includes database migrations and SQLite development database support.

## Repository access

- **Project source:** Private / not included here.
- **Live application:** No public demo link provided in this showcase.
- **Screenshots:** UI previews only, with no customer or production records.

This repository is intended to demonstrate application scope and user interface design. It does **not** provide a deployable build, software license for the private code, API credentials, or a copy of the project database.

## Contact

Maintained as a portfolio showcase by [@Mohamedshawkeyamar](https://github.com/Mohamedshawkeyamar). For access or project inquiries, contact the repository owner.
