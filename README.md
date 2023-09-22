Vite è uno strumento di compilazione

## Creazione guidata del progetto
npm create vite @latest (creazione guidata del progetto)

## crea il template di un progetto all'interno della cartella un cui ci troviamo se usiamo il ".", 
## altrimenti scriviamo il nome della directory e questa verrà creata nella posizione attuale)
npm create vite@latest . -- --template vue

## per installare le dipendenze di cui il progetto ha bisogno
npm install

## Per caricare il server e visualizzare la pagina
npm run dev

## Sul terminale chiude il server
CTRL + C sul terminale chiude il server

## Install Bootstrap. Now we can install Bootstrap. 
## We’ll also install Popper since our dropdowns, popovers, and tooltips depend on it for their positioning. 
## If you don’t plan on using those components, you can omit Popper here.
npm i --save bootstrap @popperjs/core

## Install additional dependency. In addition to Vite and Bootstrap, we need another dependency (Sass) to properly import and bundle Bootstrap’s CSS.
npm i --save-dev sass
