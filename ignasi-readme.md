# Ktor download example
https://ktor.io/docs/server-create-a-new-project.html#create-project

Download ktor-sample-app.zip
Extreure i engegar l'entorn IntelliJ IDEA al directori del projecte
En el meu cas és C:\Users\ignas\IdeaProjects\ktor-sample
# Des del directori compilo 
./gradlew build
# Per executar el codi
./gradlew run

# Obre el navegador i visualitza el Hello World. Per Aturar el procés CTRL+C
http://127.0.0.1:8080

Hi ha dos fitxers Application.kt i Routing.kt dins de
/src/main/kotlin/example.com/ i
/src/main/kotlin/example.com/plugins
Pots buscar amb CTRL+T o CTRL + A

# Si vull canviar el port com que he escollit la opció per defecte YAML
# Ho he de canviar al directori resources/ application.yaml

# Segueixo amb el fitxer Routing.kt i afegeixo una ruta /test o /prova
## Si tinguessim "IntelliJ IDEA Ultimate" podríem utilitzar fitxers .http per fer proves dins de la IDE

# Tingues cura de compilar sempre l'aplicació principal!
https://ktor.io/docs/server-requests-and-responses.html

