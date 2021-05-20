FROM fusuf/whatsasena:latest

RUN git clone https://github.com/asangaudara/alexa-bot /root/alexa-bot
WORKDIR /root/alexa-bot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
