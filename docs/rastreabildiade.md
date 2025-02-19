# Matriz de Rastreabilidade dos Requisitos

| Requisito               | Fonte de Elicitação                              | Requisitos Dependentes     |
|-------------------------|--------------------------------------------------|----------------------------|
| F01 - Login              | Entrevistas com stakeholders, análise de sistemas existentes | Nenhum                     |
| F02 - Cadastrar veículo  | Entrevistas com motoristas, análise de sistemas existentes | F03 - Assinar plano        |
| F03 - Assinar plano      | Entrevistas com motoristas e administradores, análise de sistemas de pagamento recorrente | F02 - Cadastrar veículo    |
| F04 - Liberar entrada    | Entrevistas com administradores de estacionamento, análise de sistemas de controle de acesso | F03 - Assinar plano        |
| F05 - Liberar saída      | Entrevistas com administradores de estacionamento, análise de sistemas de controle de saída | F04 - Liberar entrada      |
| F06 - Descadastrar veículo | Entrevistas com motoristas, análise de sistemas existentes | F02 - Cadastrar veículo    |
| F09 - Cancelar plano     | Entrevistas com motoristas, análise de sistemas de planos recorrentes | F03 - Assinar plano        |
| F10 - Reportar problema  | Entrevistas com motoristas, análise de plataformas de feedback de usuários | Nenhum                     |
| F11 - Contagem de uso    | Entrevistas com administradores de estacionamento, análise de sistemas de monitoramento de fluxo | F04 - Liberar entrada      |
| F12 - Logout             | Entrevistas com motoristas, análise de sistemas de autenticação e segurança | F01 - Login                |
