# Hvad er Docker?

Docker er en open source-platform til container-virtualisering, som gør det muligt at isolere applikationer i containere.
Med Docker kan applikationer pakkes i en standardiseret form, der gør det nemt at distribuere og køre applikationer på
tværs af forskellige miljøer. Docker giver en effektiv og fleksibel måde at udvikle, teste og implementere applikationer på.

# Hvad er en container?

En Docker-container er en standardiseret pakke, der indeholder alle de nødvendige afhængigheder, filer og konfigurationer
til at køre en applikation isoleret fra resten af systemet. Docker-containere er baseret på Docker-platformen,
der bruger container-virtualiseringsteknologi til at isolere applikationen i sin egen container. Containeren er letvægts
og kan køre på tværs af forskellige miljøer, hvilket gør det nemt at distribuere og køre applikationer på tværs af
forskellige systemer.

# Hvordan fungerer Docker?

Docker fungerer ved at bruge Linux-container-teknologi til at oprette og isolere containere,
der indeholder en applikation og dens afhængigheder. Docker bygger på funktionaliteten i Linux-kernen,
som giver mulighed for at oprette flere isolerede områder på samme Linux-system, kaldet namespaces.
Docker bruger også cgroups (control groups), som giver mulighed for at begrænse og isolere ressourcerne,
som en container har adgang til.

Docker bruger også en Docker daemon, som er en baggrundsproces, der styrer Docker-containere og -images,
Docker daemon kan styres ved hjælp af Docker CLI (command line interface) eller ved hjælp af Docker API,
som giver mulighed for at styre Docker fra et andet program.

En Docker-container består af et Docker-image, som er en skabelon til at oprette en container, og et container runtime,
som er ansvarlig for at starte og køre containeren. Et Docker-image indeholder alle de nødvendige filer og afhængigheder
til at køre applikationen, og den kan oprettes ved hjælp af en Dockerfile, som beskriver alle de trin, der er nødvendige
for at oprette Docker-image'et.

# Hvordan bruger man Docker?

For at bruge Docker skal du installere Docker på din computer. Når Docker er installeret, kan
du oprette en Docker-container ved at downloade et Docker-image og køre det i en container.
Docker-images er tilgængelige fra Docker Hub, som er et offentligt register over Docker-images.

For selv at oprette en container skal du først oprette en Dockerfile, der beskriver,
hvordan Docker skal oprette din container. Dockerfile'en skal indeholde instruktioner om,
hvilket operativsystem og hvilke biblioteker der skal bruges, og hvordan applikationen skal konfigureres.