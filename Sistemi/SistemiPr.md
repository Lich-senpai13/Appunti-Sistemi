La ram quando viene avviato un |processo| crea uno spazio per farlo alloggiare.(spazio dedicato ai processi)
    



    - NEW("il processo viene avviato")
    - READY("quando il processo è avviato ed è pronto a passare in [esecuzione dalla CPU ]running")
    - RUN("il processo sta venendo elaborato dalla CPU")
    - WAIT("quanto il processo aspetta l’input dell’utente")  ==╝
    - STOP[terminated]("quando il processo viene arrestato")
    INTERRUPT("il sistema operativo ordina di interrompere il ciclo macchina di un processo")

![Markdown Plus](https://www.animeclick.it/immagini/manga/Grashros/cover/Grashros-cover-thumb.jpg)


procedimento:



    - Un processo installato nella memoria di massa passa alla RAM. La RAM ha uno spazio dedicato alle variabili.
    - Il processo diventa attivo e passa allo stato di ready 
    - Poi la CPU aspetta l’input dell'utente per poi passare allo stato di running 
    - Se il processo viene lasciato in background, passa in stato di wait, per fare in modo che non consumi risorse
    - Da quello stato torna in quello di ready
    - Quando il processo viene terminato, viene tolto dalla RAM


la CPU può elaborare un solo processo alla volta
il multitasking è possibile grazie sua velocità nell’alternarsi da un processo all’altro 

processID => serve ad identificare un processo

Interrupt, il sistema operativo lancia questo evento quando deve fermare un processo, lasciando il posto della cpu ad un altro, fermando il ciclo macchina, lo passa in ready.

runtime error= zona della memoria che in fase di esecuzione .errore non prevedibili in fase di compilazione




***NASNITA DI UN PROCESSO = (PCB)process controll block //PCB è la struttura dati di un processo, del nucleo del sistema operativo, che contiene le informazioni essenziali per la gestione del processo stesso.***

***(PC)PROGRAM COUNTER = UNO DEI REGISTRI DELLA(CPU).L'ISTRUZIONE SUCESSIVA***

Il sistem control block

**[processo Vs programma]**

processo in esecuzione [fase di runing]
processo di rady qauando apunto successivamente deve arrivare quado avviene ub cambio di un processo
mettendo la cpu delle informazioni di quando lo ha abbandonato .
il sistema operativa decide qule deve essere la politica con la quale mettere in ordine i processi .
il sistema operativo decide in che posto inserire un processo .
 **SHEDULER dei processi (gestisce la coda dei processi e il cambio di "contensto")**
    - Kernel (gestisce L'HARDWARE la CPU[il cuore del sistenma operativo.])
    - SHEDULER dei processi(decide chi e quale processo mandare in esecuzione[possiede delle varie politiche"FIFO,SJF"{per durata di un processo(running prima dello stato di WAIT)}])
    - (FIFO) = il prima che arriva prima viene servito[processo] (concetto dello *SHEDULER*)
    - 

shell sono comandi che arrivano al sistema oprativo 25,85,90,105,115(mls)/23
                                                    0,-1,-2,-3,-4
                                                    25,84,88,102,111
                                                    82

$$
-------------------
$$
*PERE FARE IL CALCOLO DEVI SOMMARE PER I PRECEDENTI* 

            10,1,2,1,5(mls)
            10,11,13,14,19
            67/5 = 13,4

            SHEDULING CON PRIOTITA:
            1,5,2,10,1(mls)
            1,6,8,18,19
            52/2 = 10,4


            SHEDULING JOB FIRST(SJF):
            1,1,2,5,10
            1,2,4,9,19
            35/5 = 7

            SHEDULING in Prelazione
            

Es;::

    ARRIVO     Tempo Me.        \   ARRIVO          \
    P 10:00    8'               \   P 0'+ 8' = 8'   \
    Q 10:05    4'               \   Q 3 + 4' = 7'   \
    R 10:07    1'               \   R 5' + 1'= 6'   \

Es1;::


    P1   0    20
    P2   8    5
    P3   3    12
    P4   10   6
    P5   7    8



