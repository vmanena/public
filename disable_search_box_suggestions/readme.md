# Jak vypnout vyhledávání na internetu v nabídce Start
Práce s nabídkou Start může být ve Windows 10/11 pomalá, protože při vyhledávání standardně prohledává kromě názvů aplikací a souborů také internet. Když toto chováni vypnete, nabídka Start se zrychlí a navíc bude přehlednější. 

Toto chování lze změnit pomocí klíče v registru. Níže jsou dva soubory, pomoci kterých můžete prohledávání internetu vypnout/zapnout. Stačí je stáhnout a dvojitým kliknutím na soubor změnit nastavení. 

## Vypnutí vyhledávání

Soubor [disable_websearch.reg](disable_websearch.reg)
    
    Windows Registry Editor Version 5.00
    
    [HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer]
    "DisableSearchBoxSuggestions"=dword:00000001

## Zapnutí vyhledávání
Soubor [enable_websearch.reg](enable_websearch.reg)

    Windows Registry Editor Version 5.00
    
    [HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer]
    "DisableSearchBoxSuggestions"=-
