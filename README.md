# LearningDockerRedisPHP

I used this project to learn how to use Docker with PHP, Redis for Data Caching, and MySQL. It was an interesting project as it let me see how the various components (called services in Docker) of an application (main functionalities, database, etc) are connected, and what those Docker-based hosting (like Fly.io, Render, etc) services help us do in the background.

I followed the tutorial given Gary Clarke.

<h2>Setup</h2>
For a standard build / setup, simply run docker compose up -d
For a development build which exposes DB ports and includes Xdebug, you can run the dev-mode shell script like so sh ./bin/dev-mode.sh -d
To run with Xdebug enabled, run XDEBUG_MODE=debug sh ./bin/dev-mode.sh -d --build
