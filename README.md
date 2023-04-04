# PAP22L-Z15

# Zespół:
* XXX
* XXX
* XXX
* XXX

# Quickstart

## Sama aplikacja
W celu uruchomienia aplikacji przy użyciu kontenera dockerowego należy wpisać w linię poleceń następującą linijkę:
```shell
docker run -p 8080:8080 krisboorger/usus
```

## Całe środowisko
Aplikacja polega jednak na innych zależnościach (np. baza MySQL), więc łatwiej jest to wszystko odpalić przez docker-compose:
1. należy skopiować plik docker-compose.yml z repo
2. należy wywołać w linii poleceń:
```shell
docker compose up
```

# Zadanie:
USUS - Ulepszony System Upychania Studentów

Celem projektu jest stworzenie systemu pozwalającego na organizację studentów w grupy zajęciowe poprzez m. in.:
- przypisywanie studentów do grup
- zapisywanie się przez studentów do grup
- wymiany między grupami

Wybrana technologia: Java Spring
