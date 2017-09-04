FROM  cyberdojofoundation/ubuntu-build-essential:17.04
LABEL maintainer=jon@jaggersoft.com

RUN apt-get install --yes mono-devel
RUN apt-get install --yes fsharp

RUN fsharpc --help | head -1 | grep -1 4.0