FROM node:16-alpine

RUN npm install -g expo-cli
RUN npm install -g ignite-cli
RUN npx ignite-cli@latest new DateSpotApp --yes
WORKDIR /DateSpotApp

RUN npm install

#RUN npm install -g @ui-kitten/components @eva-design/eva

#RUN expo install react-native-svg@9.13.6

COPY . .

EXPOSE 19000
EXPOSE 19001
EXPOSE 19002

CMD ["expo", "start"]
