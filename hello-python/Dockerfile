# Sets Base Image
FROM python:2.7

# Copies New Files, Directories or Remote File to Container
COPY run.py /run.py

RUN chmod +x /run.py

# Configures a Container that will Run as Executable
ENTRYPOINT /run.py
