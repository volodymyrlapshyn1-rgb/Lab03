# Lab03 - Menu de Registos (CLI + Arrays)

## Tabela de testes

Realizar os testes pela ordem indicada, sem reiniciar o programa.

| # | Caso | Passos / Entrada | Saída esperada |
|---|---|---|---|
| 1 | Listar vazio | Opção 2 | (vazio) |
| 2 | Adicionar | Opção 1; ID: 1; Nome: Ana | [OK] Adicionado. |
| 3 | Duplicado | Opção 1; ID: 1; Nome: Ana | [X] Falhou (ID repetido ou nome vazio). |
| 4 | Remover existente | Opção 3; ID: 1 | [OK] Removido. |
| 5 | Remover inexistente | Opção 3; ID: 9 | [X] ID inexistente. |
| 6 | Adicionar vários | Opção 1: ID 1, Ana; opção 1: ID 2, Bob; opção 2 | Mostra Ana e Bob em duas linhas |
| 7 | Nome vazio | Opção 1; ID: 3; Nome: apenas espaços | [X] Falhou (ID repetido ou nome vazio). |
| 8 | Fluxo completo | Adicionar ID 3, Eva; listar; remover ID 3; listar | Eva aparece antes da remoção e desaparece depois; Ana e Bob mantêm-se |
| 9 | Sair | Opção 0 | Adeus! |
