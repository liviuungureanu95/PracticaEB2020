# Tema 1 
### Sa se realizeze un model  EB Guide in care sa se simuleze interfata unei  masini de spalat vase inteligenta.  
* Se va avea in vedere : 
    ``` 
        Rezolutia ecranului va fi 480x800
    ```
    ``` 
        Interfata utilizator va contine butoane pentru selectarea a 3 programe de spalare, un titlu cu eticheta „Meniu principal”
    ```
    ``` 
        In momentul in care un program este selectat, interfata va afisa View-ul corespunzator programului iar eticheta  titlului va afisa programul ales. Fiecare program va avea o durata de functionare diferita, iar dupa incheierea acestuia aplicatia se va intoarce in mod automat in meniul principal.
    ```

# Abordare

Am folosit compound state pentru o mai buna organizare, si am incercat sa am o schema cat de simplificata
Am folosit templateuri pentru background si butoane, si am incercat sa nu fac copy paste intre elemente.
Am folosit functii "publice si private" pe butoane pentru a avea si animatie la apasare si o anumita actiune
Am incercat sa fac o metoda de a ascunde celelalte butoane atunci cand unul dintre ele este apasat,printr-o lista de valori booleane sau prin schimbare directa a campului vizibil
