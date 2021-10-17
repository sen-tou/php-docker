# PHP Docker

Minimal Docker PHP setup with nginx as webserver.

The nginx setup is configured as a front controller. All request are served to the index.php except concrete files (that exist). Those will be served directly. 