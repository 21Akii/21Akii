
<div align="center">

<sub>AKRAM CHERBANE · FREELANCE DEVELOPER</sub>

# Business software, built end to end.

Full-stack and AI engineer building web, mobile and back-office systems for real companies.

[**Portfolio**](https://github.com/21Akii/portfolio) · [**Selected work**](#selected-work) · [**How I build**](#how-i-build) · [**Contact**](#contact)

<br>

<img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/cops-dashboard.webp" alt="ConstraOps dashboard with open contracts, unpaid invoices, site progress with budget rings and a map of active sites" width="92%">

<sub>ConstraOps, company back office (demo data)</sub>

<br>

<img src="https://cdn.simpleicons.org/typescript/8b949e" alt="TypeScript" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/react/8b949e" alt="React" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/nextdotjs/8b949e" alt="Next.js" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/nodedotjs/8b949e" alt="Node.js" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/nestjs/8b949e" alt="NestJS" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/flutter/8b949e" alt="Flutter" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/dart/8b949e" alt="Dart" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/python/8b949e" alt="Python" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/tensorflow/8b949e" alt="TensorFlow" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/postgresql/8b949e" alt="PostgreSQL" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/prisma/8b949e" alt="Prisma" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/redis/8b949e" alt="Redis" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/docker/8b949e" alt="Docker" height="28">&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/tailwindcss/8b949e" alt="Tailwind CSS" height="28">

</div>

<br>

## Selected work

Construction and fuel-distribution platforms, a fitness app, and the AI projects from my degree.

---

### ConstraOps

**An ERP for Algerian construction companies**, from tender preparation to site tracking and equipment management.

Three products share one API: the company back office, a supplier marketplace and an offline-capable Flutter field app. Built as the label prototype for the national *Projet Innovant* application, co-founded with Fares Nadji.

<p align="center">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/cops-tenders.webp" alt="ConstraOps tender pipeline with nine tenders, win rate and status filters" width="32%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/cops-equipment-planning.webp" alt="ConstraOps monthly Gantt chart assigning machines to sites" width="32%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/cops-ocr-employee.webp" alt="ConstraOps new employee form after an ID card was read" width="32%">
</p>

- **Added value:** cuts the days of manual work behind a tender dossier. Data is entered once and reused from one tender to the next, documents are read by OCR instead of retyped, official documents such as the G50 are generated from the data, and management gets one view of sites, staff, machines and money.
- **Tender wizard:** a five-step flow takes a tender from the specification to the generated offer, and turns a won bid into a site.
- **OCR-assisted entry:** ID cards, CVs, CNAS cards and blank bills of quantities are read instead of retyped. *In this prototype the extraction runs on sample data; real OCR is on the roadmap.*
- **Equipment management:** fleet by type and status, monthly Gantt planning, availability against an 80% target, preventive and corrective maintenance, and a file per machine.
- **Field app:** a Flutter companion for the site foreman with tasks, attendance, incidents and requests, and an offline queue that syncs when the signal returns.
- **Algerian compliance:** official G50 tax forms filled in from the data, with VAT and TAP declarations. French interface, Arabic on official documents.
- **Roles and permissions:** 12 built-in roles and 46 permissions across three workspaces, API guards for roles, plan and licensed modules, and an audit log of who did what, when, from which IP, with before and after values.

`Flutter` `NestJS` `PostgreSQL` `Prisma` `Docker` `Traefik`

*Deployed on a VPS behind Traefik. The source is in a private repository.*

---

### TRG

**An ERP and CRM for an Algerian fuel-distribution company.**

Dispatchers plan deliveries, tank levels are reconciled, the equipment fleet and its expiring documents are tracked, the cash book and safety incidents are logged, and drivers report problems from a Flutter app. The interface comes in French, English and Arabic.

<p align="center">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/trg-dashboard.webp" alt="TRG dashboard with quick actions, trucks on the road, deliveries today, service rate, monthly revenue and a live map" width="32%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/trg-deliveries.webp" alt="TRG deliveries list with status tabs, product, truck, driver and quantity" width="32%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/trg-arabic.webp" alt="TRG dashboard in Arabic with a right-to-left layout and the menu on the right" width="32%">
</p>

- **Added value:** one system for the whole operation. The owner sees on one screen which trucks are rolling, which deliveries are at risk and which customers owe money, while fuel stock, fleet documents, cash and safety incidents live in the same place.
- **Driver app:** missions, maintenance alerts and a one-tap problem report that notifies the HSE manager.
- **Three languages:** French, English and Arabic, with a right-to-left layout in the web app and the driver app.
- **Equipment management:** tractor units and trailers with documents and expiry alerts, a maintenance plan and costs per vehicle, and workshop stock with reorder thresholds.
- **Roles and permissions:** seven roles share one permission matrix, written once in a shared package. The API enforces it and the web app reuses it to hide actions a user cannot take.

*Demo build running on seeded data. The source is in a private repository.*

---

### weGym

**A self-hosted gym, nutrition and recovery tracker** you install on your own server and use as an app on your phone. A personal project.

<p align="center">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/gym-plan.webp" alt="weGym weekly plan screen" width="22%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/gym-workout.webp" alt="weGym guided workout with set tracking and rest timer" width="22%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/gym-stats.webp" alt="weGym stats screen with heatmap, charts and personal records" width="22%">
</p>

Built on openGym by Duarte Santos (AGPL-3.0). My additions: nutrition and meal prep, recovery tracking, goal rings on the home screen, a shared recipe feed and a guided tour of the whole app.

Your data stays on your own server: no account on someone else's platform, no subscription, no ads. It installs on the phone like a normal app, works offline and syncs across devices.

---

### Attendify

**Access control that recognises faces in real time.** Bachelor's thesis, Numidia Institute of Technology, 2024-2025, built with Chakib Younsi.

<p align="center">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/attendify-rooms.webp" alt="Attendify rooms dashboard listing monitored rooms with an add room tile" width="46%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/attendify-add-person.webp" alt="Attendify form for registering a new person with role and access level" width="46%">
</p>

YOLOv8 finds the face, a convolutional network of our own identifies it, and everything runs on the local machine, so no raw biometric data leaves the device. Administrators register people, assign rooms and access levels, configure the camera stream and receive alerts from a desktop dashboard.

| **&lt; 2 s** | **87%** | **6** |
|:---:|:---:|:---:|
| per recognition cycle | validation accuracy, preliminary tests | layers in the custom convolutional backbone |

---

### More projects

**HealthMate** · *Team project of five, Numidia Institute of Technology*

<p align="center">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/healthmate-login.webp" alt="HealthMate sign-in screen with email and password fields on a teal gradient" width="22%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/healthmate-chat.webp" alt="HealthMate chat screen with a message field on a blue gradient" width="22%">
  <img src="https://raw.githubusercontent.com/21Akii/portfolio/main/public/projects/healthmate-conversations.webp" alt="HealthMate conversation drawer listing separate conversations" width="22%">
</p>

A symptom-based diagnosis chatbot. The Flutter app has sign-in and a chat with separate conversations. The model behind it is a bagged ensemble of random forests over TF-IDF features, which reached 84% accuracy on its test set. It was trained and evaluated separately; in the app's repository the chat is still an interface without the model connected. It supports a visit to a doctor and does not replace one.

**Production and distribution CRM** · *In progress, starting from the PostgreSQL infrastructure.*

**[w2l-virtual-classroom](https://github.com/21Akii/w2l-virtual-classroom)** · A 5G-powered virtual classroom platform for tutoring and attention tracking, written in Dart.

<br>

## How I build

Habits that show up in every project above.

| | |
|---|---|
| **Start from the data** | Schemas are designed first, in Prisma and PostgreSQL. In ConstraOps every business row belongs to an organisation, so one deployment can serve many companies without their data ever mixing. |
| **Give each user their own app** | ConstraOps serves the company back office, the supplier marketplace and the site worker's phone as three separate products on one API, instead of one interface with half the buttons hidden. |
| **Enforce access where the data lives** | Hiding a button is not security. Role, plan and module guards live in the API, and TRG writes one permission matrix that the API enforces and the web app reuses. |
| **Work without a signal** | Site workers are not always online. The ConstraOps field app keeps an offline queue and syncs it when the connection comes back. |
| **Write it down before building it** | Requirements specifications and data-model documents come first. ConstraOps and HealthMate both started from a written SRS. |
| **Ship it, and keep notes** | Docker Compose, a reverse proxy, backups and a deployment log. ConstraOps runs on a VPS, and the steps to rebuild it are written down. |

<br>

## About

**I design, build and deploy the whole system.**

Since October 2025 I have worked as a freelance full-stack and AI developer, building web and mobile applications and custom management software: ERP, CRM, HR, finance and stock. On the AI side that means RAG systems, model fine-tuning, computer vision and automation.

I work with Flutter, Python, Node.js, NestJS, PostgreSQL and Docker, from the first schema to production. I hold a Bachelor's degree in Computer Science, option Artificial Intelligence and Embedded Systems, from the Numidia Institute of Technology.

### IBM certifications, 2026

| Certification | Score |
|---|:---:|
| Python for Data Science & AI | **96** |
| AI Capstone Project with Deep Learning | **94** |
| Deep Learning with Keras & TensorFlow | **90** |
| Introduction to Deep Learning & Neural Networks | **88** |
| Developing AI Applications with Flask | **84** |
| Machine Learning with Python | **83** |

<br>

## Contact

**Have a system that needs building?** Tell me what your company runs on today and what is slowing it down.

[**GitHub · @21Akii**](https://github.com/21Akii) · [**Portfolio**](https://github.com/21Akii/portfolio)

<div align="center">
<sub>© 2026 Akram Cherbane</sub>
</div>
