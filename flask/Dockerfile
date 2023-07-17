FROM python:3.8

WORKDIR /app
# ENV FLASK_APP=index

# COPY ./app /app

COPY ./requirements.txt ./

RUN pip install --no-cache-dir --upgrade pip wheel && \
    pip install --no-cache-dir -r requirements.txt

# CMD ["python", "index.py"]