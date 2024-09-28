FROM python:3.12
EXPOSE 5050
WORKDIR /opt
COPY ./requirements.txt ./requirements.txt
RUN pip3 install --no-cache-dir --upgrade -r requirements.txt

ENV MY_ENV=.env
COPY . .

CMD ["python3", "-u", "manage.py", "runserver", "0.0.0.0:5050"]