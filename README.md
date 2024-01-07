-QuickNote: Bohužel framework má moc souborů, takže když stahujete z githubu, tak se musíte proklikat několika zipama. Program bohužel musíte spustit na localhost, protože u AWS mám problém s úložištěm a digital ocean mi zakázal přístup k účtu.
# ProjektWAPololetni
programy potřebné ke spuštění:
RestApi bylo vytvořeno pomocí ratchet framework v PHP s xampp. Využívá apache a mysql.

----------------------------
programy použité při vytváření: 

https://www.jetbrains.com/phpstorm/ (popřípadě vaše volba jiného kódovacího programu) https://www.apachefriends.org/index.html
http://socketo.me/
----------------------------
spuštění na localhost:

1. stažený rozbalený soubor vložíte do složky xampp\htdocs
2. druhý soubor register vložíte do složky xampp\mysql\data
3. Soubor zkouska si otevřete v kódovacím programu
4. Zapněte si xampp control panel a spusťte apache a mysql
5. do terminálu v kódovacím programu vložte tento příkaz: php server.php
6. Poté otevřete Register.php a zaregistrujte se a poté pro ověření přihlašte
7. Vytvořte místnost a můžete v ní komunikovat

-----------------------
Popis Aplikace:
Aplikace je online chat, kde můžete vytvářet místnosti a komunikovat s ostatními. Lze zamítnout přístup osobám. Tuto možnost máte při vytvoření místnosti.


------------------------------------------------

RestApi není, protože mi nešel nainstalovat slim framwork a nebyl čas hledat problém z důvodu ostatních projektů.

------------------------
Websocket se zde používá pro implementaci chatovacího serveru. Umožňuje chatování v reálném čase a okamžité přenosy informací. Vytváří připojení k serveru, který běží na portu 8080. Poté otevře spojení a komunikuje se serverem a posílá si informace. Informace ze serveru přijímá data v JSON a zpracuje je. 

