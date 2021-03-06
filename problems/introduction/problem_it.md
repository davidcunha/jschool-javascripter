Per mantenere le cose organizzate, creiamo una cartella per questo workshop.

Esegui questo comando per creare una directory chiamata `jschool-javascripter` (o qualcos'altro a tuo piacere):

```bash
mkdir jschool-javascripter
```

Cambia la directory di lavoro con la directory `jschool-javascripter`:

```bash
cd jschool-javascripter
```

Crea un file dal nome `introduction.js`:

```bash
touch introduction.js
```

oppure, se ti trovi su Windows,
```bash
type NUL > introduction.js
```
(`type` è parte del comando!)

Apri il file nel tuo editor preferito, e aggiungi questo testo:

```js
console.log('hello');
```

Salva il file, quindi verifica che il tuo programma sia corretto eseguendo questo comando:

```bash
jschool-javascripter verify introduction.js
```

Tra parentesi, lungo il corso di questa guida, puoi dare al file con cui stai lavorando il nome che desideri, quindi se vuoi usare un nome di file come `catsAreAwesome.js` per ciascun esercizio, puoi farlo tranquillamente. Assicurati tuttavia di eseguire il file giusto:

```bash
jschool-javascripter verify catsAreAwesome.js
```
