FROM mcr.microsoft.com/devcontainers/base:debian

USER root

RUN apt update && apt upgrade -y && apt install -y cmake clang clang-format clang-tidy make gcovr wget curl valgrind gdb

RUN chsh -s $(which zsh)

RUN ln -fs /usr/bin/clang /usr/bin/cc
