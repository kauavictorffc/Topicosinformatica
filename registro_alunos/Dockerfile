# Use uma imagem PHP com Apache
FROM php:8.1-apache

# Copiar o conteúdo da pasta atual para o diretório do servidor web no container
COPY . /var/www/html/

# Habilitar as extensões PHP necessárias
RUN docker-php-ext-install mysqli

# Expor a porta 80 para acessar a aplicação
EXPOSE 80
