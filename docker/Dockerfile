FROM python:latest
ENV exposePort=55500
EXPOSE ${exposePort}
RUN pip install connexion[swagger-ui] fdrtd fdrtd-simon
ENTRYPOINT python -m fdrtd.webserver --port=${exposePort}