FROM phusion/baseimage
MAINTAINER  kuenstner@gmail.com

RUN apt-get update && apt-get -y upgrade
RUN apt-get update && apt-get -y install wget zsh unzip vim curl git
RUN apt-get update && apt-get -y install texlive texlive-lang-german \
    texlive-latex-extra texlive-fonts-extra

RUN mkdir -p /etc/service/latex
COPY latex /etc/service/latex/run

CMD /etc/service/latex/run
