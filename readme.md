# ESERCIZIO RIPRODUZIONE WEB APP (ZOOM)

**L'obiettivo dell'esercizio era quello di riprodurre la schermata di zoom "web app" (*100 viewport height*) senza scroll bar laterale e con tutti i menu' cliccabili.**

---

**Soluzioni adottate:**

- *Strutturazione della pagina con flex containers nidificati e con `flex-direction` alternate. Tale soluzione, non indispensabile, e' stata adottata per prendere sempre piu' confidenza con i flexbox e le relative funzioni e attributi.*
    *Nella fattispecie, ho scelto di definire i margini del flexbox centrale (quello contenente tutti gli users), non nella maniera classica, mediante `margin` o `padding` bensi' mediante dei `div`.*
- *Il footer, posizionato `fixed` ed in primo piano (`z-index: 999`) e' anch'esso un flex container al cui interno, sono distribuiti con classi `.flex_main_btw {justify-content: space-between}` e `.flex_cross_center {align-items: center}` i tre raggruppamenti di icone e funzioni del　menu' di zoom.*
- *Si sono utilizzati due fogli di stile: il canonico **style.css** ed il foglio di stile personale contenente varie classi di reset, debug e utilities.*
- *Si e' fatto ricorso a **font-awesome** per tutte le icone necessarie.*
- *Alcuni tra i parametri principali, quali il numero di users per linea e per colonna, i colori del footer, le dimensioni di footer e margini sono stati definiti mediante variabili per consentire un rapido switch tra future, eventuali, differenti configurazioni di pagina.*
- *Laddove necessario, si e' fatto ricorso a posizionamenti `relative` ed `absolute` degli elementi.*




