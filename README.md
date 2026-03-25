# API Tests - Serverest

Projeto de testes automatizados de API desenvolvido para o processo seletivo da SimFrete. 
Testes apontando para [Serverest](https://serverest.dev/).

## Sobre o Projeto

Este projeto implementa testes automatizados para a API Serverest, aonde foi aplicado:
- Testes Exploratórios da API
- Utilização de variáveis globais para os testes
- Criação de Scripts de Testes ao invés do Asserts do Bruno
- Post Response scripts para variáveis
- Exclusão de dados criados no fluxo
- Githib actions + Bru Cli para execução pós commit

## Tecnologias

- **[Bruno](https://www.usebruno.com/)** - Framework de automação de API

## Principais Estrutura do Projeto

```
frontend-tests/
├── .github/workflows/            # Pasta com a configuração do Github Actions
├── collections/
│   ├── 1-Login/                  # Pasta com testes de /login
│   ├── 2-Usuários/               # /usuarios
│   ├── 3-Produtos/               # /produtos
│   ├── 4-Carrinhos/              # /carrinhos
│   └── 5-Last/                   # Limpeza de dados restantes
|  
├── emvironments/                 # Pasta com variáveis globais
|
└── bruno.json                    # Configurações do Bruno
```

## Melhorias futuras

  - logs para partes complexas
  - parâmetro para visualizar logs ou não.
  - melhorar documentação
  - os demais testes
  
