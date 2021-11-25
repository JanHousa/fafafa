[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6446654&assignment_repo_type=AssignmentRepo)
# Seznamy v HTML: Gamebook

## Zadání samostatné práce

Vytvořte vlastní (nevelký) Gamebook v HTML. Při jeho tvorbě použijte všechny předepsané prvky, sestavte je do smysluplné podoby.

## Cíle zadání

* Zopakovat tvorbu struktury souborů a složek
* Zopakovat vytváření odkazů mezi nimi
* Zopakovat validaci stránek
* Procvičit použití HTML syntaxe: obrázky, citace, vzorce, zvýrazňování
* Procvičit vytváření víceúrovňových seznamů, seznamů definic
* Zopakovat a procvičit odevzdávání úloh na GitHub
* Vyzkoušet si práci v editoru VS Code a VS Code Online

## Podmínky splnění

* Alespoň **10 herních stránek** - míst hry, každá s popiskem a nadpisem
* Celá hra začíná na stránce */index.html*, tato stránka se počítá mezi herní
* Alespoň **dvouúrovňová struktura** složek
* Alespoň **3 obrázky**
    * max *800px* velikost strany
    * jeden z obrázků v nejhlubší úrovni složek
    * **všechny obrázky uložené** ve složce */images*, každý linkovaný z jiné stránky
* Libovolné téma, ve kterém se vyskytují **dvě postavy** a **tři cizí slova**
    * Postavy jsou zvýrazněné tučně
    * Cizí slova jsou označena a zvýrazněna jako cizí slova
* Všechny stránky **projdou validátorem** na https://validator.w3.org/
* Prvky, které se musí vyskytnout mezi stránkami:
    * **citát** někoho slavného s uvedením autora
    * **vzorec**, ve kterém jsou použity indexy (chemický nebo matematický vzorec)
* Neherní stránka */guide.html*, která **obsahuje stromovou strukturu** všech herních stránek zapsanou jako **víceúrovňový seznam** ul
* Neherní stranka */characters*, která obsahuje seznam postav a autorů (tj. Vás) formátovaný jako **seznam definic**
* Výsledný web bude **uložen na GitHubu** v repozitáři určeném pro tuto úlohu a to **nikoli nahráním souború**, ale commitem a pushem ve VSCode, nebo analogickým způsobem ve VSC Online

## Znalosti

* HTML
    * Prezentace 02-textovéPrvky-seznamy.pptx
    * https://www.w3schools.com/html/default.asp
* GitHub
    * [Jak pracovat s Gitem a GitHubem](https://pslib-cz.github.io/learn-git-and-github/)
* VSCode
    * [Cheatsheet VSCode](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
    * [Cheatsheet Emmet](https://docs.emmet.io/cheat-sheet/)

## Tipy

* Velikost obrázku umí upravit každý bitmapový grafický editor - https://www.photopea.com/
* IMG musí mít atribut ALT
* V seznamu UL i OL může být bezprostředně pouze LI
* IMG nesmí být ihned v BODY, může být ale například v DIV
* VS Code umí generovat kód a je k němu spousta rozšíření