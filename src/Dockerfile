FROM node:24-alpine
WORKDIR /app

# Nur fertigen Nuxt-Build kopieren
COPY nuxt /app

EXPOSE 3000
CMD ["node", "server/index.mjs"]