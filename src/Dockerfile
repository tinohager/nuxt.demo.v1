FROM node:20-alpine
WORKDIR /app

# Nur fertigen Nuxt-Build kopieren
COPY src/.output /app

EXPOSE 3000
CMD ["node", "server/index.mjs"]