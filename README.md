Connect four με AI & βιβλιοθήκη raylib
/Παρακάτω θα παρατέθει μια υλοποίηση του παιχνιδιού Connect Four με τα γραφικά της Raylib και με αντίπαλο τον υπολογιστή βασισμένο στον αλγόριθμο Minmax


Τι θα χρειαστείτε για να τρέξετε το παιχνίδι:
  
   1)"C++ compiler"
  
   2)"Raylib" (βιβλιοθήκη γραφικών παιχνιδιού)

Εγκατάσταση της Raylib σε linux
    >>"sudo apt install libraylib-dev"
Εγκατάσταση σε Windows
   
   1)Κατεβάστε το:"precompiled Raylib για Windows"
   
   2)Προσθέστε τα ".lib" και ".dll" αρχεία στο project σας ή στο path του compiler
Εγκατάσταση σε macOS
   >>brew install raylib

Για την μεταγλώττιση μπορείτε:
    >>g++ main.cpp -o connect4 -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
  Σε windows,μπόρει να χρειαστεί να προσθέσετε:-lwinmm -lgdi32


Για το τρέξιμο του παιχνιδίου
  Αφού κάνετε compile:
    >>"./connect4"


Τρόπος παιχνιδιού
 
  1.Πατήστε SPACE για να ξεκινήσει το παιχνίδι
  
  2.Παίξτε Πέτρα-Ψαλίδι-Χαρτί με κλικ στο ανάλογο κουμπί για να δείτε ποιος ξεκινά
  
  3.Κάντε αριστερό κλικ σε μια στήλη για να ρίξετε το δίσκο σας
  
  4.Πατήστε R για την επανεκκίνηση του παιχνιδιού



Τι ειναί η  Raylib;
   >>Η raylib είναι μια απλή βιβλιοθήκη για τη δημιουργία παιχνιδιών και εφαρμογών με γραφικό περιβάλλον.
   Είναι γραμμένη σε C αλλά χρησιμοποιείται άνετα με C++.Παρέχει υποστηρίξη για:
    *2D & 3D γραφικά
    *Χειρισμό ήχου
    *Είσοδο απο πληκτρολόγιο και ποντίκι
    *Δυνατότητες για animation


AI Λογική
 >>Η τεχνιτή νοημοσύνη χρησιμοποιεί:
    *Mixmax αλγόριθμο για να μπορεί να προβλέπει κινήσεις
    *Alpha-Beta Pruning για να επιταχύνει την αναζήτηση
    *Αξιολόγηση του πίνακα για εντοπισμό θέσεων

 Screenshot-Demo game
  ![image](https://github.com/user-attachments/assets/4c891eca-ff4c-4c61-a05c-b58f6fff66de)
  ![image](https://github.com/user-attachments/assets/e068dbf7-565b-43a4-9b04-cdcacf60fd81)
  ![image](https://github.com/user-attachments/assets/b5879945-5dab-44be-9c4f-26764e1ede08)
  ![image](https://github.com/user-attachments/assets/bb5747c2-dc6c-4513-8988-418b261fc027)
  https://github.com/user-attachments/assets/adac4d2f-0f95-4510-a8cd-7aa1dfa4e20b/αναπραγωγή βίντεο
  



   
