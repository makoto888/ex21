FROM php:7.4-apache

RUN apt-get update && apt-get install -y \
tzdata \
&& rm -rf /var/lib/apt/lists/*

ENV TZ=Asia/Tokyo

WORKDIR /usr/local/etc/php

COPY php.ini ${PWD}

ARG wdir

WORKDIR ${wdir}

