# Modelo de Oficina mecânica

# ** Principais entidades

- Clientes cadastrados (Cliente)
- Veículos (Veículo)
- Fornecedor de Peças (Fornecedor)
- Estoque de Peças (Estoque)
- Peças de Automóveis (Peça)
- Mecânicos (Mecânico)
- Ordem de serviço (OS)
# ** Entidades de tipo

- Tipo de pagamento (Formas de Pagamento)
- Definição do tipo de Serviço (Vistoria Técnica)

# ** Entidades relacionadas
- Mecânicos da equipe e serviços (Equipe)
- Produtos da OS (Requerimento)
- Tipos de Pagamento (Pagamento)
- Fornecimento de peças a Oficina (Fornecedor/Peça)
- Peças na Oficina (Estoque/Peças)

# ** Contexto
- O cliente leva o veículo ao estabelecimento;
- Um procedimento é originado com a informações do veículo, o de serviço é definido após uma avaliação técnica;
- O cliente autorizando, é aberta uma OS e feito o registro das atividades e produtos a serem lançados, bem como data de abertura e previsão de encerramento, constando o valor total com os gastos de peças e mão de obra e definição de pagamentos;
- Sendo acionada a equipe de acordo com o tipo de serviço a ser feito é iniciado os procedimentos a serem realizados no veículo, requerimento de peças no estoque, ou se necessário, com o fornecedor, bem como, disponibilizando o andamento das atividades;

