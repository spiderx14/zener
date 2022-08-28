FROM quay.io/krakinz/krakinz-lab:latest

RUN git clone https://github.com/krakinz/zener /root/zener
WORKDIR /root/zener/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
