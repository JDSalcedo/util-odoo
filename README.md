# base_module
Utilitarios para el Odoo ERP

usage:

odoo-bin scaffold [-h] [-t TEMPLATE] name [dest]

Ejemplo(Con un entorno virtual 'venv'):
---------------------------------------
..\venv\Scripts\python3.exe ..\odoo\odoo-bin scaffold --template=base_module factiva_facturactiva_custom ..\odoo-facturactiva\

# vscode_conf
Configuraciones para el IDE VSCode pueda realizar debug a Odoo ERP.

- Se utiliza un entorno virtual de python3.6, declarado en el archivo settings.json.
- Tiene configuraciones para usar linters, pydocstyle que ayuda a escribir código con convenciones del PEP8 para Python.