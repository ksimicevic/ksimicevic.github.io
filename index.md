---
title: "Korina Šimičević - portfolio"
format:
  html:
    toc: true
    toc-location: left
---

<img align="left" width="20" height="20" src="./icons/email.png" alt="E-mail"> &nbsp; <a href = "mailto: korina.simicevic99@gmail.com">korina.simicevic99@gmail.com</a>

<img align="left" width="20" height="20" src="./icons/linkedin.png" alt="LinkedIn"> &nbsp;  [korinasimicevic](https://www.linkedin.com/in/korinasimicevic/)

<img align="left" width="20" height="20" src="./icons/github.png" alt="GitHub"> &nbsp;  [ksimicevic](https://github.com/ksimicevic)

## About Me

I’m a passionate and detail-oriented software engineer with over 3 years of professional experience, primarily focused on modern **C++ (C++17/20)** and writing **high-performance C++ backends and networked systems**.

I care deeply about code quality, maintainability, and following best testing practices to ensure reliability and robustness. <br> 
Whether writing production systems or contributing to open-source libraries, I strive for clean, well-documented, and thoroughly tested code. <br>

I also enjoy mentoring other developers, conducting deep code reviews, and fostering a culture of continuous learning and improvement.

While **C++** is my core language, I’m also experienced in **Python** and **Java**, and have a foundation in web development. I am always eager to learn new tools and technologies.

---

## Software Engineer @ Mireo (Jul 2021 - Present)

### Data Ingestion Connector for the SpaceTime Database

As part of my internship in Summer 2021, I developed a data ingestion connector for integrating new data into the SpaceTime database.

The connector was implemented in **C++20** (using **Boost** and **Boost.Asio**), **Java**, and **Python** to support interoperability across different systems and use cases.

---

### Asynchronous Client-Server Backend System for Querying the SpaceTime Database

I implemented an asynchronous client-server system for handling user queries and delivering responses from the SpaceTime database.

- **Client**: Developed in **C++20** using **Boost.Asio** for **asynchronous programming** and **TCP communication**. Features include:
   - Automatic reconnect and retry: Upon connection loss, the client automatically reconnects and resends any pending queries.
   - Multi-flight support: Allows multiple queries to be sent concurrently, with responses handled asynchronously.

- **Server**: Also implemented in **C++20** with **Boost.Asio**, capable of handling multiple simultaneous client connections using non-blocking I/O.

---

### Boost.MQTT5
GitHub link to the [repository](https://github.com/boostorg/mqtt5).

An **open-source**, **industrial-grade MQTT 5.0** client built in **C++17** using **Boost.Asio**. <br>
The Client is designed for publishing or receiving messages from an MQTT 5.0 compatible Broker.

Released as part of Boost 1.88 — **the largest collection of open-source and peer-reviewed C++ libraries.**

My responsibilities include:

- Coordinated and tracked development tasks across contributors
- Core development
- Implemented testing infrastructure to mock broker messages
- Writing unit and integration tests
- Wrote and maintained technical documentation
- Set up and maintained CI pipelines via GitHub Actions
- Managed GitHub issues and engaged with the open-source community

---

### In-House Raft Consensus Algorithm Implementation

Currently leading the development of an in-house **C++20** implementation of a **consensus algorithm for distributed systems** using Boost.Asio. 

My responsibilities include:

- Architecture design
- Writing design documents
- Core development
- Creation of a testing infrastructure using Discrete-event simulation (DES) technique
- Writing unit and integration tests
- Mentoring junior developers and conducting in-depth code reviews to ensure best practices and maintain code quality

## Personal Pet Projects

### Discord Message Analyzer (Jan 2022 - Dec 2022)
GitHub link to the [repository](https://github.com/ksimicevic/discord-message-analyzer).

Discord message analyzer is a Jupyter notebook with statistical and data analysis performed on extracted Discord messages. <br>
The analysis includes:

- Total message count, message count per author
- Day with the most messages sent
- Mean/median/standard deviation of messages per day
- The longest message streak (period where at least one message was sent each day)
- Determining the initiator (the person who sends the first message of the day)

The project also involved creating data visualizations, including:

- Plotting the number of messages per day on the time scale
- Showcasing the distribution of messages per day and the distribution of messages per day for each author
- Plotting the distribution of messages during the day to answer the question during which hour of the day the most of the conversation occurs

**Technologies used:** Python, Jupyter, matplotlib, pandas, seaborn

---

### Study Hours (Sep 2020 - Apr 2024)
GitHub link to the [repository](https://github.com/ksimicevic/study-hours).

During the 2020/2021 academic year, I tracked the number of hours spent on various university-related activities across different subjects, including attending lectures, studying, completing homework, and more.

After collecting the data, I developed a web server to display interactive data visualizations that provide insights into my study habits over time.

**Technologies used:**  Python, Plotly, Dash

---
