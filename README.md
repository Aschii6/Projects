# Projects
## Bachelor's Thesis
***Spoiler detection, a solution refined for specific titles***

*ABSTRACT:* <br>
"Spoiler content in online discussions, reviews, or anywhere else on the internet
can have a negative impact on the experience of some people..."
"This thesis aims to address the challenge of automatically detecting spoilers in text content, with a focus on online reviews, by exploring varying machine learning methods, as well as to offer a resolution in the form of an application for everyday use."

"The research begins with a comparative study of ... Support Vector Machines,
Convolutional Neural Networks, Recurrent Neural Networks, transformer-based
models, and Graph Neural Networks. A series of experiments are conducted to
compare the approaches in these papers... Further experiments attempt to fine-tune models on distinct movie titles,
offering a solution meant to excel at detecting spoilers related to their respective title; experiments which, as far as the literature reviewed to date suggests, have yet
to be attempted."

"To offer some practicality... a Google
Chrome browser extension was developed to hide textual content from the body of
webpages, using... the Chrome API. With the
content of webpages being exposed by the said API, the task of predicting spoilers
is managed by a specialised spoiler prediction API server"

**Spoiler Fighter, the Chrome extension:** https://github.com/Aschii6/Spoiler-Fighter
> TypeScript, React, MaterialUI, TailwindCSS, Chrome API

**Spoiler Prediction API Server**
> FastAPI

**Spoiler Detection**
> PyTorch, SVM, CNN, RNN, BERT

## Software
### **Jobbble**
Jobbble - the Job Application Tracker. Basically what I wished I had used when I started the intern/job hunt.

You can keep track of companies, application processes and the steps involved in each process.

### Backend
**Jobbble Spring:** https://github.com/Aschii6/jobbble-spring
> Java, Spring Boot, Spring JPA & Hibernate with Postgres, Spring Security, JWT, Spring Validation, MapStruct
> Entities, DTOs, Repositories, Services, Controllers, Custom Exceptions and Global Controller Exception Handling

Requests that want to access protected routes need to include a JWT token in the Authorization header. The username is extracted from the token, Spring Security checks that the user exists in the DB and that the token is not expired and sets the context of the authentication assigning user roles and other custom data.

Users can only access and alter data that they created.

### Frontend
**Jobbble React:** https://github.com/Aschii6/jobbble-react
> Vite, React, TypeScript, TanStack Router, TanStack Query, Zustand, ShadCN, Tailwind, React Hook Form, Zod

<br/>

**Farming Assistant:** https://github.com/Cozma-Alex/Frontend-Farming-Assistant
> Flutter, Dart

University Project where a team of 10 students worked for a full semester, for the course Collective Project. Alongside 2 other colleagues, I worked on Front End, where I contributed to all Task related pages, a weather widget that uses and API from OpenWeather and more...

<br/>

**Outdoor Sustenabil**
> Flutter, Dart

My internship project at CS InnoHub (an organization that is part of UBB), where I worked alongside 4 other students and a mentor to develop an application meant to keep track and alert users of the presence of bears nearby, a project made for The Faculty of Environmental Science and Engineering.

<br/>

**Movie Manager:** https://github.com/Aschii6/UBB_RO/tree/main/Sem5/PDM/Ionic/Ionic3

Add and review movies
> Ionic React, Auth (Token, Private Route), Context, Routing

<br/>

**Compiler:** https://github.com/Aschii6/Compiler
> Lexical and syntax analysis in Java for a subset language of C++ and using Flex + Bison to generate Assembly Code

This project is related to an university course, but with new improvements and better design choices.

<br/>

**Triathlon Management in Java:**
> Java, JavaFX, Sqlite, networking using RPC Protocol and Protobuf, ORM, REST services, React

**Triathlon Management in C#:**
> C#, Windows Forms, networking using Object Protocol and Protobuf

**Toy Social Network:** https://github.com/Aschii6/Toy-Social-Network
> Java, JavaFX, PostgreSQL

**Employee Management:** https://github.com/Aschii6/Employee-Management
> Models, Diagrams

## Machine Learning
**Predictive Mental Health Monitoring System**
> RNN, LSTM

Predicting user mental state based on physiological data from wrist devices.

**Handwritten Digit Recongnition**
> CNN, MNIST Dataset

## Some games
### Made using Godot (a game engine)
**Dungeon Crawler:** https://github.com/Aschii6/dungeon-crawler

**Tower Defense:** https://github.com/Aschii6/TowerDefenseGodot

**Block Drop:** https://github.com/Aschii6/Block-Drop

**Sokoban:** https://github.com/Aschii6/Sokoban

### Made using SFML (a low level C++ library)

**Platformer Game:** https://github.com/Aschii6/Platformer
> C++, SFML (Simple and Fast Multimedia Library), ECS (Entities Components Systems), Scene Management

I made heavy use of the Entity Component Template to abstract some features away from the Entities, e.g. Rendering, Physics Processes.

**Vampire Survivors Copy:** https://github.com/Aschii6/Vampire-Survivors-Copy
> C++, SFML, Animations, Assest Management

## And
Other projects: https://github.com/Aschii6/Some-Small-Projects
Consisting of: C++ projects with QT for GUI, Java projects with JavaFX and other small games
