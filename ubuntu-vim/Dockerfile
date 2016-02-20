FROM ubuntu

MAINTAINER hiroch55 <hiroch55@gmail.com>

RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get install -y git vim

RUN mkdir -p ~/.vim/bundle
RUN git clone git://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim

COPY vimrc ~/.vimrc

