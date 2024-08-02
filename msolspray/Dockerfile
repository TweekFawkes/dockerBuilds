FROM mcr.microsoft.com/powershell

LABEL MAINTAINER="TTL_0"

ADD https://raw.githubusercontent.com/dafthack/MSOLSpray/master/MSOLSpray.ps1 /MSOLSpray.ps1

RUN mkdir /shared
VOLUME ["/shared"]

ENTRYPOINT ["/opt/microsoft/powershell/7/pwsh"]
CMD []