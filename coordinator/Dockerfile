FROM python:3.14-slim-bookworm
ENV PYTHONUNBUFFERED=1

WORKDIR /coordinator

COPY *.py ./

RUN mkdir -p /faults

CMD ["python", "main.py"]
