[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Feffie375.github.io%2FTPTE-AEGEAN&count_bg=%23E3802B&title_bg=%2307359E&icon=internetarchive.svg&icon_color=%23E7E7E7&title=%CE%A0%CF%81%CE%BF%CE%B2%CE%BF%CE%BB%CE%AD%CF%82&edge_flat=false)](https://hits.seeyoufarm.com)

# Εργασία Ενδιάμεσης Εξέτασης

## Ανάπτυξη ιστοσελίδας με χρήση HTML

### Περιγραφή

Δημιουργείστε ιστοσελίδα με πολιτιστικό περιεχόμενο ενσωματώνοντας με iFrame

- Βίντεο από το YouTube (360ο ή απλό),  
- 360ο φωτογραφία από το Momento360.com (δική σας ή άλλη)
- Χάρτη της Google (με τοποθεσία σχετική με το θέμα/περιεχόμενο)

Στην αρχή της σελίδας να υπάρχει μενού με τις εξής επιλογές:

- Περιγραφή  
- 360o video από το YouTube  
- 360o photo από το Momento360.com 
- Google map (η πόλη μου)  

Κάθε επιλογή να συνδέεται με αντίστοιχο σημείο της σελίδας που εμφανίζεται το περιεχόμενο.

Στο κάτω μέρος της σελίδας να υπάρχει υπερσύνδεσμος που συνδέεται με την αρχή (πάνω μέρος) της σελίδας (top).

Στον τίτλο της σελίδας (`<title>`) να αναφέρει «Πρόοδος 2021, Τεχνολογίες Διαδικτύου».

Με επικεφαλίδα `<h1>` στην αρχή της σελίδας να αναφέρει το όνομά σας και τον ΑΜ.

### Βαθμολόγηση

- Μενού επιλογών: **3**
- Ενσωμάτωση video από το ΥοuTube: **2**
- Ενσωμάτωση εικόνας από το Momento360.com: **2**
- Ενσωμάτωση χάρτη από Google maps: **2**
- Σύνδεση υποσέλιδου (footer) με την αρχή της σελίδας (top): **1**

### Παραδοτέα

Στο eClass, θα υποβληθεί .html ή .zip αρχείο της μορφής **«επίθετο.html»** ή **«επίθετο.zip»**.

### Ενδεικτική υλοποίηση

```html
<!DOCTYPE html>

<html lang="el">
    <head>
    <meta charset="UTF-8">
        <title>Πρόοδος 2021, Τεχνολογίες Διαδικτύου</title>
    <style>
        body {background-color: #f8e9d5;}
    </style>
    </head>
    <body>
        <h1 id="top">Ευστρατία Καζή, 1312020044</h1>
        <a href="#desc">Περιγραφή Ακρόπολης</a>
        <br>
        <a href="#video">360&deg; video από την Ακρόπολη</a>
        <br>
        <a href="#photo">360&deg; photo από την Ακρόπολη</a>
        <br>
        <a href="#map">Google map (Ακρόπολη Αθήνας)</a>

        <h2 id="desc">Περιγραφή Ακρόπολης</h2>
        <p>H εργασία μου με θέμα "Η Ακρόπολη της Αθήνας". Η Ακρόπολη της Αθήνας αφορά έναν βραχώδη λόφο ύψους 156 μ. 
        από την επιφάνεια της θάλασσας και 70 μ. περίπου από το επίπεδο της πόλεως των Αθηνών. Η κορυφή του 
        έχει σχήμα τραπεζοειδές μήκους 300 μ. και μέγιστου πλάτους 150 μ. Ο λόφος είναι απρόσιτος απ’ όλες τις 
        πλευρές εκτός της δυτικής, όπου και βρίσκεται η οχυρή είσοδος, η διακοσμημένη με τα λαμπρά Προπύλαια.</p>
        <hr>

        <h2 id="video">360&deg; video από την Ακρόπολη</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/TFZu-9igt1o" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <hr>
        <h2 id="photo">360&deg; photo από την Ακρόπολη</h2>
        <iframe width="560" height="315" src="https://momento360.com/e/u/877f5f09bc6944e7bc253f6ebb88987f?utm_campaign=embed&utm_source=other&heading=53.1&pitch=-14.7&field-of-view=75&size=medium"></iframe>
        <hr>
        <h2 id="map">Google map (Ακρόπολη Αθήνας)</h2>
        <iframe width="560" height="315" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2690.6541413104646!2d23.72356051481573!3d37.97153650858848!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14a1bd1837f5acf3%3A0x5c97c042f5eb0df6!2zzpHOus-Bz4zPgM6_zrvOtyDOkc64zrfOvc-Ozr0!5e1!3m2!1sel!2sgr!4v1616070967555!5m2!1sel!2sgr" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        <br>
        <a href="#top">Επιστροφή στην αρχή(top)</a>
        <hr>

        <footer>
            <address>
                <p>Copyright &copy; <script>document.write(new Date().getFullYear())</script> <a href="mailto:ct20044@ct.aegean.gr">Efstratia Kazi</a> All Rights Reserved</p>			
            </address>
        </footer>
    </body>
</html>
```
