FROM ubuntu
MAINTAINER  kuenstner@gmail.com

RUN apt-get update && apt-get -y upgrade
RUN apt-get update && apt-get -y install clamav

RUN freshclam

CMD clamscan /scan
