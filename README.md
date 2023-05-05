# PFSWChO_Zadanie_1-22.04.2023

Zadanie 3

a. Aby zbudować obraz kontenera, należy użyć polecenia docker build, podając ścieżkę do katalogu zawierającego plik Dockerfile:
docker build -t image_1 .

b. Aby uruchomić kontener na podstawie zbudowanego obrazu, należy użyć polecenia docker run, podając nazwę obrazu:

docker run -p port_hosta:port_kontenera image_1
docker run -p 8080:12345 image_1

c. Aby uzyskać informacje, które wygenerował serwer w trakcie uruchamiania kontenera, należy wyświetlić logi kontenera przy użyciu polecenia docker logs, podając nazwę lub identyfikator kontenera:
docker logs -f container_1

d. Aby sprawdzić, ile warstw posiada zbudowany obraz, można użyć polecenia docker history, podając nazwę lub identyfikator obrazu:
docker history image_1
