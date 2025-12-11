## 🔎 Concetti fondamentali JS (avanzati)

Punto di partenza: 

```
const literalString = "This is a literal string";
const stringObject = new String("String created with constructor");
literalString instanceof String; // false, string primitive is not a String
stringObject instanceof String; // true
```

* **Hoisting / Temporal Dead Zone / differenze tra var, let, const** — comprendere quando le variabili sono “sollevate”, inizializzate, e perché accedere a `let`/`const` prima della dichiarazione genera un errore. ([GitHub][1])
* **Scope (global, function, block) e closure** — capire come la visibilità e il ciclo di vita delle variabili cambia a seconda di keyword e contesto. ([GitHub][1])
* **Differenza tra funzioni “normali” e arrow-function** — e come influisce su `this`, contesto, `prototype`, comportamento. ([GitHub][1])
* **Conversioni implicite di tipo (type coercion), operatori, truthy/falsy** — come JS converte tipi, quando un’operazione restituisce stringhe, numeri, booleani, e quali valori sono considerati truthy/falsy. ([GitHub][1])
* **Oggetti e primitive, confronto di valori (== vs ===), oggetti per riferimento** — cosa significa che oggetti sono confrontati per riferimento, come funziona l’uguaglianza, e quando hai oggetti vs primitivi. ([GitHub][1])
* **Comportamento di array, metodi di array, Sparse arrays / “empty slots”** — cosa succede quando modifichi array, usi metodi come `map`, `reduce`, o assegni valori oltre la lunghezza attuale. ([GitHub][1])
* **Loop, funzioni asincrone, event loop, callback, setTimeout / setInterval** — come funzionano i loop, le callback, il meccanismo asincrono / ritardi, e il concetto di “queue” / event loop. ([GitHub][1])
* **Template literals, tagged templates, spread operator, rest parameters, destructuring** — comprendere le moderne feature di ES6+ per stringhe, array/oggetti, funzioni, e come manipolare dati in modo flessibile. ([GitHub][1])
* **Prototipi, ereditarietà, classi vs function constructor, proprietà dinamiche, `delete`, `Object.defineProperty`** — come funziona la prototipazione in JS, come creare classi/oggetti, modificare proprietà, e limiti relativi. ([GitHub][1])
* **Generators / iterabili / async-generators / iterazione** — capire cosa sono i generatori, come funzionano gli iteratori, `yield`, `for-of`, `for await … of`, e come gestire valori asincroni. ([GitHub][1])
* **Funzioni di libreria globali / built-in / API del browser (es: localStorage / sessionStorage / JSON / Intl / Set / Map / Symbol / …)** — il comportamento di oggetti e funzioni forniti da JS/ambiente per manipolazione dati, storage, conversioni, formattazioni. ([GitHub][1])
* **Tipizzazione dinamica e `typeof` / differenze tra tipi primitivi & oggetti** — come JS gestisce tipi, cosa restituisce `typeof`, e le implicazioni tra tipi primitivi e oggetti. ([GitHub][1])
