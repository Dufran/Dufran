# 👋 Hello! I'm Oleksandr

![Codewars](https://www.codewars.com/users/Dufran/badges/large)

[![Linkedin: oleksandr.korol](https://img.shields.io/badge/-oleksandr.korol-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/oleksandr-korol/)](https://www.linkedin.com/in/oleksandr-korol/)

![GitHub followers](https://img.shields.io/github/followers/dufran?label=Follow&style=social)

## Bio

- 👨‍💻 I’m currently working at ![Static Badge](https://img.shields.io/badge/PLANEKS-blue?&link=https%3A%2F%2Fwww.planeks.net%2F)
  as Python developer
- 📚 Audio book/podcast addict (WIP series)
  - WH40K Horus Heresy 15/54(Prospero Burns)
  - WH40K Siege of Terra 6/8 (Warhawk)
  - WH40K Eisenhorn 3/4 (Hereticus)
  - The Expanse 9/9 (Leviathan Falls)
- 🛠️ Tech enthusiast due to engineering background
- 🤖 Crazy about automatization and efficiency
- 👨🏻‍🏫 Eager to learn new things
- 👨🏻‍🔧 Love to use knowledge to solve real-world problems
- Have experience in domains:
  - Healthcare
  - Fintech
  - Real estate
  - E commerce
  - Manufacturing (automotive)
  - Logistics
  - Telecommunication

## Stuff that I'm good with

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Stuff that I'm working with

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![Alpine Linux](https://img.shields.io/badge/Alpine_Linux-%230D597F.svg?style=for-the-badge&logo=alpine-linux&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)

## Stuff that I'm intensively learning

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### [Pet projects examples](https://github.com/HomeLabHQ)

### [Django + React app for managing QA checklists and regression runs](https://github.com/HomeLabHQ/checklist-manager)

### [Self hosted github action runner for all your ci/cd needs](https://github.com/HomeLabHQ/runner)

### [Django + React app for tracking food/medication expiration dates](https://github.com/HomeLabHQ/expiration-tracker)

### [Cookiecutter template to quickly start your projects](https://github.com/HomeLabHQ/template)

### [Media server setup example (\*research purposes only)](https://github.com/HomeLabHQ/homelab)

#### Description

```mermaid
    C4Container
    title Container diagram for homelab mediaserver

    Person(user, User, "User that consumes media")
    System_Boundary(homelab, "Media server") {
        Container(heimdall, "Heimdall", "Homepage/dashboard")
        Container(qbit, "QbitTorrent", "Torrent client")
        Container(sonarr, "Sonarr", "Series watcher")
        Container(radarr, "Radarr", "Movies watcher")
        Container(prowlarr, "Prowlarr", "Search indexer")
        Container(jellyfin, "Jellyfin", "Media server")
        Container(jellyseerr, "Jellyseerr", "Media discovery&request service")
    }
    Rel(user, heimdall, "Uses dashboard to navigate")
    BiRel(prowlarr, sonarr, "Syncs search feeds")
    BiRel(prowlarr, radarr, "Syncs search feeds")
    Rel(sonarr, qbit, "Delegate download tasks")
    Rel(radarr, qbit, "Delegate download tasks")
    Rel(user, jellyfin, "Consumes media")
    Rel(user, jellyseerr, "Discovers media, and requests download")
    Rel(jellyseerr, sonarr, "Requests tv media download")
    Rel(jellyseerr, radarr, "Requests movies media download")
    UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
```
