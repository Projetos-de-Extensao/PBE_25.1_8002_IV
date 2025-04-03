### Caso de Uso 2: Atualizar Dados do Morador
* **Atores**:  Agente de campo ou morador ( autoatendimento se habilitado)
* **Descrição**:Atualizar informações cadastrais (mudança de endereço, nova renda).
* **Pré-condições**:
   * Morador já estar cadastrado.
   * Permissões de edição.
        
* **Fluxo Principal**:
   *  O agente busca o morador por CPF ou nome.
   *  Edita os campos necessários.
   *  Registra motivo da atualização.
   *  Sistema armazena nova versão.
* **Pós-condição**:
*  Banco de Dados Atualizado
*  Data/hora da modificação registrada
*  Histórico de Alterações
