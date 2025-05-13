FROM python:3.13.2-slim

WORKDIR /usr/src/discord_bot
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

CMD ["python", "discord_bot.py"]
