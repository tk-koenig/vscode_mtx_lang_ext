# Bosch Rexroth MTX syntax and highlighting extension 

This VSCode extension recognizes files with the **\*.npg** file extension.
These files are typically NC files for the Bosch Rexroth MTX control.

Thise extension currently includes syntax highlighting and some snippets.

## Syntax hightlighting
The syntax highlighting is automatically detected and activated.

![picture](https://github.com/tk-koenig/vscode_mtx_lang_ext/raw/main/Ressources/img/nc_test_file.PNG)

## Snippets
The following snippets are currently stored:

|prefix|snippet|
|------|-----|
|nc-header-info|;############################################<br>;Progname:<br>;Version:<br>;Date:<br>;Author:<br>;############################################|
|nc-header-no-info|;############################################"<br>;Prog.name:<br>;############################################"|
|for|10 FOR CNT%=1 TO NR_CNT%<br>20 :REM Do something..."<br>30 NEXT CNT%|
|repeat|10 REPEAT<br>20 X=X+1 :REM Repeat until X=100<br>30 UNTIL X=100 :REM Condition TRUE|
|while|10 WHILE {Condition TRUE} DO<br>20 :REM Do something<br>30 END|
|call|;------------------------------------------<br>N1 CALL ;Path of the called program<br>;------------------------------------------|
|if-then-endif|10 IF (TRUE) THEN<br>20 :REM Do something<br>30 ENDIF|
|if-then-else-endif|10 IF (TRUE) THEN<br>20 :REM Do something<br>30 ELSE<br>40 :REM Do something else<br>50 ENDIF|
|...|and some more|

This extension is a **beta-version**.

Further versions will follow!

**Enjoy!**
