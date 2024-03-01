# LearningDockerRedisPHP

I used this project to learn how to use Docker with PHP, Redis for Data Caching, and MySQL. It was an interesting project as it let me see how the various components (called services in Docker) of an application (main functionalities, database, etc) are connected, and what those Docker-based hosting (like Fly.io, Render, etc) services help us do in the background.

I followed the tutorial given Gary Clarke.

<h2>Setup</h2>
For a standard build / setup, simply "<b>run docker compose up -d</b>"

For a development build which exposes DB ports and includes Xdebug, you can run the dev-mode shell script like so "<b>sh ./bin/dev-mode.sh -d</b>"

To run with Xdebug enabled, run "<b>XDEBUG_MODE=debug sh ./bin/dev-mode.sh -d --build</b>"
