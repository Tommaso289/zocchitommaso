# 🚦 Progetti Arduino - Semaforo

Questo repository contiene una serie di esercizi realizzati con Arduino su Tinkercad.

## 📂 Contenuto

* 🔴 **ledblinkZocchiTommaso**
  LED che lampeggia ogni secondo.

* 🟡 **incrocio4ZocchiTommaso**
  Simulazione di un incrocio con due semafori.

* 🟢 **semaforoZocchiTommaso**
  Semaforo base con sequenza:

  ```
  ROSSO → VERDE → GIALLO
  ```

* 🔵 **semaforoPulsanteZocchiTommaso**
  Semaforo con pulsante pedonale.

---

## ⚙️ Componenti utilizzati

* Arduino UNO
* Breadboard
* LED (rosso, giallo, verde)
* Resistenze (220Ω)
* Pulsante (solo per ultimo esercizio)
* Cavi jumper

---

## 🔌 Collegamenti base

* LED rosso → pin 13
* LED giallo → pin 12
* LED verde → pin 11
* Pulsante → pin 2

---

## 💡 Funzionamento

### 🔴 LED Blink

Il LED si accende e si spegne ogni secondo usando `delay()`.

### 🚦 Semaforo base

Il sistema segue la sequenza:

1. Rosso acceso
2. Verde acceso
3. Giallo acceso

### 🚸 Semaforo con pulsante

* Il verde resta acceso normalmente
* Quando si preme il pulsante:

  * si attiva il giallo
  * poi il rosso per permettere l’attraversamento

### ➕ Incrocio

Due semafori lavorano in alternanza:

* Uno verde mentre l’altro è rosso
* Cambio sincronizzato con giallo

---

## 🧠 Obiettivi didattici

* Uso di `pinMode`, `digitalWrite`, `digitalRead`
* Gestione dei tempi con `delay()`
* Logica dei semafori
* Input da pulsante

---

## 👨‍💻 Autore

**Tommaso Zocchi**

---

## 🛠️ Note

Progetti realizzati su Tinkercad per esercitazione scolastica.
