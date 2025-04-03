### Caso de Uso 1:Cadastrar Morador
* **Atores**: Agente de Campo
* **Descrição**:Permite o cadastro de moradores da Ilha Primeira com seus dados socioeconômicos
* **Pré-condições**: Agente deve estar autenticado no sistema.
* **Fluxo Principal**:
    1.Agente seleciona "Novo Cadastro"
    2.Sistema exibe formulário com campos:
    -Dados pessoais (Nome, CPF, Data Nascimento)
  
    -Endereço completo
  
    -Dados socioeconômicos (renda, acesso a serviços)
  
    3.Agente preenche todos os campos obrigatórios
    4.Agente confirma cadastro
    5.Sistema valida CPF e dados
    6.Sistema armazena cadastro
    7.Sistema emite comprovante digital
* **Pós-condição**:
1.Novo morador consta no banco de dados
2.Dados disponíveis para relatórios
