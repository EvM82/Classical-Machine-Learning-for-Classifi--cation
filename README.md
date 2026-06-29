# Classical-Machine-Learning-for-Classification
Εξετάζονται τεχνικές μείωσης διαστάσεων, ομαδοποίησης και ταξινόμησης σε σύνολα δεδομένων εικόνων, χρησιμοποιώντας τα CIFAR-10 και PC Parts.

Οι μέθοδοι Spectral Embedding, Locally Linear Embedding (LLE) και Isomap συνδυάζονται με Spectral Clustering και αξιολογούνται με τις μετρικές ARI, NMI και accuracy στο test set μέσω nearest-centroid ταξινόμησης. Το Isomap πέτυχε τα καλύτερα αποτελέσματα ομαδοποίησης, με 22,03% accuracy στο CIFAR-10 και 36,87% στο PC Parts.

Επιπλέον, εξετάζεται ένα pipeline ταξινόμησης που συνδυάζει Kernel PCA, Linear Discriminant Analysis (LDA) και Nearest Centroid Classifier. Δοκιμάζονται γραμμικός, πολυωνυμικός και RBF πυρήνας με διαφορετικούς αριθμούς συνιστωσών, ενώ τα αποτελέσματα συγκρίνονται με SVM, k-NN και αυτόνομο Nearest Centroid Classifier. Οι πολυωνυμικοί και RBF πυρήνες παρουσίασαν γενικά καλύτερη απόδοση από τον γραμμικό, υποδεικνύοντας ότι τα δεδομένα δεν είναι γραμμικά διαχωρίσιμα. Το pipeline KPCA–LDA πέτυχε ανταγωνιστική απόδοση, εμφάνισε μικρότερη υπερπροσαρμογή και απαιτούσε σημαντικά μικρότερο χρόνο εκτέλεσης σε σχέση με τα SVM μοντέλα.

