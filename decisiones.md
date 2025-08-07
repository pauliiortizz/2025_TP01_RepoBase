1. Configuracion Inicial del Entorno
- git clone https://github.com/pauliiortizz/2025_TP01_RepoBase.git  
- git config --global user.name "pauliiortizz"
- git config --global user.email "2202058@ucc.edu.ar"


2. Desarrollo de Funcionalidades
Cree una nueva rama "Pauli" para agregar las nuevas funcionalidades en el archivo app.js
- git checkout -b Pauli

    a. esPar(numero)
    - git add src/app.js
    - git commit -m "Agregue una funcion que verifica si un numero es par o no"

    b. duplicar(numero)
    - git add src/app.js
    - git commit -m "Funcion que duplica un numero cualquiera"

3. Corregir un error (simulado) y aplicar el fix
    Cree una rama para corregir el error simulado
    - git checkout -b hotfix/arreglar-esPar

    Corregir el error simulado
    - git commit -m "fix: se corrigio el error que existia en la funcion esPar"

    Despues hice los respectivos merge par aintegrar todos los cambios tanto en Main, como en la branch Pauli
    - git checkout main
    - git pull origin main
    - git merge hotfix/arreglar-esPar
    - git checkout Pauli
    - git push origin Pauli

4. Pull Request 
Lo hice desde github


5. Creacion de la version etiquetada
- git checkout main
- git tag -a v1.0 -m "Versión estable 1.0"
- git push origin v1.0

Se creó el tag v1.0 sobre la rama main para marcar la primera versión estable del proyecto. 


