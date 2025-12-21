---
# Tópico: Novidades do Python 3.13
**TIPO:** Linguagem de Programação
**TAGS:** Python 3.13, Linguagem de Programação, Desenvolvimento de Software
**DATA_REF:** 2024

## Núcleo do Conhecimento
* **Lançamento do Python 3.13**
    * **Data de Lançamento:** 7 de outubro de 2024
    * **Recursos:** Interpretador interativo aprimorado, suporte experimental para execução em modo de threads livres, compilador Just-In-Time
* **Melhorias no Interpretador**
    * **Interpretador Interativo:** Melhorias significativas, incluindo suporte a cores e mensagens de erro aprimoradas
    * **Mensagens de Erro:** Realçadas em cores por padrão
* **Biblioteca Padrão**
    * **Adições:** Nova exceção `PythonFinalizationError`, suporte a descontinuar opções de linha de comando, argumentos posicionais e subcomandos no módulo `argparse`
    * **Remoções:** Vários módulos legados removidos após descontinuação no Python 3.11
* **Typing**
    * **Suporte a Type Defaults:** Em type parameters
    * **Type Narrowing Annotation:** `typing.TypeIs`
* **Remoções e Novas Depreciações**
    * **Módulos Removidos:** `aifc`, `audioop`, `chunk`, `cgi`, `cgitb`, `crypt`, `imghdr`, `mailcap`, `msilib`, `nis`, `nntplib`, `ossaudiodev`, `pipes`, `sndhdr`, `spwd`, `sunau`, `telnetlib`, `uu`, `xdrlib`, `lib2to3`
    * **Depreciações:** Várias classes, funções e métodos em módulos da biblioteca padrão

## Controle de Versão do Runtime do Python
* **Habilitação:** Adicionar referência ao pacote de runtime do Python no arquivo `requirements.txt`
* **Comportamento:** Dependendo do valor de versão, o aplicativo pode ser executado na versão mais recente disponível, fixado em uma versão específica ou executado em uma versão padrão

## Outras Alterações e Melhorias
* **Isolamento de Dependência:** Habilitado por padrão para prevenir conflitos de versão
* **Desempenho de Início a Frio:** Redução no tempo de início a frio
* **Tratamento JSON:** Suporte ao uso automático de `Orjson` para serialização e desserialização JSON
* **Aceitação Simplificada para Streaming HTTP:** Melhorias na aceitação de streaming HTTP

## Recursos Removidos
* **Suporte a Funcionalidades:** Vários recursos não têm mais suporte no Python 3.13 e versões posteriores

---
**BLOCO DE NOTAS (ENTRADA BRUTA):** 
* Fonte 1: https://www.clariontech.com/blog/python-3.13-latest-advancement-you-need-to-know-in-2025
* Fonte 2: https://docs.python.org/pt-br/dev/whatsnew/3.13.html
* Fonte 3: https://docs.python.org/pt-br/3/whatsnew/3.13.html
* Fonte 4: https://docs.python.org/3/whatsnew/3.13.html
* Fonte 5: https://www.python.org/downloads/release/python-3130/
* Fonte 6: https://learn.microsoft.com/pt-br/azure/azure-functions/python-313-changes