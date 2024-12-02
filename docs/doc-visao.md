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

| Código              |  Nome               |          Descrição  |  
| -----------------   | -----------------   | -----------------   | 
|  F01  |  Login  |  O usuário tem acesso ao sistema.  | 
| F02  | Cadastrar veículo | Motorista cadastra veículo que deseja fazer plano  | 
| F03  | Assinar plano | Motorista assina plano recorrente de assinatura | 
| F04  | Liberar entrada | Motorista escanea seu código na entrada do estacionamento parceiro via QR Code |
| F05  | Liberar saída | Motorista escanea seu código para liberar a saída |
| F06  | Descadastrar veículo | Motorista remove carro cadastrado | 
| F09  | Cancelar plano | Motorista cancela plano de assinatura e não será mais cobrado |  
| F10  | Reportar problema | Motorista pode reportar algum problema no aplicativo |
| F11  | Contagem de uso | Administrador consegue ver cantos carros estão usando o estacionamento no momento e quantos já usaram no período filtrado | 
| F12  | Logout | usuário sai do sistema | 



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
| RN01 | Limitação do uso | Motorista não pode está em mais de um estacionamento ao mesmo tempo |
| RN02 | Mutiplicidade de carros | Caso o cliente tenha mais de um carro e apenas uma assinatura, o segundo carro fica impedido de entrar em estacionamento enquanto o outro esteja usado |
