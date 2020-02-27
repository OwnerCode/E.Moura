# E.Moura
Empresa de Servicos e Vendas de produtos Hidraulicos e Pneumaticos

# Versão 1.0 ** Funcionario ** (Planejamento)
  - CRUD de Funcionarios
  
  * Requisitos * 
    - Cada Funcionario será responsavel por um Setor (Geral/Financeiro/Estoque...)
    
  * Detalhes Funcionario * (Andamento)
    - Nome: String
    - Email: String
    - Celular: String
    - Grupo: Object (O grupo que empregado se enquadra na empresa e a que equipe ele/ela pertence.)
    - Administração: Object (tempo de serviço e status do empregado, assim como informações sobre ausências)
    - Endereço: Object
    - Observação: String
    - Anexos: <?>

# Versão 2.0 ** Estoque ** (Planejamento)
  - CRUD produto do estoque
  - CRUD de Fornecedores  
  
  * Requisitos *
    - Poderá visualizar em um Dashboard os Produtos que estão em estoque baixo (Grafico)
    - Poderá visualizar movimentação dos produtos ( Qual mais sai e qual menos sai "Top 10" )
    - Poderá solicitar o Produto para compra
    
  * Detalhes Pedido de Produtos * (Ok)
    - Numero de Identificação (Unico) (Int)
    - Data da Solicitação
    - Hora da Solicitação
    - Estatus (Aguardando/Entregue)
    - Aprovação (Negado/Aprovado)
    - Funcionario que está solicitando
    - Produtos
  
  * Detalhes Produto * (Ok)
    - Numero de Identificação (Unico) (Int)
    - Codigo de Referencia "Modelo" (Objeto)
    - Marca (String 30)
    - Quantidade (Int)
    - Quantidade Minima (Int) { Notificar o Funcionario quando estiver com baixa no Estoque }
    - Valor Final (Double) (Para Venda para o Cliente)
    - Valor Revenda (Double) (Para Venda para Outros)
    - Valor Fornecedor (Double) (Valor Adquirido do fornecedor)
    - Local onde se encontra o produto (Sala(A-Z)/Prateleira(A-Z)/Gaveta(Dezena) ex: "ABAB12") (String 10)
    - Histórico (Entrada e Saida)
  
  * Detalhes Fornecedor * (Ok)
    - Numero de Identificação (Unico) (Int)
    - Nome (String 100)
    - Contato 1 (String 30)
    - Contato 2 (String 30)
    - Email 1 (String 60)
    - Email 2 (String 60)
    - Endereço (Objeto)
    - Produtos "Listagem dos produtos" (Objeto)  
    
# Versão 3.0 ** Financeiro ** (Planejamento)
   
# Versão 4.0 ** Vendas ** (Planejamento)

 * Detalhes Ordem de Venda *
    - Numero de Identificação (Unico) (String 20)
    - Atendente
    - Cliente
    - Produtos (Listagem dos Produtos)
    - Valor Final
    - Desconto
    
# Versão 4.0 ** Serviços ** (Planejamento)


