# twentynineteen-child

Delujoča child tema WP teme Twenty Nineteen.

@localhost - C:\xampp\apps\wordpress\htdocs\wp-content\themes\twentynineteen-child

1. V file explorerju navigiraj na zgornjo povezavo (@localhost) - C:\xampp\apps\wordpress\htdocs\wp-content\themes
2. Ustvari folder z imenom twentynineteen-child - C:\xampp\apps\wordpress\htdocs\wp-content\themes\twentynineteen-child
3. skopiraj style.css in functions.php v ta folder in ju zip-aj.
4. Na wordpress-u naloži novo temo --> uporabi ustvarjen .zip
5. Po želji lahko sedaj editiraš style.css datoteko.

Child temo uporabimo zato, da s kakšno napačno kodo ne uničimo "Parent" teme. V primeru, da se nam to zgodi, lahko enostavno nastavimo parent temo s klikom na gumb Activate v zavihku Themes v WP. Child tema preko functions.php dobi vse podatke parent teme in je ne prepisuje. V tem primeru uporabi style.css od child teme, vse ostalo pa ostane kot je.
