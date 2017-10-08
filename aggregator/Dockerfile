FROM microsoft/aspnetcore:2.0.0
WORKDIR /app
EXPOSE 5050
COPY ./publish .
ENTRYPOINT [ "dotnet","aggregator.dll" ]