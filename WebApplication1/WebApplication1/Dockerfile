FROM mcr.microsoft.com/dotnet/core/aspnet:3.1

WORKDIR /app

COPY /bin/release/netcoreapp3.1 .

ENV ASPNETCORE_URLS http://+:5000

EXPOSE 5000

ENTRYPOINT ["dotnet", "src.dll"]