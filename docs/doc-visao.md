# Documento de Visão

## Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| -----------------   | -----------------   | -----------------   | -----------------   |
| 02/12/2024 | 1.0 | Primeira versão | Yuri Thairony Feitosa de Oliveira | 


## 1. Objetivo do projeto

Criar um sistema para plano de assinatura de estacionamento privados.

## 2. Descrição do problema

|     |      |
| --- | --- |
| **Problema**            | Não existir um sistema unificado que integre diversos estacionamento administrado por diferentes empresas. |
| **Afeta**               | Usuários que usam bastante estacionamento privado. |  
| **Impacta**             | Empresas e logistas que podem perder vendas por causa da cobrança do estacionamento. |
| **Solução**             | Um sistema para um plano de assinatura que integre diversos estacionamento e o usuário paguem uma mensalidade para usar os estacionamentos de forma livre. | 

## 3. Descrição dos usuários 

| Nome                |  Descrição          |   Responsabilidade  |
| -----------------   | -----------------   | -----------------   |
| Administrador do estacionamento | Parceiro com estacionamento | Pode visualizar fluxo de uso do estacionamentos, verificar quantos motoristas com plano usaram |
| Motorista | Usuários cadastrados no sistema que pagam o plano de assinatura para ter direito ao acesso aos estacionamentos parceiros. | Cadastra seu veículo da assinatura, ler seu código de liberação do estacionamento e não compartilha seu código. |

## 4. Descrição do ambiente dos usuários

O motorista ao se cadastradar na plataforma, cadastra seu(s) veículo(s) e assina o plano correpondente a cada veículo, com isso visualiza sempre que está fora de um estacionamento que seu carro não gosta em estacionamento, após adentrar em algum estacionamento parceiro o mesmo sabe quais estacionamento está e visualiza que seu usuário está em uso.

## 5. Principais necessidades dos usuários

Usuários que usam estacionamentos privados com frequência gastam em torno de R$ 300,00 em média na cidade de São Paulo e podem não ter o controle nem a previsibilidade dos gastos com estacionamento que pode ter durante o mês.


## 6. Visão geral do produto

A plataforma visa trazer uma economia e previsilidade de gastos para os assinantes e com isso incetivar o uso de estacionamentos parceiros onde eles podem consumir mais das lojas sediadas nos ambientes dos estacionamentos parceiros.

## 7. Requisitos funcionais

| Código              |  Nome               |          Descrição  |  Prioridade         |
| -----------------   | -----------------   | -----------------   | -----------------   |
|  F01  |  Login  |  O usuário tem acesso ao sistema.  | -  |
| F02  | Cadastro de Ações | O Colaborador cadastra uma ação de trabalho voluntário  |  - |
| F03  | Cadastro de colaboradores | Visitante pode se cadastrar na plataforma | - |
| F04  | Gerenciamento de Ações | Administrador gerencia ações disponíveis e responsável gerencia a própria ação (atualizar e remover) | - | 
| F05  | Gerenciamento de Colaboradores | Administrador gerencia usuários da plataforma (atualizar e remover) | - |
| F06  | Busca de Ações | usuários pesquisam ações disponíveis | Alta | 
| F09  | Visualização de Ações | usuários podem visualizar ações disponíveis | Alta | 
| F10  | Avaliação de Ações | Permite que Colaboradores que participaram avaliem (com critérios a definir como resultados obtidos, pontualidade, efetividade, etc) a ação ocorrida | Média |
| F11  | Denuncia de Ações | usuário alerta os admins sobre questões de segurança da ação elencadas na RN06 | - |
| F12  | Denuncia de Usuário | usuário alerta os administradores sobre questões de segurança elencadas na RN07 | - |
| F13  | Autorização de colaborador em ação | Responsável da ação aceita os Colaboradores que solicitaram participar da ação | Alta |
| F14  | Cadastro do Voluntário em uma ação | Colaborador solicita aos responsáveis de uma ação para participar da mesma | Alta |
| F15  | Logout | usuário sai do sistema | - |



## 8. Requisitos não-funcionais

| Código              |  Nome               |          Descrição  |  Categoria          |  Classificação      |
| -----------------   | -----------------   | -----------------   | -----------------   | -----------------   |
| NF01 | Segurança das informações pessoais | Os dados pessoais, endereços e outras informações dos bancos de dados da plataforma deverão estar asseguradas segundo a Lei Geral de Proteção de Dados Pessoais (LGPD). | Segurança | Obrigatório |
| NF02 | Interface acessível | Espera-se que a interface e o design sejam construídos a partir de fontes, tamanhos, imagens, ícones, esquemas de cores  e outras ferramentas que possibilitem inclusão de pessoas com problemas de visão (ferramenta de lupa, alto contraste, leitura em voz alta, etc), prezando por uma comunicação clara com os usuários | Usabilidade | Desejável |
| NF03 | Usabilidade da plataforma | Espera-se que o uso da plataforma seja intuitivo para que vários tipos de usuários (iniciais, intermediários, avançados, admin) possam navegar pelo sistema sem grandes dificuldades | Usabilidade | Desejável |
| NF04 | Confiabilidade e credibilidade | Serão estabelecidos protocolos para que os usuários tanto possam denunciar ações e/ou usuários suspeitos, como será possível um sistema de avaliação entre voluntários na plataforma sobre confiança e credibilidade das ações | Segurança | Obrigatório |
| NF05 | API externa | Utilizar API externa no sistema | Arquitetura |  Obrigatória |
| NF06 | Arquitetura Distribuída | Separar o front-end e back-end | Arquitetura | Obrigatória |

## 9. Regras de negócio

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| RN01 | Limitação de cadastro de ações | Um Colaborador não pode criar mais de três ações |
| RN02 | Acesso a ações | Em ações "fechadas" (não-públicas), um voluntário precisa ter seu acesso permitido pelo responsável da ação para ver informações sensíveis sobre ela. |
| RN03 | Requisito para avaliar ação | Um voluntário só pode avaliar uma ação em que participou. |
| RN04 | Impedimento de spamming por denúncia | Um usuário não pode fazer mais de 3 denúncias ao mesmo usuário/evento na mesma semana.
| RN05 | Critérios de denúncia do ação | Inverdade da proposta da ação,  entre outros. | 
| RN06 | Critérios de denúncia do usuário | Discurso de ódio, comportamento suspeito, entre outros. | 
