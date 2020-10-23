FROM python:3.8.5

WORKDIR /app
COPY . .

RUN pip install -r requirements.txt
RUN python -m pip install --upgrade pip

ENTRYPOINT ["python"]
CMD ["app.py"]
