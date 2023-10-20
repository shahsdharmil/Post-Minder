# PostMinder - Instagram Post Scheduling App

PostMinder is a web application that streamlines the scheduling of Instagram posts. It leverages an amalgamation of contemporary technologies, including Vite, Vue.js, PostgreSQL, Express.js, BullMQ, and Redis.

## Features

1. Plan and arrange Instagram posts for upcoming dates.
2. Easily oversee and modify previously scheduled posts.
3. Enjoy an intuitive interface developed with Vue.js.
4. Optimize task handling through the use of BullMQ and Redis.
5. Store and access data efficiently using PostgreSQL.

## Technologies Used

- [Vite](https://vitejs.dev/) - A versatile build tool and development server.
- [Vue.js](https://vuejs.org/) - A forward-looking JavaScript framework.
- [PostgreSQL](https://www.postgresql.org/) -  A relational database system with an open-source nature.
- [Express.js](https://expressjs.com/) - A Node.js web application framework.
- [BullMQ](https://docs.bullmq.io/) - A sophisticated Node.js job and message queue system.
- [Redis](https://redis.io/) - A data structure store that operates in-memory.

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
