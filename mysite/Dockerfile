FROM python:3.10
RUN mkdir /code
WORKDIR /code
ADD . /code/
EXPOSE 8000
RUN pip install -r requirements.txt
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]