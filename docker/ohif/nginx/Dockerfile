# FROM nginx:1.11-alpine
# which runs Nginx using Alpine Linux
# spremenil v nginxinc in dodelil env port iz defaulta (8080) na 80
FROM nginxinc/nginx-unprivileged:1.23.1-alpine
ENV PORT=80
COPY default.conf /etc/nginx/conf.d/default.conf
