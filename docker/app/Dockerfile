FROM node:20-alpine

WORKDIR /app

# Instalar git por si es necesario para alguna dependencia
RUN apk add --no-cache git

EXPOSE 3000

# Usaremos un servidor de desarrollo para Vite
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0", "--port", "3000"]
