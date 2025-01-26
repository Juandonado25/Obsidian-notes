<Badit's level passwords:

ssh command: ssh bandit#@bandit.labs.overthewire.org -p 2220

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

level 0: bandit0
- cat readme

level 1: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
- cd ..
- cd bandit0
- cat readme

level 2: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
- cat ./- 
- **nota:** el archivo se llama "-", esto causa problemas al usar el comando cat, para soluconarlo se debe usar cat ./-, de esta manera cat no queda esperando que se ingrese texto y muestra el contenido del archivo.

level 3: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
- cat spaces\ in\ this\ filename

level 4: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
- cat ...Hiding-From-You

level 5: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
- cat ./-file07

level 6: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
- find . -type f -size 1033c
- **nota:** Busca recursivamente en todo los directorios a partir de el punto de partida indicado, en este caso ".", ademas con "-type f" solo nos mostrará archivos y con "-size 1033c" solo mostrará los que pesen 1033 bytes.

level 7: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
- find ../.. -type f -size 33c -user bandit7 -group bandit6 2>/dev/null

level 8: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
- cat data.txt | grep "millionth"
