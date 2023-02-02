# prmJulia

Ovaj repozitorijum sadrzi zadatke urađene kao deo semestralnog rada iz predmeta _Praktikum iz Računarskih alata u Matematici_.

Tema semestralnog rada je programski jezik _Julia_.

## Zadaci
1. `linReg.ipynb` - demonstracija linearne i kvadratne regresije nad generisanim podacima korišćenjem _Metode najmanjih kvadrata_
1. `kockice.ipynb` - nasumično izabrana slika kockice se obrađuje na jedan od dva data načina kako bi se odredio broj koji je prikazan


# Instalacija i pokretanje
1. Skinuti Juliju sa [sajta](https://julialang.org/downloads/) 
1. Cekirati __Add Julia to Path__ (Za lakse pokretanje iz komandne linije)
1. U Julia REPL ukucati `]add Plots`
1. U Julia REPL ukucati `]add Image`
1. U Julia REPL ukucati `]add ImageFeatures`
1. U Julia REPL ukucati `]add ImageFiltering`
1. U Julia REPL ukucati `]add IJulia` (za vscode ili jupyter)

## Jupyter
1. Najlaksi nacin za instalaciju Jupyter-a jeste instalacija [Anaconda](https://www.anaconda.com/products/distribution) distribucije
1. Iz _Anaconda Navigator_ pokrenuti __Jupyter notebook__
1. Otvoriti fajlove _linReg.ipynb_ ili _kockice.ipynb_

## Visual Strudio Code
1. Za rad sa julijom u jupyter fajlovima potrebno je instalirati ekstenzije __Julia__ i __Jupyter__
1. Otvoriti fajlove _linReg.ipynb_ ili _kockice.ipynb_



# Napomena
Zbog nacina na koji Julija funkcionise pri prvom pokretanju komande _using <package\>_ treba vremena da se ucita paket i kesira. Naredna pokretanja budu brza.

Takodje, slicno se desava za plotovanje, prvo pokretanje _plot(x, y)_ traje malo duze ali svaki sledeci poziv bilo koje funkcije za plotovanje je vrlo brz. Ovaj problem se naziva _Time to first plot_.