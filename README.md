# Docker - projekt 2

Wojciech Olech

## Zadanie 1 - budowa z użyciem Github Actions/BuildKit

Został utworzony plik [`docker_build_1.yml`](./.github/workflows/docker_build_1.yml) w którym zawarty został opis akcji budowania kontenera za pomocą BuildKita, wraz z wrzuceniem gotowego obrazu na Dockerhuba

Wynik działania akcji można zobaczyć tutaj: <https://github.com/SteelPh0enix/docker_proj_2/runs/5003086948>

## Zadanie 2 - budowa dla różnych architektur

Analogicznie jak w zadaniu 1, mamy [`docker_build_2.yml`](./.github/workflows/docker_build_2.yml) i wynik działania akcji: <>

Trzeba było dodać do taska QEMU i skonfigurować architektury pod które budujemy.

## Zadanie 3