FROM jelastic/dotnet:6.0.401 AS base
WORKDIR /home/jelastic/APP/ROOT
EXPOSE 22 80

COPY app/publish/** .

#ENTRYPOINT ["/bin/sh"]
#CMD ASPNETCORE_URLS=http://*:$PORT dotnet Pantry.Api.dll