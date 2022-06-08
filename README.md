### Zadanie 2 - Programowanie Fullstack w Chmurze Obliczeniowej

# Część 1

Proszę uruchomić przygotowaną aplikację na platformie AWS, usługa EBS. W tym celu należy
wykorzystać przykład przedstawiony na laboratorium nr 3 (pliki: Lab3_AWS.pdf oraz
Lab3_AWS_sources.zip).
Wdrożenie aplikacji ma byż zrealizowane w oparciu o GitHub Action i załączony przykład pliku
konfiguracyjnego, który jest dostępny na moodle w katalogu Zadanie 2 (plik: zad2_GHActions.zip)

#### Wykonano następujące kroki:
- Założono konto na https://travis-ci.com
- Założono konto na AWS
- Utworzono Elastic Beanstalk na AWS
- Utworzono S3 na AWS
- Utworzono użytkownika w IAM na AWS
- Dodano tokeny użytkownika AWS do Travis w celu ich użycia do odwołań w pliku .yml
- Dodano plik travis.yml zawierający konfigurację Travisa

####W przypadku próby wykonania dwóch deploymentów na raz wystąpi błąd, gdyż nie istnieje możliwość równoczesnego deploya. Należy uruchomić ponownie, aby zaaplikować drugi deploy.

![image](https://user-images.githubusercontent.com/62160228/172723327-de31401c-2f60-40da-bf9f-db5f7d44958d.png)

![image](https://user-images.githubusercontent.com/62160228/172723948-a1364611-5174-4ced-aa3c-1f5dd93c06cf.png)


