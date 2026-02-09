Esse SDK foi feito em uma versão do python antiga sendo obrigado a instalar o python 2.7
Python 2.7 https://www.python.org/downloads/release/python-2718/
Pynaoqi https://www.maxtronics.com/en/support/kb/softwares/downloads-softwares/nao6-software-downloads/

No windows:
Instale e descompacte de modo que teremos duas pastas no disco principal
C:\python27\
C:\pynaoqi\

Verifique qual a versão que está instalada na máquina:
```
python --version
```
Se não for a 2.7 crie uma venv e defina as variáveis de ambiente.

Importar a biblioteca:
1. Adicione o diretório das DLLs do NAOqi ao PATH
```
set PATH=%PATH%;C:\pynaoqi\bin
```
2. Adicione o diretório principal do módulo Python ao PYTHONPATH
```
set PYTHONPATH=%PYTHONPATH%;C:\pynaoqi\lib\
```
