# Perceptron-2D-and-3D-in-Octave

# Perceptron Classification (2D & 3D)

## Περιγραφή
Αυτό το έργο περιλαμβάνει την υλοποίηση ενός **Perceptron** μονής στρώσης σε **2D και 3D**, το οποίο ταξινομεί δύο κατηγορίες δεδομένων και εμφανίζει τον διαχωρισμό τους γραφικά.

## 2D Perceptron
### Περιγραφή
Ο αλγόριθμος δημιουργεί **40 σημεία** (20 για κάθε κλάση) και εκπαιδεύει ένα perceptron για να μάθει έναν γραμμικό διαχωρισμό μεταξύ των δύο κλάσεων.  
Η έξοδος είναι ένα **διάγραμμα** όπου:
- Τα δεδομένα της πρώτης κλάσης συμβολίζονται με **"o" (κόκκινο)**
- Τα δεδομένα της δεύτερης με **"+" (μπλε)**
- Η διαχωριστική γραμμή απεικονίζεται ως **μαύρη γραμμή**

### Βήματα
1. **Δημιουργία δεδομένων**  
   - Τα σημεία της πρώτης κλάσης είναι στο εύρος (1,1) - (5,5).  
   - Τα σημεία της δεύτερης κλάσης είναι στο εύρος (6,6) - (10,10).  
   - Τα δεδομένα περιλαμβάνουν **bias (1 στη θέση x0).**  
2. **Εκπαίδευση του perceptron**  
   - Τα βάρη αρχικοποιούνται σε **0**.  
   - Εκτελούνται **500 εποχές** ώστε το perceptron να μάθει τον διαχωρισμό.  
   - Για κάθε σημείο, αν η πρόβλεψη είναι λανθασμένη, τα βάρη ενημερώνονται.  
3. **Οπτικοποίηση**  
   - Τα σημεία σχεδιάζονται σε ένα γράφημα.  
   - Η διαχωριστική γραμμή υπολογίζεται από τα τελικά βάρη.  

## 3D Perceptron
### Περιγραφή
Η υλοποίηση αυτή επεκτείνει το **2D Perceptron** σε **3D**, ώστε να διαχωρίζει τα δεδομένα σε τρεις διαστάσεις. Το αποτέλεσμα είναι ένας **επίπεδος διαχωρισμός** αντί για μια γραμμή.

### Βήματα
1. **Δημιουργία δεδομένων**  
   - Τα σημεία της πρώτης κλάσης είναι στο εύρος (1,1,1) - (5,5,5).  
   - Τα σημεία της δεύτερης κλάσης είναι στο εύρος (6,6,6) - (10,10,10).  
2. **Εκπαίδευση του perceptron**  
   - Αρχικοποίηση βαρών σε **0**.  
   - Εκτέλεση **500 εποχών**.  
   - Προσαρμογή των βαρών αν η πρόβλεψη είναι λανθασμένη.  
3. **Οπτικοποίηση**  
   - Σχεδίαση των σημείων σε 3D διάγραμμα.  
   - Σχεδίαση του επιπέδου διαχωρισμού.  

---
✏️ *Δημιουργήθηκε για εκπαίδευση και επίδειξη του perceptron!* 🚀

