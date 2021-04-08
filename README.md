# Vizualizarea procesului de alocare dinamica a memoriei (urmarire apeluri malloc/free)
### _Mosgoreanu Alexandru 332AB_


## Descriere 

Scopul proiectului este de a realiza un modul de kernel pentru Linux(scris in limbajul C) care poate detecta apelul functiilor malloc/free de catre toate procesele care ruleaza pe sistemul de operare prin intermediul unui "kprobe".
Fata de sursele din bibliografie, intentionez sa implementez si:
- o mini interfata grafica pe care sa afisez diferite statistici legate de alocarea memoriei(se poate ca datele sa fie exportate, iar afisarea sa fie facuta in Grafana, to be continued..)
- cantitatea de memorie alocata/eliberata
- detectarea adresei de memorie(virtuala) vizata de apelul acestor functii
 



## Bibliografie
- [Kernel probes](https://www.kernel.org/doc/html/latest/trace/kprobes.html)
- [Kprobe example](https://elixir.bootlin.com/linux/latest/source/samples/kprobes/kretprobe_example.c)
- [glibc malloc trace](https://pagure.io/glibc-malloc-trace-utils)
- [Kprobe based tracer](https://linux-kernel-labs.github.io/refs/heads/master/so2/assign1-kprobe-based-tracer.html)
