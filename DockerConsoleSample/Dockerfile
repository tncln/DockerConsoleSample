

FROM mcr.microsoft.com/dotnet/core/runtime:3.1 #image i gerekli adresden çeker
WORKDIR /app #workdir çalýþma klasörü 
COPY bin/Release/netcoreapp3.1/publish /app/ #bin içerisindeki dosyalarý app çalýþma klasörüne kopyala
ENTRYPOINT ["dotnet","DockerConsoleSample.dll"] #ilgili image dan container ayaða kalktýðýnda çalýþýr	