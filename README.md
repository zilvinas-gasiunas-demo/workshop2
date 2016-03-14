Workshop pasiruošimo instrukcija
===================


Pateikiama bendra instrukcija ir nuorodos reikalingos parsisiųsti reikiamą programinę įrangą iš interneto ir paruošti kompiuterį darbui.

----------
- Iš https://www.apachefriends.org/download.html parsisiunčiame ir įdiegiame xampp. 
> Naudoti 5.5.33 / PHP 5.5.33 versiją.
- Per xampp valdymo skydą paleidžiame Apache ir Mysql. Užtenka paspausti start, jokių konfigūracijų nereikia. **Pasitaiko nesuderinamumų su skype programa, todėl paleidimo metu skype gali tekti išjungti**
> Po instaliacijos terminale (cmd.exe) įrašius 'php -v' išves versijos numerį. **Ši komanda turi veikti**

- Iš https://getcomposer.org/download/ arba https://getcomposer.org/Composer-Setup.exe parsisiunčiame ir įdiegiame composer. 
> - Instaliacijos metu  "Shell menus" pasirenkame "Do not install Shell Menus"
> - Standartiškai php.exe failo vieta yra "C:\xampp\php\php.exe", nebent XAMPP instaliacijos metu nurodyta kitaip.
> - Po instaliacijos terminale įrašius 'composer -V' išves versijos numerį. **Ši komanda turi veikti**.

- Diegiame symfony
> - Terminale pereiname į xampp direktoriją 'cd c:\xampp\htdocs'.
> - Atsisiunčiame instaliacinį failą per terminalą: 
> 'php -r "readfile('https://symfony.com/installer');" > symfony' 
> - Terminale įvesdami komandą sukuriame naują projektą norimu pavadinimu, pvz "workshop":
> 'php symfony new workshop'
> Atidarius naršyklę adresu http://localhost/workshop/web/ turite matyti standartinį symfony langą.

