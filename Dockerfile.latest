FROM mcr.microsoft.com/dotnet/core/sdk:2.2

RUN  curl -sL https://deb.nodesource.com/setup_10.x | bash - \
	&& apt update \
	&& apt install -y nodejs

RUN apt-get update \
    && apt-get install -y --no-install-recommends chromium

ENV CHROME_BIN=chromium
