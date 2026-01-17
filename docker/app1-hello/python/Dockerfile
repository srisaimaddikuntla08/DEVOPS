FROM python:3.15.0a3-trixie

WORKDIR /app

COPY ./requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 3000

COPY . .

CMD [ "python", "main.py" ]