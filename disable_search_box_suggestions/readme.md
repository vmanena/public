# Jak vypnout vyhledávání na internetu v nabídce Start
Práce s nabídkou Start může být ve Windows 10/11 pomalá, protože při vyhledávání standardně prohledává kromě názvů aplikací a mistně uložených souborů také internet.
## Vypnutí vyhledávánaí

Soubor [disable_websearch.reg](disable_websearch.reg)

Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Explorer]
"DisableSearchBoxSuggestions"=dword:00000001

## Zapnutí vyhledávání
