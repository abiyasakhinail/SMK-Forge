# SMK-Forge (Project IT-CBT)
SMK-Forge is a web-based application built to help SMK students document and showcase their technical projects. The platform allows students to upload their work, manage their digital portfolios, and share their progress with teachers and potential employers. It features a secure authentication system and full CRUD (Create, Read, Update, Delete) capabilities.

## The Team

|             Name                |                Role                       |                       Responsibilities                              |
| :-----------------------------: | :---------------------------------------: | :-----------------------------------------------------------------: |
| **Aloysius Gonzaga D.L**        | **Lead Developer**                        | Full-stack development, database architecture, and system logic.    |
| **Bianca Nazihah Putri**        | **UI/UX Designer & QA Tester**            | Visual design, user experience, and Quality Assurance (QA) testing. |
| **Abiya Sakhi Nail**            | **System Analyst & Technical Writer**     | Flowchart logic design and technical documentation.                 |
| **Dhafa Nathan Fahlevi**        | **Frontend Developer**                    | UI implementation using Bootstrap and Laravel Blade templates.      |
| **Keyzahara Princess Giroth**   | **Creative Lead & Branding**              | Visual identity (Logo design), presentation architecture (Canva)    |

## Tech Stack
Core Frameworks

    Framework: Laravel 10 (PHP 8.2.12)

    Frontend: Bootstrap 5 & Blade Templating Engine

    Database: MySQL

Tools & Software

    Version Control: Git & GitHub

    Design: Figma
            
    Presentation & Branding: Canva

    Planning: Microsoft Excel (Logic Mapping)

    Environment: XAMPP (Local Server)

    Editor: Visual Studio Code

Key Features

    Secure Auth: Login and Registration system for students.

    Student Dashboard: A private area for students to manage their uploaded projects.

    Project Management: Full CRUD functionality (Add, View, Edit, and Delete projects).

    Authorization: Security logic that ensures only the owner can modify their specific data.

    Public Gallery: A home page for visitors to explore student creations.

## How to Run Locally
1. `git clone https://github.com/aldogonzaga/project-it-cbt.git`
2. `composer install`
3. `cp .env.example .env`
4. `php artisan key:generate`
5. `php artisan migrate`
6. `php artisan serve`
