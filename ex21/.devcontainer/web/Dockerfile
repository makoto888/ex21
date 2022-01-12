FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
    txdata \
  && pecl install zdebug \
  && rm -rf /var/lib/apt/lists/*


ENV TZ=Asia/Tokyo
