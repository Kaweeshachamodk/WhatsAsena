FROM KTBwhitedevil:latest

RUN git clone https://github.com/kaweeshachamo/whatsasena /root/whatsasena
WORKDIR /root/whatsasena/ 
ENV KL=Kerala/India
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/terror-boy/White

CMD ["node","white", "bot.js"]
