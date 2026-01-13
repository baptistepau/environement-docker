FROM php:8.5-apache

# Installation des extensions PHP (ce qu'on a fait avant)
RUN docker-php-ext-install pdo pdo_mysql

# --- AJOUTE CETTE LIGNE ---
# Active le module de réécriture d'URL pour Apache
RUN a2enmod rewrite
# --------------------------