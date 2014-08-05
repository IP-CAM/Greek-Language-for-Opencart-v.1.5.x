Ελληνική Μετάφραση του OpenCart
===============================

Η παρούσα μετάφραση αφορά την έκδοση 1.5.6 του OpenCart και μόνο για catalog (όχι για το admin interface).
  
Εγκατάσταση
-----------
1. Αντιγράψτε τους φακέλους 'catalog' και 'admin' μέσα στην εγκατάσταση OpenCart που έχετε.
2. Φροντίστε ο φάκελος να έχει - όπως και τα περιεχόμενά του - τα κατάλληλα permissions όπως αναγράφονται στο εγχειρίδιο του OpenCart.
3. Εισέλθετε στο administration του OpenCart, μεταβείτε στο μενού System > Localization > Languages.
4. Εισάγετε μια νέα γλώσσα με τις εξής παραμέτρους:  
  Language Name: Greek  
  Code: gr  
  Locale: el_GR.UTF-8,greek  
  Image: gr.png  
  Directory: greek  
  Filename: greek  
  Status: Enabled  
  Sort Order: 2 (ή όποιο άλλο διαθέσιμο αριθμό έχετε, αν π.χ. θα είναι μόνο τα Ελληνικά βάλτε 1)
5. Πατήστε Save και η γλώσσα έχει εγκατασταθεί.

  Εισέλθετε κανονικά στο κατάστημά σας και αλλάξτε τη γλώσσα στα Ελληνικά από το εικονίδιο στο πάνω μέρος της οθόνης. Περιηγηθείτε στο κατάστημα και ελέγξτε ότι όλα τα κείμενα εμφανίζονται σωστά. Αφού ελέγξετε το κατάστημά σας, μπορείτε να προεπιλέξετε τα Ελληνικά σαν γλώσσα.

FAQ
---
* Q: Αφού η παρούσα μετάφραση είναι μόνο για catalog, γιατί προσθέτει αρχεία στο `admin` directory;

A: Το OpenCart 1.5.6 φαίνεται ότι για κάποια email που αποστέλλονται στον πελάτη, όπως status update της παραγγελίας, αντί να χρησιμοποιεί αρχεία από το `catalog/language/greek` ψάχνει για αρχεία στο `admin/language/greek`. Επομένως, έχω αντιγράψει όλο το `admin/language/english` από τη default εγκατάσταση στο `admin/language/greek` και μετέφρασα μόνο κάποια αρχεία που αφορούν email που πάνε στον πελάτη. Ίσως υπάρχει καλύτερος τρόπος να διορθωθεί αυτό αλλά, προς το παρόν, λειτουργεί.

* Q: Υπάρχον σχέδια για μετάφραση του administration interface;

A: Όχι. Προσωπικά το προτιμώ στα Αγγλικά οπότε δεν με ενδιαφέρει να μπω στον κόπο να το μεταφράσω. Ωστόσο, αν κάποιος ενδιαφέρεται και μπει στο κόπο, ευχαρίστως να το συμπεριλάβω στο παρόν project.

Άδεια Χρήσης
------------
  Η παρούσα μετάφραση διέπεται από τους όρους χρήσης της άδειας  GPL v3.

  Το project βρίσκεται στο github στη διεύθυνση:
  https://github.com/lathan/opencart-greek  
  Οποιεσδήποτε διορθώσεις, παρατηρήσεις, σχόλια και pull requests είναι καλοδεχούμενα.


  Καλές πωλήσεις :)
