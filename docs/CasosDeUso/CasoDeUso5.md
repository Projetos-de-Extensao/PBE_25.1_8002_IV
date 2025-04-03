### Caso de Uso 2: Registrar Problema de Infraestrutura
* **Atores**: Morador, Agente comunitário
* **Descrição**: Cadastra ocorrências de problemas públicos (esgoto, iluminação etc.)
* **Pré-condições**:
   *  Localização geográfica definida
   *  Usuário autenticado (para moradores)
   *  Problema ainda não reportado
        
* **Fluxo Principal**:
   *  Usuário seleciona "Reportar Problema"
   *  Preenche o tipo de ocorrência, Gravidade (1-5) e Foto comprobatória
   *  Sistema atribui protocolo
   *  Encaminha para órgão responsável
* **Pós-condição**:
   *  Ocorrência registrada no mapa interativo
   *  Criado ticket de acompanhamento
   *  Disparo de alerta para equipe técnica
   *  Registro no histórico do endereço
