# manutenção_de_maquinas_grupoY
 -Funcionalidades do Sistema
 -Cadastro de máquinas

-Código da máquina
Nome
Ano
Estado (ativa / inativa)

 -Registro de manutenções

Tipo de manutenção
Data
Máquina associada
Responsável
Observações

 -Listagem

Máquinas cadastradas
Manutenções registradas
Relatório geral

 -Módulo Extra nº 2 — Cálculo de Custos

O sistema calcula automaticamente:
Custo total de cada manutenção
Custos acumulados por máquina
Relatório geral de gastos da planta

 -Execução do Projeto

1. No Google Colab
Faça upload de: manutencao_maquinas.py
pasta dados/
notebook_colab.ipynb
Execute o notebook.

2. Localmente (Windows/Linux)
python manutencao_maquinas.py

 Histórico Completo de Commits 

 -AULA 1 — Estrutura Inicial
commit: Inicialização do repositório
- Criação da pasta do projeto
- Adicionado arquivo README.md inicial

commit: Criação da estrutura base do sistema
- Criado arquivo manutencao_maquinas.py
- Implementado menu inicial
- Criada pasta /dados

 -AULA 2 — Cadastro de Máquinas
commit: Implementada função de cadastro de máquinas
- Função cadastrar_maquina()
- Validação de entradas
- Gravação em maquinas.txt

commit: Adicionada função de listagem de máquinas
- Função listar_maquinas()
- Leitura da base de dados

 -AULA 3 — Registro de Manutenções
commit: Criada função registrar_manutencao()
- Permite registrar manutenções
- Integração com cadastro de máquinas
- Armazenamento em manutencoes.txt

commit: Função listar_manutencoes() adicionada
- Exibe todas as manutenções registradas

 -AULA 4 — Relatórios
commit: Implementado relatório geral
- Relatório agrupado por máquina
- Visualização de manutenções completas

 -AULA 5 — Refatoração e Modularização
commit: Organização do código e modularização
- Melhoria no menu
- Código reorganizado em funções
- Correções gerais

 -AULA 6 — Módulo Extra nº 2 (Custos de Manutenção)
commit: Implementação do módulo de custos
- Função registrar_custo()
- Cálculo automático por manutenção
- Criação de custos_manutencao.txt

commit: Relatório de custos adicionado
- total_por_maquina()
- total_geral()
- Exibição formatada

 -AULA 7 — Testes e Validações
commit: Validações e tratamento de erros
- Correções de input inválido
- Garantia de integridade dos arquivos

 -AULA 8 — Finalização e Entrega
commit: Documentação final
- README completo
- Notebook Colab adicionado
- Projeto pronto para apresentação

Desenvolvido por Equipe do Projeto Integrador — Computação 1 – Engenharia Mecânica

LINK DE ACESSO PARA O COLAB ABAIXO
https://colab.research.google.com/drive/1C0snwrpYBnytH0vr100TOK9bEaYqLZxO?authuser=2#scrollTo=9kmTZPP3vvG3
