# Sistema de gerenciamento de estoque para pequenos comerciantes.

Um software simples e intuitivo que ajude os comerciantes a  monitorar o estoque em tempo real, gerar relatórios e alertas de produtos prestes a vencer ou em falta.


## Sumário executivo


### 1 - Visão geral do projeto 

O objetivo deste projeto é desenvolver um sistema de gerenciamento de estoque para pequenos comerciantes, permitindo o controle eficiente de inventário, redução de desperdícios, e otimização dos processos de reposição de produtos.


### 2 - Público alvo

Este software é destinado a pequenos comerciantes que necessitam de uma solução prática e acessível para gerenciar seus estoques, como donos de lojas de conveniência, pequenos mercados, farmácias, e outros estabelecimentos de varejo.


### 3 - Principais funcionalidades

- Cadastro de Produtos: Permitir o registro e organização de produtos com informações detalhadas como nome, código, categoria, preço e quantidade em estoque.
- Controle de Inventário: Monitorar a entrada e saída de produtos, e emitir alertas quando o estoque estiver baixo.
- Relatórios de Estoque: Gerar relatórios detalhados de estoque, incluindo histórico de vendas e movimentações.
- Integração com Fornecedores: Facilitar a reposição automática de produtos ao integrar o sistema com os fornecedores preferenciais


### 4 - Benefícios

- Eficiência Operacional: Reduzir o tempo gasto com a gestão manual de estoques e minimizar erros humanos.
- Redução de desperdício: Acompanhar o vencimento de produtos e evitar excessos de estoque, diminuindo o desperdício.
- Melhoria na Tomada de Decisão: Oferecer dados precisos para auxiliar os comerciantes a tomarem decisões informadas sobre compras e vendas.


### 5 - Considerações finais

Este sistema irá facilitar a gestão de estoque para pequenos comerciantes, promovendo eficiência, economia, e crescimento sustentável dos negócios.


## Documento de Requisitos

### 1 - Definições, Acrônimos e Abreviações

- Sistema: Refere-se ao Sistema de Gerenciamento de Estoque.
- Usuário: Pequenos comerciantes utilizando o sistema.
- Estoque: Quantidade de produtos disponíveis no estabelecimento.
- Produto: Qualquer item que esteja sendo gerenciado pelo sistema.


### 2 - Requisitos Funcionais

#### 2.1 Cadastro de Produtos

- RF001: O sistema deve permitir o registro de novos produtos, incluindo informações como nome, código, categoria, preço e quantidade em estoque.
- RF002: O sistema deve permitir a edição e exclusão de produtos cadastrados.
- RF003: O sistema deve organizar os produtos por categorias para facilitar a consulta e o controle.


#### 2.2 Controle de Inventário

- RF004: O sistema deve monitorar a entrada e saída de produtos do estoque.
- RF005: O sistema deve emitir alertas quando o estoque de um produto atingir um nível mínimo configurável.
- RF006: O sistema deve permitir a visualização em tempo real da quantidade de produtos em estoque.


#### 2.3 Relatórios de Estoque

- RF007: O sistema deve gerar relatórios detalhados de estoque, incluindo histórico de vendas, movimentações, e vencimentos.
- RF008: O sistema deve permitir a exportação dos relatórios em formatos como PDF e Excel.


#### 2.4 Integração com Fornecedores

- RF009: O sistema deve integrar-se com sistemas de fornecedores para facilitar a reposição automática de produtos.
- RF010: O sistema deve permitir a configuração de fornecedores preferenciais para cada produto.


### 3 - Requisitos Não Funcionais

#### 3.1 Usabilidade

- RNF001: O sistema deve ter uma interface intuitiva, de fácil utilização por usuários com pouco conhecimento técnico.
- RNF002: O sistema deve ser acessível via dispositivos móveis e desktops.


#### 3.2 Desempenho

- RNF003: O sistema deve ser capaz de processar transações em tempo real, sem atrasos significativos.
- RNF004: O tempo de resposta do sistema para operações de cadastro, consulta, e geração de relatórios não deve exceder 2 segundos.


#### 3.3 Segurança

- RNF005: O sistema deve garantir a segurança dos dados, incluindo autenticação de usuários e criptografia de dados sensíveis.
- RNF006: O sistema deve manter um histórico de alterações realizadas nos cadastros de produtos e inventário.


#### 3.4 Confiabilidade

- RNF007: O sistema deve estar disponível pelo menos 99,5% do tempo, excluindo períodos de manutenção programada.
- RNF008: O sistema deve ter mecanismos de backup e recuperação de dados em caso de falhas.

### 4 - Restrições

#### 4.1 Tecnologia

O sistema será desenvolvido usando tecnologias web modernas, garantindo compatibilidade com os principais navegadores e sistemas operacionais.


#### 4.2 Orçamento

O desenvolvimento do sistema deve ser realizado dentro do orçamento previsto pelo cliente, sem comprometer a qualidade ou as funcionalidades essenciais.
