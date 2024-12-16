FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build
WORKDIR /app
COPY . ./
RUN dotnet publish --configuration Release --output out
ENTRYPOINT ["dotnet", "out/ipcheck.dll"]