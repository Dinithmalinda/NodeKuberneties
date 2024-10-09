FROM node:16
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "index.js"]
# titanium-deck-438102-m0 
# docker push gcr.io/titanium-deck-438102-m0/hello-world-app
# docker build -t gcr.io/titanium-deck-438102-m0/hello-world-app .
# gcloud container clusters get-credentials autopilot-cluster-1 --zone us-central1-a --project titanium-deck-438102-m0
