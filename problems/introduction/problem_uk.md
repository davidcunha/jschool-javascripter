Давайте створемо окрему директорію для цього воркшопу, щоб зберігати чистоту в наших файлах.

Запустіть цю команду, щоб створити директорію, яка називатиметься `jschool-javascripter` (або будь-як інакше):

```bash
mkdir jschool-javascripter
```

Перейдіть в директорію `jschool-javascripter` командою:

```bash
cd jschool-javascripter
```

Створіть файл `introduction.js`:

```bash
touch introduction.js
```
 або якщо ви на Windows,

```bash
type NUL > introduction.js
```
 (`type` це частина команди!)

Відкрийте файл у вашому улюбленому текстовому редакторі та додайте цей текст:

```js
console.log('hello');
```
Збережіть файл, а потім перевірте вашу програму запустивши команду:

```bash
jschool-javascripter verify introduction.js
```

До речі, на процязі цього курсу ви можете можете називати файли так, як вам подобається. Якщо ви хочете назвати файл ім’ям `catsAreAwesome.js` для кожної вправи, то зробіть це. Лише не забудьте потім перевірити його:

```bash
jschool-javascripter verify catsAreAwesome.js
```
