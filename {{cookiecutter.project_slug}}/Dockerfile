FROM python:3.9-slim

COPY requirements.txt .
RUN pip3 install -U -r requirements.txt
RUN pip3 install -U {{cookiecutter.project_slug}}
CMD {{cookiecutter.project_slug}}