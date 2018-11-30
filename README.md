# bash_radio_gr

![alt text](https://i.imgur.com/18Bp9pcl.png)

Ένα απλό bash script για να παίζετε τους αγαπημένους σας σταθμούς στο τερματικό. Απλά προσθέτε το όνομα και το URL του σταθμού στο ```gr_stations.txt``` όπου κάθε γραμμή πρέπει να είναι της μορφής 

```Όνομα σταθμού,URL_σταθμού```

Κατόπιν κάνετε εκτελέσιμο το ```radio.sh``` με ```chmod +x radio.sh``` στον  φάκελο όπου το έχετε αποθηκεύσει

Εξ'ορισμού το script αν δε δωθεί όρισμα στο τερματικό ανοίγει τη λίστα με τους σταθμούς που είναι αποθηκευμένοι στο ```gr_stations.txt```. Αλλιώς μπορείτε να φορτώσετε το δικό σας αρχείο δίνοντας στο τερματικό 
```./bash_radio_gr όνομα_αρχείου.txt```

Απαιτείται το πακέτο ```mplayer``` ή το ```mpv``` για να δουλεψει

Σε κάποιες διανομές δίνεται κατευθείαν είτε το ```mplayer``` είτε το ```mpv``` στα αποθετήριά τους, οπότε καλό είναι να το ελέγξετε πρώτα

Εξ'ορισμού το script αν δε δωθεί όρισμα στο τερματικό ανοίγει τη λίστα με τους σταθμούς που είναι αποθηκευμένοι στο ```gr_stations.txt```. Αλλιώς μπορείτε να φορτώσετε το δικό σας αρχείο δίνοντας στο τερματικό 
```./bash_radio_gr όνομα_αρχείου.txt```

Απαιτείται το πακέτο ```mplayer``` ή το ```mpv``` για να δουλεψει

Σε κάποιες διανομές δίνεται κατευθείαν είτε το ```mplayer``` είτε το ```mpv``` στα αποθετήριά τους, αν υπάρχει έστω το ένα από τα 2 πακέτα το script θα τρέξει κανονικά
>>>>>>> master

## Σε Debian based διανομές
```sudo apt install mplayer``` (από το Debian Multimedia repository https://deb-multimedia.org) ή ```sudo apt install mpv```

## Σε Arch based διανομές
```sudo pacman -S mplayer``` ή ```sudo pacman -S mpv```

## Σε Fedora based διανομές
```sudo dnf -y install mplayer``` ή ```sudo dnf -y install mpv```

## Σε OpenSuse Linux
```sudo zypper in mplayer``` ή ```sudo zypper in mpv```

## Σε CentOS Linux (από το nux-desktop repository)
```yum -y install epel-release && rpm -Uvh http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-5.el7.nux.noarch.rpm```

```sudo yum -y install mplayer``` ή ```sudo yum -y install mpv```

## Σε FreeBSD Unix
```sudo pkg install mplayer``` ή ```sudo pkg install mpv```
