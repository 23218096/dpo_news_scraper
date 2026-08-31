To create exe file:
1. open terminal in program folder
2. In terminal, run ```pip install pyinstaller```
3.In terminal, run ``` pyinstaller -F -w app.py --name NewsScraper --hidden-import=openpyxl --hidden-import=openpyxl.cell._writer ```
