FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Tutux1/mainrepo /root/Tutux1
WORKDIR /root/Tutux1/mainrepo
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
