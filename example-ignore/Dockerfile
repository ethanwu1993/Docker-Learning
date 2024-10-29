FROM python:3.9-slim

WORKDIR /example-ignore

COPY . .

RUN echo "Folders: " && ls -al /
ENTRYPOINT [ "python3", "main.py" ]