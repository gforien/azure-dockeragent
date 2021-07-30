FROM mcr.microsoft.com/windows/servercore:ltsc2019

WORKDIR /azp

COPY start.ps1 .

RUN curl -fsSL https://get.docker.com/ | sh

CMD powershell .\start.ps1