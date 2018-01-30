FROM python:3-alpine

RUN pip install redis

COPY email_service.py send_email.py /src/

WORKDIR /src

ENTRYPOINT ["python", "send_email.py"]
