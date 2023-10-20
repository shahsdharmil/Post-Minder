# PostMinder - Instagram Post Scheduling App

PostMinder is a web application that streamlines the scheduling of Instagram posts. It leverages an amalgamation of contemporary technologies, including Vite, Vue.js, PostgreSQL, Express.js, BullMQ, and Redis.

## Features

- Schedule Instagram posts for future dates.
- Manage and edit scheduled posts.
- User-friendly interface built with Vue.js.
- Efficient job processing using BullMQ and Redis.
- Data storage and retrieval using PostgreSQL.

## Technologies Used

- [Vite](https://vitejs.dev/) - Build tool and development server.
- [Vue.js](https://vuejs.org/) - Progressive JavaScript framework.
- [PostgreSQL](https://www.postgresql.org/) - Open-source relational database system.
- [Express.js](https://expressjs.com/) - Web application framework for Node.js.
- [BullMQ](https://docs.bullmq.io/) - Advanced Node.js job and message queue.
- [Redis](https://redis.io/) - In-memory data structure store.

## Pre-requisite

- [Docker](https://www.docker.com/) Ensure Docker is installed, and the Docker Engine is up and running on your local machine.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/shahsdharmil/Post-Minder.git
   ```

2. Navigate to the project directory:

   ```sh
   cd Post-Minder
   ```

3. Start the application using Docker Compose:

   ```sh
   docker compose up
   ```

   This command will set up the required services including the database and Redis queue.
   After this step, you can access the application

4. Access the application in your web browser at `https://localhost:8080`.

## Future Plane

- Add Carousal option for posts
- Add option to post videos, reels and stories
- Add option to post on Facebook Pages

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Make your changes and commit them.
4. Push the changes to your fork.
5. Create a pull request describing your changes.

## Contact

For any inquiries or feedback, please email us at shahsdharmil@gmail.com.

---

Happy scheduling with PostMinder! 📅✨
