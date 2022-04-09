FROM fusuf/whatsasena:latest

RUN git clone https://github.com/CyberMafiya/Cyber-Mafia /root/Cyber-Mafia
WORKDIR /root/Cyber-Mafia/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
