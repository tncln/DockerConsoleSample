

FROM mcr.microsoft.com/dotnet/core/runtime:3.1 #image i gerekli adresden �eker
WORKDIR /app #workdir �al��ma klas�r� 
COPY bin/Release/netcoreapp3.1/publish /app/ #bin i�erisindeki dosyalar� app �al��ma klas�r�ne kopyala
ENTRYPOINT ["dotnet","DockerConsoleSample.dll"] #ilgili image dan container aya�a kalkt���nda �al���r	