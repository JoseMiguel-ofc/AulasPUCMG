
# Matriz de Rastreabilidade de Requisitos

Uma ferramenta para garantir a cobertura e rastreabilidade de requisitos desde sua origem até a implementação e teste.

## Template

### 1. Requisitos de Alto Nível → Requisitos Detalhados

| ID | Descrição | Fonte | ID Requisito Detalhado(s) | Entrega da EAP | Prioridade | Responsável | Comentários |
|----|-----------|------|---------------------------|----------------|-----------|------------|------------|
| RAL### | - | - | RD### | (Referência à entrega específica da EAP) | (Alta, Média, Baixa) | - | - |

**Entrega da EAP:** Refere-se à entrega específica do projeto na Estrutura Analítica de Projetos (EAP) com a qual o requisito está alinhado. 

**Prioridade:** Indica o nível de importância ou urgência de um requisito. Pode ser classificada em:

- **Alta:** Requisitos críticos que devem ser implementados o mais rápido possível.
- **Média:** Requisitos importantes, mas que podem ser adiados se necessário.
- **Baixa:** Requisitos desejáveis, mas que têm menor impacto se não forem implementados imediatamente.

### 2. Requisitos Detalhados → Testes

| ID | Descrição | ID Teste(s) | Entrega da EAP | Prioridade | Responsável | Status | Comentários |
|----|-----------|------------|----------------|-----------|------------|-------|------------|
| RD### | - | T### | (Referência à entrega específica da EAP) | (Alta, Média, Baixa) | - | - | - |

## Exemplo de Uso

### 1. Requisitos de Alto Nível → Requisitos Detalhados

| ID | Descrição | Fonte | ID Requisito Detalhado(s) | Entrega da EAP | Prioridade | Responsável | Comentários |
|----|-----------|------|---------------------------|----------------|-----------|------------|------------|
| RAL001 | Usuário deve poder cadastrar colaborador no sistema | Cliente | RD001, RD002 | Cadastro colaborador | Média | José Miguel | Cadastro dos colaboradores pelo usuário |
| RAL002 | Usuário deve poder cadastrar setores no sistema | Cliente | RD003 | Cadastro setor | Média | Joãozinho | Cadastro dos setores pelo usuário |

### 2. Requisitos Detalhados → Testes

| ID | Descrição | ID Teste(s) | Entrega da EAP | Prioridade | Responsável | Status | Comentários |
|----|-----------|------------|----------------|-----------|------------|-------|------------|
| RD001 | Sistema deve aceitar credenciais válidas | T001 | Cadastro | Média | José Miguel | Em Progresso | - |
| RD002 | Sistema deve rejeitar credenciais inválidas | T002 | Cadastro | Alta | José Miguel | Em Progresso | Falha ocasional |
| RD003 | Setor deve ver nome, local e responsável | T003 | Cadastro | Média | Joãozinho | Não Iniciado | - |

