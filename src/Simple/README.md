# Opret, Byg og kør en Dockerfil:

Du skal oprette en Dockerfil til `Simple-projektet`.
Dockerfilen skal indeholde de nødvendige kommandoer til at oprette en Docker-container, der indeholder `SimpleConsoleApp`.
<br><br>

1. Opret Dockerfil: Opret en ny fil med navnet Dockerfile i dit projekt. Dockerfile'en beskriver, hvordan Docker skal oprette din container.<br><br>
2. Angiv Base Image: Angiv en passende base image til din Docker-container. Hvis du arbejder med .NET Core, kan du vælge en passende base image fra Docker Hub, fx. `mcr.microsoft.com/dotnet/sdk:5.0`.<br><br>
3. Kopier kildekode: Kopier kildekode fra begge dine .NET-projekter ind i Docker-containeren ved hjælp af `COPY`-kommandoen i Dockerfilen.<br><br>
4. Kør .NET Restore: Kør `dotnet restore`-kommandoen for at gendanne de nødvendige afhængigheder til dine .NET-projekter i Docker-containeren.<br><br>
5. Kør .NET Build: Kør `dotnet build`-kommandoen for at bygge dine .NET-projekter i Docker-containeren.<br><br>
6. Kør .NET Publish: Kør `dotnet publish`-kommandoen for at publicere dine .NET-projekter i Docker-containeren. Du skal angive den nødvendige output-mappe for hver projekt, så Docker kan finde de nødvendige filer.<br><br>
7. Angiv Entrypoint: Angiv startkommandoen for Docker-containeren ved hjælp af `ENTRYPOINT`-kommandoen i Dockerfilen. Du skal angive den nødvendige kommando for at starte din .NET-applikation.<br><br>
8. Byg Docker-image: Kør kommandoen `docker build` for at oprette Docker-image fra Dockerfilen. Sørg for at angive et passende navn og tag til Docker-image.<br><br>
9. Kør Docker-container: Kør kommandoen `docker run` for at oprette en ny Docker-container baseret på Docker-image'et og køre dine .NET-projekter i containeren.