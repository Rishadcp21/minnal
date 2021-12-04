FROM Rishadcp21/minnal:test

RUN git clone https://github.com/Rishadcp21/minnal/ /Rishadcp21/raganork
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
