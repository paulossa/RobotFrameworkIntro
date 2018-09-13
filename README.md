## Projeto exemplo para utilização do RobotFramework 

#### Requisitos 
- Python 2.7 ou 3 - (adicionar /Scripts ao path) ```python --version``` deve mostrar a versão.
- WxPython ~ Dependências do ```RIDE```. 
- ``` pip install robotframework ```
- ``` pip install robotframework-ride``` 
- ``` pip install --upgrade robotframework-seleniumlibrary```


#### Starting

New Project (ProjectName: Project1) -> New Test Suite (SuiteName: TestSuite1) -> (testName: testCase1) Test Case

--- 
1. Clique na visão do suite de testes, na aba de edição,  Clique em **add import** > Library. _(Vermelho indica falha, preto indica sucesso);_ 
2. Add o [driver do selenium](https://www.seleniumhq.org/download/) ao Path (python/scripts) ? 
3. Ir até (TestCase1) add: 
```python 
    Open Browser    https://google.com    Chrome
    Close Browser
```
4. Ir até a aba run na visão de (TestCase1) e clicar no botão 'Start' (deve abrir um navegador na página do google). 
5. Crie um novo teste (Teste2);



Lugares para leitura.

https://github.com/MarkusBernhardt/robotframework-archetype-selenium2library/blob/master/src/main/resources/archetype-resources/src/test/resources/robotframework/testsuites/google.txt


https://github.com/robotframework/HowToWriteGoodTestCases/blob/master/HowToWriteGoodTestCases.rst



https://blog.codecentric.de/en/2010/07/how-to-structure-a-scalable-and-maintainable-acceptance-test-suite/




















--- 

==================
RIDE Keyboard Shortcuts
==================


============  ===========================
*Shortcut*    *What it does*
============  ===========================
Ctrl+S        Save
Ctrl+Shift+S  Save all
Ctrl+O        Open
Ctrl+Shift+O  Open directory
Ctrl+R        Open resource
Ctrl+Shift+R  Refresh directory
Ctrl+N        New project
Ctrl+Shift+N  New resource
Ctrl+Q        Quit RIDE
Alt+X         Go Forward
Alt+Z         Go Back
F6            Open preview
F5            Open search keywords dialog
F8            Run test suite
Ctrl+F8       Stop running test suite
============  ===========================

Grid
----

============  ========================================
*Shortcut*    *What it does*
============  ========================================
Ctrl+Space    Suggestions and auto completion
Ctrl+I        Insert row(s)
Ctrl+D        Delete row(s)
Ctrl+Z        Undo
Ctrl+Y        Redo
Ctrl+3        Comment row(s)
Ctrl+4        Uncomment row(s)
Alt+Up        Move row(s) up
Alt+Down      Move row(s) down
Ctrl+A        Select all
Ctrl+X        Cut (does not remove cells or rows)
Ctrl+C        Copy
Ctrl+V        Paste (does not move cells or rows)
Ctrl+Shift+V  Insert (adds empty rows and pastes data)
Delete        Delete
============  ========================================

Tree view
---------

============  =====================================
*Shortcut*    *What it does*
============  =====================================
Ctrl+Shift+T  Add new test case
Ctrl+Shift+K  Add new keyword
Ctrl+Shift+V  Add new scalar variable
Ctrl+Shift+L  Add new list variable
F2            Rename
Ctrl+Shift+C  Clone/Copy selected keyword/test case
Ctrl+Up       Move item up
Ctrl+Down     Move item down
============  =====================================

