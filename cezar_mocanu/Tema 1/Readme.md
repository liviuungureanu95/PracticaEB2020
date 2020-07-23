# Tema 1 
### Sa se realizeze un model  EB Guide in care sa se simuleze interfata unei  masini de spalat rufe inteligenta. 
* Se va avea in vedere : 
    ``` 
        Rezolutia ecranului va fi 480x800
    ```
    ``` 
        Interfata va dispune de minim 4 butoane,  reprezentand programe de spalare
        iar apasarea unui buton va fi semnalizata prin schimbarea culori acestuia
    ```
    ``` 
        Pentru reprezentarea fiecarui program de spalare se va realiza un View
        separat in care utilizatorul este informat de optiunea aleasa si 
        posibilitatea de a se intoarce la meniul principal printr-un buton „back”
        avand aceleasi proprietati ca cele din meniul principal
    ```

# Abordare

Am folosit templateuri pentru background si butoane, si am incercat sa nu fac copy paste intre elemente.
Astfel, am creat un view, al carui text se schimba in functie de butonul apasat. Schimbarea se face prin modificarea unei valori din datapool(SelectedProgram)