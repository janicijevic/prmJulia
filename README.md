# Instalacija

1. Skinuti Juliju sa [sajta](https://julialang.org/downloads/) 
2. Cekirati __Add Julia to Path__ (Za lakse pokretanje)
3. U Julia REPL ukucati __]add Plots__
4. U Julia REPL ukucati __]add Images__
5. U Julia REPL ukucati __]add ImageFeatures__
6. U Julia REPL ukucati __]add DataFrames__


## VSCode
7. Instalirati ekstenzije __Julia__ i __Jupyter__
8. U Julia REPL ukucati __]add IJulia__


# Napomena

Zbog nacina na koji Julija funkcionise pri prvom pokretanju komande _using <package\>_ treba vremena da se ucita paket i kesira, naredna pokretanja budu brza.

Takodje, slicno se desava za plotovanje, prvo pokretanje _plot(x, y)_ traje malo duze ali svaki sledeci poziv bilo koje funkcije za plotovanje je vrlo brz. Ovaj problem je nazvan _Time to first plot_.