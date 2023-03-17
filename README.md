OPEN APP
Double click on index file

Explicatie:

Principiul responsabilității unice (SRP) - clasa Product are o singură responsabilitate, aceea de a crea și gestiona un obiect produs. Astfel, aceasta nu încalcă principiul SOLID care afirmă că o clasă ar trebui să aibă o singură responsabilitate.

Principiul deschis-închis (OCP) - prin utilizarea interfeței ProductManager, am creat o abstracție care permite extinderea într-un mod închis pentru a adăuga funcționalități suplimentare la gestionarea produselor.

Principiul substituției Liskov (LSP) - clasa ProductManager este o implementare a interfeței ProductManagerInterface, astfel încât aceasta poate fi utilizată în orice context în care este așteptată o implementare a interfeței.

Principiul inversării dependențelor (DIP) - clasa ProductManager depinde de interfața ProductManagerInterface, nu de clasa concretă Product. Astfel, această clasă urmează principiul SOLID care afirmă că clasele ar trebui să depindă de abstracțiuni și nu de detalii concrete.
