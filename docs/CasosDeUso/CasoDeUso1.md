### Caso de Uso 1:Cadastrar Morador
* **Atores**: Agente de Campo
* **Descrição**:Permite o cadastro de moradores da Ilha Primeira com seus dados socioeconômicos
* **Pré-condições**: Agente deve estar autenticado no sistema.
* **Fluxo Principal**:
    i.Agente seleciona "Novo Cadastro"
    ii.Sistema exibe formulário com campos:
    -Dados pessoais (Nome, CPF, Data Nascimento)
    -Endereço completo
    -Dados socioeconômicos (renda, acesso a serviços)
    iii.Agente preenche todos os campos obrigatórios
    iv.Agente confirma cadastro
    v.Sistema valida CPF e dados
      vi.Sistema armazena cadastro
    vii.Sistema emite comprovante digital
* **Pós-condição**:
i.Novo morador consta no banco de dados
2.Dados disponíveis para relatórios
