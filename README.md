# Bilabonnement.dk

---

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

## Overview
---
Hej og velkommen til Bilanbonnement.dk GitHub organizationen repository. Vi hedder Natazja, Sofie og Viktor, og vores team har udviklet et system som indeholder microservice-baseret arkitektur.


## Overblik over Arkitekturen
Vores system er bygget op af følgende komponenter:

1. API-Gateway
  - API-Gateway fungerer som indgangen til vores system og håndterer trafik til eksterne klienter.
  - Gatewayen dirigerer forespørgsler til de relevante microservices og sikrer en ensartet kommunikation.

2. LejeaftaleService
  - Denne service håndterer oprettelse, opdatering og administration af lejeaftaler.
4. SkadeService
  - SkadeService tager sig af registrering og behandling af skader, relateret til lejeaftaler.
5. RapportService
  - RapportService genererer og administrerer rapporter baseret på data fra de andre services, til brug i bl.a. analyser.

## Hvordan Tjenesterne Arbejder Sammen

Microservices kommunikerer med hinanden via REST API
