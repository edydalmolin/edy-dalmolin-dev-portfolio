# MEI em Dia

**Aplicativo de gestão empresarial para microempreendedores brasileiros**

MEI em Dia é um aplicativo Flutter desenvolvido para ajudar profissionais autônomos e pequenos empresários a organizar as partes mais importantes da operação diária do negócio em um só lugar.

O produto tem foco em simplicidade, clareza e controle prático do negócio.

## Visão Geral do Produto

O aplicativo centraliza:

- Gestão de clientes
- Receitas e despesas
- Contas a receber
- Contas a pagar
- Compromissos e lembretes
- Orçamentos e propostas
- Visão geral do negócio
- Informações específicas do MEI e orientação financeira
- Interação com IA para o negócio

## Stack Tecnológica

- Flutter
- Dart
- Riverpod
- GoRouter
- Drift
- SQLite
- Material 3
- Arquitetura pronta para REST
- Android
- iOS
- Testes automatizados

## Arquitetura

O projeto segue uma arquitetura modular, orientada a features, com separação clara entre as camadas de interface, lógica de negócio e dados.

Cada funcionalidade principal é organizada de forma independente, com controllers, repositories, modelos de domínio e responsabilidades de persistência separados para melhorar a manutenibilidade e a escalabilidade.

O aplicativo utiliza Drift + SQLite para persistência local tipada e Riverpod para gerenciamento de estado.

A navegação é feita com GoRouter.

## Principais Módulos

### Clientes

Gestão completa de clientes com:

- Criação, edição e busca
- Informações de contato
- Relações financeiras
- Valores em aberto
- Histórico do cliente
- Interação via WhatsApp
- Proteção contra exclusão de clientes com registros vinculados

### Gestão Financeira

O módulo financeiro oferece suporte a:

- Receitas
- Despesas
- Filtragem mensal
- Visibilidade do fluxo de caixa
- Cálculo do resultado do negócio
- Associação opcional com cliente

### Contas a Receber e a Pagar

O aplicativo inclui:

- Contas a receber pendentes
- Contas a pagar pendentes
- Datas de vencimento
- Acompanhamento de atrasos
- Filtragem por status
- Fluxo de quitação
- Geração automática de lançamento financeiro ao quitar uma conta a receber

### Agenda

Os usuários podem organizar:

- Compromissos
- Lembretes de pagamento
- Lembretes de recebimento
- Itens concluídos e pendentes
- Tarefas em atraso
- Eventos vinculados a clientes

### Orçamentos e Propostas

O fluxo de orçamentos oferece suporte a:

- Criação de rascunhos
- Associação com cliente
- Alterações de status
- Estados enviado e aprovado
- Conversão de orçamentos aprovados em contas a receber

### Painel do Negócio

A tela inicial consolida:

- Receitas do mês
- Despesas do mês
- Resultado financeiro
- Contas a receber
- Contas a pagar
- Próximos compromissos
- Atalhos para orçamentos
- Acesso ao assistente do negócio

### Gestão do MEI

O aplicativo inclui um módulo voltado para MEIs brasileiros com:

- Visibilidade do faturamento anual
- Monitoramento do limite de faturamento
- Orientação sobre capital de giro
- Obrigações do negócio
- Configurações e informações do negócio

## Qualidade e Testes

O projeto inclui testes automatizados para lógica de negócio, repositories, controllers e fluxos de funcionalidades.

O processo de desenvolvimento prioriza código de fácil manutenção, modularização e proteção contra regressões.

## Foco no Desenvolvimento do Produto

O MEI em Dia foi desenvolvido como um produto comercial real, e não como uma demonstração técnica.

O processo de desenvolvimento envolveu:

- Definição do produto
- Arquitetura das funcionalidades
- Modelagem dos dados locais
- Regras de negócio
- Fluxos financeiros
- Decisões de experiência do usuário
- Validação automatizada
- Preparação do build para Android
- Estrutura do projeto pronta para iOS

## Meu Papel

Sou responsável pela direção do produto, pelas decisões de arquitetura, pelo fluxo de implementação, pela validação e pela evolução contínua do aplicativo.

Ferramentas de desenvolvimento com apoio de IA são utilizadas para aumentar a produtividade, enquanto arquitetura, decisões de produto, testes e validação final permanecem sob revisão ativa.

## Status

O aplicativo está em desenvolvimento ativo e em preparação para lançamento.

O código-fonte permanece privado por se tratar de um produto comercial.

---

[Voltar ao portfólio](../README.md)
