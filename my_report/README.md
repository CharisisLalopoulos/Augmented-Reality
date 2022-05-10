# Lesson: Interaction Design

### First and Last Name: Charisis Lalopoulos
### University Registration Number: dpsd19064
### GitHub Personal Profile: [CharisisLalopoulos](https://github.com/CharisisLalopoulos)
### Augmented Reality Personal Repository: https://charisislalopoulos.github.io/Augmented-Reality/

# Introduction

# Summary


# 1st Deliverable
Αρχικά ξεκίνησα με την εισαγωγή των υπόλοιπων αντικειμένων στην σκηνή όταν η κάμερα αναγνωρίζει το "hiro" (σφαίρα & κύλινδρος), για τα οπόια βρήκα τον κώδικα στο [A-Frame School](https://aframe.io/aframe-school/#/4/1) > [Glitch](https://glitch.com/~aframe-school-position) . Έπειτα έκανα τις αισθητικές αλλαγές όσων αφορά την θέση, το μέγεθος και τα χρώματα, τους κωδικούς των οποίων πήρα απο το [HTML COLOR CODES](https://htmlcolorcodes.com/) . Στη συνέχεια απο το [A-Frame particle system component](https://www.npmjs.com/package/aframe-particle-system-component) βρήκα τον κώδικα για να προσθέσω το χιόνι στην σκηνή και με τις κατάλληλες αλλαγές, αλλά και με συμπληρωματικό κώδικα απο το [A-Frame particle system component](https://www.npmjs.com/package/aframe-speech-command-component) πρόσθεσα την λειτουργία του speech command, ώστε με την φωνητική εντολή "Start" να ξεκινάει να χιονίζει στην σκηνή, ενώ με την φωνητική εντολή "Stop" να σταματάει. Για να κάνω πιο πυκνό το χιόνι, χρησιμοποίησα κώδικα απο το [A-Frame particle system component](https://aframe.io/aframe-school/#/8) > [Glitch](https://glitch.com/~aframe-school-registry) . Ακόμη για αισθητικούς λόγους, άλλαξα το όνομα της καρτέλας στον browser σε "Marker_Based" . 

***Τέλος έχω κάνει κάποιες αισθητικές αλλαγές στην αρχική σελίδα [index.html](https://charisislalopoulos.github.io/Augmented-Reality/), με τις επιλογές "Marker_Based","Location_Based","Syros_Location_Based", την οποία σκοπεύω να δουλέψω και άλλο μέσα στο εξάμηνο. Έχω χρησιμοποιήσει γνώσεις και ιδέες για την μορφοποίηση της απο την εργασία στο μάθημα της [Πληροφορικής](https://www.syros.aegean.gr/el/spoydes/proptychiakes-spoydes/courses/pliroforiki), του 1ου εξαμήνου του προγράμματος σπουδών του [Τμήματος Μηχανικών Σχεδίασης Προϊόντων & Συστημάτων](https://www.syros.aegean.gr/el) του Πανεπιστημίου Αγαίου. Για τα 'buttons' χρησιμοποίησα κώδικα απο το [W3Schools](https://www.w3schools.com/howto/howto_css_animate_buttons.asp). Τους κωδικούς των χρωμάτων τους πήρα απο το [HTML COLOR CODES](https://htmlcolorcodes.com/) .***

# 2nd Deliverable
Για το δεύτερο deliverable ξεκίνησα δημιουργώντας τα custom Markers (DPSD19064, Hydrogen, Oxygen), χρησιμοποιόντας τις εικόνες που μας δώθηκαν στα assets για τα δύο στοιχεία, ενώ την εικόνα για το DPSD marker την έφτιαξα σε εφαρμογή στο κινητό (*Collage Maker / Photo Editor*). Στην συνέχεια χρησιμοποίησα την ιστοσελίδα [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) για την δημιουργία των markers(*.patt αρχείο και image*). Αρχικά αντιμετώπιζα κάποια προβλήματα με τα custom Markers και δεν μου τα διάβαζε ο local server. Μετά απο αρκετό ψάξιμο στο internet βρήκα βοήθεια σε κάποιες συζητήσεις στο **Github**. Το πρώτο που δοκίμασα ήταν κάτι απο αυτήν την [συζήτηση](https://github.com/jeromeetienne/AR.js/issues/172) και πιο συγκεκριμένα:![](Report_images/ri2.png) > ![](Report_images/ri3.png) Δεν δούλεψε οπότε χρησιμοποίησα κάτι απο αυτήν την [συζήτηση](https://github.com/jeromeetienne/AR.js/issues/164), το οποίο με βοήθησε και δούλεψε για εμένα. ![](Report_images/ri1.png) Για το πρώτο ζητούμενο, για να κάνει display μια εικόνα μου όταν η κάμερα αναγνωρίζει το custom Marker "DPSD19064" χρησιμοποίησα κώδικα απο το [A-Frame_a-image](https://aframe.io/docs/1.3.0/primitives/a-image.html#example). Για το όνομα έφτιαξα ένα *.glb* αρχείο στο [Blender](https://www.blender.org/), για να είναι πιο ωραίο αισθητικά σε σχέση με ένα απλο *text* και χρησιμοποίησα κώδικα για να εμφανίζεται στην οθόνη όταν αναγνωρίζεται το custom Marker απο το [A-Frame-gltf-model](https://aframe.io/docs/1.3.0/components/gltf-model.html#using-animations). 

Για το δεύτερο ζητούμενο, δημιούργησα τα animation για το Hydrogen, το Oxygen και το H2O στο **Blender** παίρνοντας ιδέες απο [αυτό](https://www.youtube.com/watch?v=qTcKajGJyes) και [αυτό](https://www.youtube.com/watch?v=fsdZdAvqpYk) το βίντεο στο YouTube αντίστοιχα.

(Επίσης χρησιμοποίησα πληροφορίες απο [αυτό](https://www.youtube.com/watch?v=UH-zqJ2Jx64) το βίντεο στο YouTube, για να κάνω export τα animation με transparent background, όπως και [αυτή](https://www.mp4compress.com/) την σελίδα για να κάνω downsize τα *.mp4* αρχεία, ώστε να μπορούν να ανέβουν στο Github.)

Για να εμφανίζονται τα animation οταν η κάμερα αναγνωρίζει τα αντίστοιχα markers, χρησιμοποίησα κώδικα απο το [A-Frame_a-video](https://aframe.io/docs/1.3.0/primitives/a-video.html).  

# 3rd Deliverable 


# Conclusions


# Sources
