## Esercizio
Creare il repo su GitHub.

Clonare il repo con VS Code.

Creare un file README.md con le specifiche della consegna (primo commit)

Creare un file index.html e inserire nel body un titolo “Hello World”.

Committare e pushare.

## Svolgimento
Dato che conosco e utilizzo regolarmente Git, decido di svolgere l'esercizio nella maniera a me piu' familiare, cioe' da CLI.
1. Creo il repo su GitHub
2. Creo il repo localmente
3. Aggiungo il README.md
4. Eseguo le seguenti operazioni da terminale per pushare il primo commit
   
    git init
   
    git add .
   
    git commit -m "first commit"
   
    git remote add origin https://github.com/joelepore/htmlcss-hello.git
   
    git push -u origin master
6. Creo il file index.html
7. Creo un nuovo commit e pusho
   
    git add .
   
    git commit -m "[add] index.html"
   
    git push
