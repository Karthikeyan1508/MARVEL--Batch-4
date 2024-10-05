# Task 1 - OSI

The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and describe the functions of a networking or telecommunication system. It was developed by the International Organization for Standardization (ISO) to standardize the protocols used in various layers of network communication. The model is divided into seven layers, each responsible for specific functions in the process of data transmission between devices across a network.

![image](https://github.com/user-attachments/assets/43485385-7795-4663-85b4-402787d0a829)

***

# Task 2 - Serverless

Serverless refers to a cloud computing model where developers build and run applications without managing the underlying infrastructure, such as servers, storage, or networking. In a serverless architecture, cloud providers (like AWS, Google Cloud, Azure) automatically handle the server management tasks, including provisioning, scaling, and maintenance.

![image](https://github.com/user-attachments/assets/84333aaf-0efe-430a-bdf9-7e44e0aa4ff0)

***

# Task 3 - Sockets!

WebSockets are a communication protocol that provides full-duplex communication channels over a single TCP connection. Unlike traditional HTTP, which is request-response based, WebSockets allow for bidirectional, real-time communication between a client and server. Once a WebSocket connection is established, data can flow freely in both directions, enabling interactive and dynamic web applications, such as chat applications, online games, and live updates.
<br /><br />
Key features of WebSockets include:<br /><br />
- **Persistent Connection**: The connection remains open, allowing for ongoing data transfer without needing to re-establish the connection.
- **Low Latency**: Data can be sent and received with minimal delay, making it ideal for real-time applications.
- **Full-Duplex Communication**: Both client and server can send messages independently, enabling more interactive and responsive applications.
<br /><br />
> **Chat App**:
A Chat application developed using Socket.io for real-time communication and SQLite for data storage. The application allows users to join chat rooms, send and receive messages, and view message history, all in real-time.
<br>
![image](https://github.com/user-attachments/assets/d6192d47-bc33-46ea-ba5d-092d03772f52)

***

# Task 4 - Make a Web app

I completed the task of creating a resource library website using Express, enabling users to browse available resource articles, books, and other materials. The website features functionalities for viewing detailed information about each resource and includes a search option to help users find specific content. The project also involved setting up a system for managing the resources, where administrators can add, edit, and delete entries as needed. This functionality ensures that the library's content remains current and comprehensive, providing a valuable tool for users to access and explore a wide range of materials.
<br /><br />

To build this project, I extensively utilized MDN documentation, which provided crucial insights and guidance on using Express and related web development technologies. The documentation was instrumental in understanding and implementing best practices for building a robust and efficient web application. The project not only helped in honing my technical skills in using Node.js, Express, and MongoDB but also provided a deeper understanding of web development concepts such as routing, middleware, and data management. This experience has been enriching, contributing to my proficiency in developing dynamic and user-friendly web applications.
<br /><br />
🔗 : [GitHub Repo](https://github.com/Karthikeyan1508/express-locallibrary)
<br /><br />
![image](https://github.com/user-attachments/assets/88177d5c-a5b9-485c-a981-6689a7388097)
![image](https://github.com/user-attachments/assets/657effac-4c10-4668-aa88-dd6cc9bb49fc)

***

# Task 5 - Docker

> Docker is a platform that allows developers to automate the deployment of applications inside lightweight, portable containers. These containers package an application and its dependencies, ensuring consistency across various environments.

For this task, I created a to-do app using Node.js and an SQLite database, which served as the application for demonstrating automated Docker container creation upon pushing to the production branch. A Dockerfile was crafted to set up the necessary environment and dependencies for the app. GitHub Actions was employed to establish a Continuous Integration (CI) pipeline, triggering the build and deployment of a Docker container each time changes were pushed to the production branch. The CI workflow ensured seamless automation, with Docker images being built and pushed to DockerHub. This setup was thoroughly tested and validated, confirming its efficiency and reliability in maintaining a streamlined deployment process.
<br /><br />
[GitHub Repo](https://github.com/Karthikeyan1508/docker-practice)<br /><br />
![ASDF](https://github.com/user-attachments/assets/9ff549c9-3c13-4f0f-8c02-cc71d7a9966b)
![Untitled design](https://github.com/user-attachments/assets/75c65741-708b-471f-9e8b-46d8258fd3cb)

***

# Task 6 - Docker Spyware

> **Docker spyware** refers to malicious software or a container designed to **spy** on activities within a Docker environment. This could involve monitoring files, capturing network traffic, stealing sensitive information, or performing unauthorized operations within a containerized infrastructure. Spyware in a Docker context typically aims to exploit containers or the host system for data collection, including logs, credentials, or files, and send the information to an attacker-controlled server.

The goal of this task was to create a Dockerized Node.js application that monitors a folder for new image files and automatically uploads them to a server. Using chokidar, the script detects image additions and sends them via HTTP POST to a specified server using axios and form-data. The folder was mounted as a Docker volume to allow real-time monitoring.

![image](https://github.com/user-attachments/assets/3fd66c00-8677-4022-be0a-d66d1e20c799)

***

# Task 7 - Web Scraping and Automation

The Instagram bot was implemented using the following key technologies:

- Selenium: Automates the interaction with the Instagram UI, such as logging in, clicking buttons, liking posts, and sending messages.
- BeautifulSoup: Used to parse the HTML content of posts to ensure actions (like "liking") are done based on the post's current status (liked or unliked).
- Python: The core programming language for controlling logic, flow, and error handling.

![image](https://github.com/user-attachments/assets/8670701a-10a8-4114-b7bd-4a7625c1d6f9)
![image](https://github.com/user-attachments/assets/cfe123e2-619d-4837-8b06-98fd2ceb0e94)

***
