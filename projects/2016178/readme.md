#Super-Mario,Διονύσιος,Κοντοζίδης,Π2016178

##Παραδοτέο 1
Forked Repository: https://github.com/dionisiskon/hci

Repository(Super-Mario): https://github.com/dionisiskon/Super-Mario 

master:https://dionisiskon.github.io/Super-Mario/

##Παραδοτέο 2

Αρχικά, δημιούργησα μία νέα πίστα με το Tiled map editor χρησιμοποιώντας το ίδιο tileset.Στη συνέχεια χρησιμοποίησα την ζωγραφική των windows για να βάψω τον χαρακτήρα(Μάριο) σε πράσινο(Luigi) ως προσωρινή λύση μέχρι να καταφέρω να κάνω δικό μου sprite sheet χρησιμοποιώντας άλλον χαρακτήρα. Επιπροσθέτως, κατέβασα ένα sprite sheet που περιέχει τα νομίσματα με το spin animation και με το lunapic online editor το προσάρμοσα κατάλληλα για το παιχνίδι(transparent bg,resize image,cropping).Κατέβασα το mario theme song,gameover ήχο για όταν χάνει όλες τις ζωές ο παίκτης ,ήχο για την ολοκλήρωση της πίστας και έκανα μετατροπή σε αυτούς αλλα και στους ήχους που είχαμε διαθέσιμους απο την εργασία για την καλύτερη συμβατότητα με τους περισσότερους δημοφιλείς browsers.Τέλος, πρόσθεσα έναν μετρητή για τα νομίσματα,τα goomba,για τις ζωές αλλα και για τα σκόρ και έθεσα ως στόχο στο παιχνίδι την συλλογή των νομισμάτων για την ολοκλήρωση της πίστας.

Links: www.lunapic.com
       www.google.com/images
       www.itch.io
       node js webserver


##Παραδοτέο 3

Για το τρίτο παραδοτέο χρησιμοποίησα το Adobe Photoshop για να δημιουργήσω κατάλληλα sprites(mario,pyroguys) και να επεκτείνω το tileset που μας παραχωρήθηκε και γενικότερα για ότι άλλες επεξεργασίες ήταν απαραίτητες.Επιπλέον, δημιούργησα εχθρούς(Pyroguys) και τους πρόσθεσα στο παιχνίδι με τις κατάλληλες αλλαγές στον κώδικα για τα collision με τα pipes για teleport και τα λοιπά.Στη συνέχεια, δημιούργησα tile layers στον χάρτη μου για τα pipes για teleport και έκανα αλλαγές στον κώδικα για να αλλάζουν οι συντεταγμένες με αυτά τα tile layers,να πραγματοποιούνται τα απαραίτητα animation και να παίζουν οι ήχοι για το teleport.Αφετέρου χώρισα το παιχνίδι σε states για την χρήση μενου σύμφωνα με τις οδηγίες της εργασίας και "διαμοίρασα" το παιχνίδι ώστε να τρέχει απο δύο scripts(state1,splash) και το κεντρικό αρχείο index.html.Επιπροσθέτως,πρόσθεσα την σημαία στο tileset και έθεσα τα collisions ώστε να εμφανίζουν κατάλληλο μήνυμα όταν "ακουμπάει" ο παίκτης την σημαία.Τέλος χρησιμοποιώντας την καινούρια έκδοση του phaser(2.9.2) πρόσθεσα ένα απλό camera fade animation για να μαυρίζει η οθόνη στην αλλαγή states μεταξύ του παιχνιδιού(state1) και του μενού(splash).

##Παραδοτέο 4 - Tελική Αναφορά

Για το τελευταίο παραδοτέο δημιούργησα μια δεύτερη πίστα χρησιμοποιώντας το tiled map editor και άλλαξα τις functions ώστε να είναι κατάλληλες για το δεύτερο state(state2.js) με την βοήθεια μιας μεταβλητής s στον κώδικα(index.html).Επίσης,άλλαξα τον κεντρικό χαρακτήρα απο τον μάριο στον λουίτζι και αφαίρεσα τον counter που μετρούσε το πλήθος των goomba που σκοτώθηκαν κατα την διάρκεια του παιχνιδιού απο τον χρήστη-παίκτη.Επιπροσθέτως, χρησιμοποιώντας το lightshot screenshot tool και τα google fonts έβγαλα screenshot τα γράμματα για το state1 και state2 και με την βοήθεια του lunapic editor έκανα transparent bg στις φωτογραφίες αυτές.Τέλος,πρόσθεσα τα απαραίτητα κουμπιά στο μένου(splash.js) και έστειλα την πίστα στον φάκελο που ζητούσε ο καθηγητής

Links:
fonts.google.com
www.lunapic.com
node js webserver
phaser examples

Συμπεράσματα:

H εργασία αυτή με βοήθησε να εξοικειωθώ με την βιβλιοθήκη Phaser αλλα και με την γλώσσα προγραμματισμου Javascript όπως επίσης και με την κύρια γλώσσα σήμανσης για τις ιστοσελίδες HTML.Mέσω αυτού,έγινα λίγο πιο γνώριμος με το Video Game Design.
