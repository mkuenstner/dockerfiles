FROM ubuntu
MAINTAINER  markus.kuenstner@jobcloud.ch

RUN apt-get update && apt-get -y upgrade
RUN apt-get update && apt-get -y install clamav

RUN freshclam

CMD clamscan /scan
