# **Lezione 1: Introduzione al Coding e a Python**

## **Obiettivi della lezione**

Questa prima lezione ha l’obiettivo di introdurre i concetti fondamentali della programmazione, utilizzando Python come linguaggio di riferimento. Gli argomenti trattati saranno:  
- Cos’è un **algoritmo** e come può essere utilizzato per risolvere problemi.  
- Il ruolo dei **linguaggi di programmazione** come strumenti di comunicazione con il computer.  
- La configurazione di un **ambiente di sviluppo**.  
- Le basi della programmazione: **variabili**, **tipi di dati**, **input/output**.  
- I concetti fondamentali di **condizionali** e **cicli**, utili per costruire programmi più complessi.  
- Introduzione a **liste** e **dizionari** per gestire collezioni di dati.

---

## **Cos’è un algoritmo?**

Un algoritmo è una sequenza ordinata di istruzioni progettata per risolvere un problema specifico. Consideriamo un esempio: un robot deve piantare semi in un campo rettangolare.

### **Passi:**
1. Inizia in uno degli angoli del campo, rivolto verso destra.  
2. Pianta un seme nel punto in cui ti trovi.  
3. Avanza di un passo verso destra.  
4. Se raggiungi il bordo del campo:
   - Svolta a sinistra e fai un passo avanti.  
   - Cambia direzione per muoverti verso sinistra.  
5. Se raggiungi il bordo opposto:
   - Svolta a destra e fai un passo avanti.  
   - Cambia direzione per muoverti verso destra.  
6. Ripeti i passi 2-5 finché non hai coperto l’intero campo con i semi.  

### **Perché è un algoritmo?**
- **Risolve un problema specifico**: coprire l’intero campo con semi.  
- **Sequenza chiara e ordinata**: ogni passo è definito con precisione.  
- **Generalizzabile**: può essere adattato per campi di dimensioni diverse o per altre attività (es. irrigazione).  

---

## **Linguaggi di programmazione: il ponte tra umani e computer**

I linguaggi di programmazione traducono le istruzioni umane in un formato comprensibile per i computer.  

Perché scegliere **Python**?  
- **Semplicità**: sintassi chiara, adatta ai principianti.  
- **Potenza**: utilizzabile in numerosi ambiti (scientifico, web, automazione).  

---

## **Ambiente di sviluppo: GitHub Codespaces**

Per questo corso, utilizzeremo **GitHub Codespaces**, che offre un ambiente Python preconfigurato.  

### **Configurazione**  
1. Accedi a [github.com](https://github.com).  
2. Forka il [repository del corso](github.com/bluephlavio/coding).  
3. Crea un nuovo Codespace selezionando **Code** > **Codespaces** > **Create Codespace**.

---

## **Primo programma in Python: il classico “Hello World!”**

```python  
print("Hello World!")  
```

Questo semplice programma mostra un messaggio nel terminale. Salvare il file con estensione `.py` ed eseguirlo con:  

```bash  
python hello_world.py  
```

---

## **Basi della programmazione**

### **Variabili e tipi di dati**

In Python, una variabile memorizza un valore:  

```python  
name = "Alice"  # stringa  
age = 18        # intero  
```  

Tipi di dati comuni:  
- **int**: numeri interi.  
- **float**: numeri decimali.  
- **str**: stringhe di testo.  
- **bool**: valori booleani (`True`, `False`).  

---

### **Input e output**

Python permette di interagire con l’utente:  

```python  
name = input("Inserisci il tuo nome: ")  
print("Ciao, " + name + "!")  
```

---

### **Operatori**

Gli operatori permettono operazioni su variabili e valori:  

- **Aritmetici**: `+`, `-`, `*`, `/`, `%`.  
- **Relazionali**: `==`, `!=`, `<`, `>`.  
- **Logici**: `and`, `or`, `not`.

---

## **Condizionali: prendere decisioni**

I condizionali permettono di eseguire azioni diverse in base a condizioni.  

```python  
age = int(input("Inserisci la tua età: "))  

if age < 18:  
    print("Sei minorenne.")  
elif age == 18:  
    print("Hai appena compiuto 18 anni!")  
else:  
    print("Sei maggiorenne.")  
```

---

## **Cicli iterativi: ripetere azioni**

I cicli permettono di eseguire un blocco di codice più volte.  

### **Ciclo `for`**  

```python  
for i in range(5):  
    print("Questo è il ciclo numero", i)  
```

### **Ciclo `while`**  

```python  
x = 0  
while x < 5:  
    print("x è:", x)  
    x += 1  
```

---

## **Liste: collezioni ordinate di dati**

Una lista è una struttura dati che contiene una sequenza di elementi.  

### **Creazione e accesso**  

```python  
numbers = [1, 2, 3, 4, 5]  
print(numbers[0])  # Output: 1  
```

### **Operazioni comuni**  
- Aggiungere elementi: `numbers.append(6)`.  
- Modificare elementi: `numbers[2] = 10`.  
- Rimuovere elementi: `numbers.remove(3)`.  
- Iterare su una lista:  

```python  
for num in numbers:  
    print(num)  
```

---

## **Dizionari: collezioni di coppie chiave-valore**

I dizionari memorizzano dati con chiavi uniche associate a valori.  

### **Creazione e accesso**  

```python  
student = {"name": "Alice", "age": 18, "class": "4A"}  
print(student["name"])  # Output: Alice  
```

### **Modifica e aggiunta**  

```python  
student["age"] = 19  
student["grade"] = "A"  
```

---

## **Conclusione**  

Abbiamo introdotto i concetti fondamentali della programmazione con Python: variabili, input/output, condizionali, cicli, liste e dizionari. Questi elementi costituiscono le basi per scrivere programmi complessi.

