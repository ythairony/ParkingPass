Atributos:  

**Prioridade**: Nível de importância do requisito para o sucesso do sistema (Alta, Média, Baixa).  
**Complexidade**: Refere-se à dificuldade de implementação (Alta, Média, Baixa).  
**Dependências**: Identifica se o requisito depende de outros para ser implementado.  
**Status**: O estado atual do requisito (Elicitado, Em desenvolvimento, Implementado).  
**Impacto no Usuário**: Define o grau de impacto que a funcionalidade tem para os usuários (Alto, Médio, Baixo).  
**Tempo Estimado**: Estimativa do tempo necessário para implementar o requisito (Curto, Médio, Longo).  

# Tabela de Atributos dos Requisitos Funcionais

| Requisito               | Prioridade | Complexidade | Dependências                | Status       | Impacto no Usuário | Tempo Estimado |
|-------------------------|------------|--------------|-----------------------------|--------------|--------------------|-----------------|
| F01 - Login              | Alta       | Média        | Nenhuma                     | Elicitado    | Alto               | Curto           |
| F02 - Cadastrar veículo  | Alta       | Média        | F03 (Assinar plano)         | Elicitado    | Alto               | Médio           |
| F03 - Assinar plano      | Alta       | Alta         | F02 (Cadastrar veículo)     | Elicitado    | Alto               | Longo           |
| F04 - Liberar entrada    | Alta       | Alta         | F03 (Assinar plano)         | Elicitado    | Alto               | Médio           |
| F05 - Liberar saída      | Alta       | Alta         | F04 (Liberar entrada)       | Elicitado    | Alto               | Médio           |
| F06 - Descadastrar veículo | Média     | Média        | F02 (Cadastrar veículo)     | Elicitado    | Médio              | Curto           |
| F09 - Cancelar plano     | Alta       | Média        | F03 (Assinar plano)         | Elicitado    | Alto               | Médio           |
| F10 - Reportar problema  | Média      | Média        | Nenhuma                     | Elicitado    | Médio              | Curto           |
| F11 - Contagem de uso    | Baixa      | Alta         | F04 (Liberar entrada)       | Elicitado    | Médio              | Longo           |
| F12 - Logout             | Alta       | Baixa        | Nenhuma                     | Elicitado    | Alto               | Curto           |
