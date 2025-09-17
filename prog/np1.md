# NP1

## <mark style="background-color:$primary;">Les bases de JAVA</mark>

### Rappel des bases déjà vu

<pre class="language-java"><code class="lang-java">/* Variable */
int i = 1;
float f = 5.9;
char c = 'A';
// Autres...

/* Structure */
class MyApp {
 public static void main(String[] args) { }
}
//Package et Classes
package myapplication.mylibrary;
<strong>
</strong><strong>public class MyClass { }
</strong>
/* Méthode */
public static type_retour nom_méthode(params) {
// …
}

/* Conditions */
if (i == 3) { doSomething(); }
else if (i == 2) { doSomethingElse(); }
else { doSomethingDifferent(); }

switch (ch) {
 case 'A':
 doSomething();
 break;
 case 'B':
 case 'C':
 doSomethingElse();
 break;
 default:
 doSomethingDifferent();
 break;
}

int a = 1;
int b = 2;
int minVal = (a &#x3C; b) ? a : b;

/* Boucles */
while (i &#x3C; 10) { doSomething(); }
do { doSomething(); } while (i &#x3C; 10);
//break : quitter la boucle
//continue : sauter une itération
for (int i = 0; i &#x3C; 10; i++) { doSomething(); }
for (int i = 0, j = 9; i &#x3C; 10; i++, j -= 3) {
doSomething(); }
for (int i : intArray) { doSomething(i); }

/* Sauts */
outerloop:
for (int i = 0; i &#x3C; 10; i++) {
while (true) {
break outerloop;
<strong> }
</strong>}
char ch;
while (ch = getChar()) {
 if (ch == ' ') {
 continue;
 }
 doSomething();
}
void doSomething(boolean streamClosed) {
 if (streamClosed) {
 return;
 }
 readFromStream();
}
int calculateSum(int a, int b) {
 int result = a + b;
 return result;
}
static int sum(int n) {
 if (n &#x3C; 0) return;
 int sum = 0;
 for (int i = 0; i &#x3C; n; i++)
 sum = sum + i;
 return sum;
}
void doSomething(boolean streamClosed) {
 try {
 if (streamClosed) {
 return;
 }
 readFromStream();
 } finally {
 freeResources();
 }
}

// Void = rien renvoyé

</code></pre>

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

