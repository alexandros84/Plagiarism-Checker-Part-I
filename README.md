# Plagiarism-Checker-Part-I

##### This app is designed to relieve the cognitive load teachers face in their hard task of educating the masses (for example, through the ability of running intraclass cheating checks) and to offer constructive insights in the way students appropriate new knowledge (through the ability for example to compare en mass, primary sources and assignments)

*The goal is to decode the many faces of repetitive patterns in learning.*

To plagiarism checker παίρνει τα assignments μιας τάξης μαθητών σε μορφή string, και συγκρίνει όλα τα πιθανά ζευγάρια εργασιών εντοπίζοντας και μαρκάροντας σε αυτά (με διάφορες κλίμακες ομοιότητας) ακόμα και μερικώς όμοιες προτάσεις (attachment pic_sample_1). Για να συμβεί αυτό κάθε ζευγάρι εργασιών σπάει σε προτάσεις/arrays λέξεων, οι οποίες αποτελούν τα rows and columns ενός μαθηματικού πίνακα. Ο πίνακας κάνει το iteration πολύ εύκολο κ καθώς κάθε index του resultant 2d array εμπεριέχει τη θέση και των δύο προτάσεων είναι πολύ εύκολο να θέσουμε διαφορετικές html/css κλάσεις και διαδραστικά events στο κάθε ζευγάρι προτάσεων κάνοντας τον εντοπισμό του plagiarism παιχνίδι.

##### ** Quick-start: **

* Open the html file and the https://github.com/alexandros84/Plagiarism-Checker-Part-I/blob/master/test%20strings.

* Copy and paste stringA / stringB to the corresponding input boxes.

* Press Submit.

* Hover over red or yellow spans to see their matching pair. 

* Click them to restore their state.

* If the relative positioning of elements does not facilitate easy comparison, double click on any marked span to have its pair pasted on the third div of the screen. 

* Clear the third div's contents by clicking anywhere inside it.
