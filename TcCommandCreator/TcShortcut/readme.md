# TcShortcut  
``` php
$command_name := "em_TcCommandCreator-shorcut-test"
        .create()                              ; 1. create command
        .shortcut("shift", "alt", "0")         ; 2. create shotrcut
        .shortcut("shift", "alt", "win", "f3") ; 2. create another shotrcut
        .shortcut()                            ; 3. get TcShortcut object
        .delete()                              ; 4. delete last shortcut
```  