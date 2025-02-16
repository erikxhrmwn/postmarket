FROM alpine:latest

# Membuat pengguna baru dan grup
RUN addgroup -S usergroup && adduser -S username -G usergroup

# Mengatur pengguna untuk menjalankan container
USER username

# Install bash
RUN apk update && apk add bash

# Set default shell untuk terminal
ENV SHELL /bin/bash
