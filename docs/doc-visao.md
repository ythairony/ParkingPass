# Documento de Visão

## Histórico de Revisões

| Data                |  Versão             |          Descrição  |  Autores            |
| -----------------   | -----------------   | -----------------   | -----------------   |
| 25/04/2023 | 1.0 | Primeira versão | Ana Célia Baía Araújo, Felipe Xavier de Carvalho, José Vilanir de Souza Brito Neto, Rômulo da Silva Cavalcanti e Yuri Thairony Feitosa de Oliveira | 
| 13/09/2023 | 2.0 | Segunda Versão | Ana Célia Baía Araújo, Felipe Xavier de Carvalho, José Vilanir de Souza Brito Neto, Matheus Duarte de Medeiros e Yuri Thairony Feitosa de Oliveira |
| 20/09/2023 | 2.1 | Terceira Versão | Ana Célia Baía Araújo, Felipe Xavier de Carvalho, José Vilanir de Souza Brito Neto, Matheus Duarte de Medeiros e Yuri Thairony Feitosa de Oliveira |

## 1. Objetivo do projeto

Criar uma plataforma para conectar voluntários com projetos comunitários.

## 2. Descrição do problema

|     |      |
| --- | --- |
| **Problema**            | não existir um canal de comunicação específico para promover trabalhos voluntários, com credibilidade e confiabilidade, a partir da conexão entre pessoas e instituições interessadas e ações voluntárias interessadas em voluntariado |
| **Afeta**               | interessados em promover e em participar de ações de voluntariado |  
| **Impacta**             | várias pessoas deixam de colaborar com e/ou de receber ações sociais |
| **Solução**             | existir uma plataforma que permita que interessados e instituições relacionadas a trabalho voluntário possam se articular em ações  | 

## 3. Descrição dos usuários 

| Nome                |  Descrição          |   Responsabilidade  |
| -----------------   | -----------------   | -----------------   |
| Administrador | Os administradores serão usuários com permissões para alterar ações e perfis dos demais usuários, e todos os outros requisitos | Gerenciar ações e usuários - Moderar o conteúdo postado - Validar denúncias sobre ações e usuários - Realizar manutenções e melhorias no sistema |
| Colaborador | Os usuários cadastrados com login, que não são administradores, poderão utilizar a plataforma para se voluntariar, interagir com outros usuários e criarem ações voluntárias nas quais eles serão responsáveis. | Criar ações, se tornando Responsável da ação; Gerenciar os colaboradores das suas ações; Interagir e visualizar detalhes sobre categorias, interesses, ações que já participaram, outras informações disponíveis de outros colaboradores e ações; Inscrever-se em ações.  |
| Voluntário | Os Voluntários são usuários que tem sua solicitação de participação em ação aceita por um responsável da ação.  | Os voluntários podem fazer determinadas ações, como por exemplo, avaliar uma ação. 
| Visitante | Os usuários que podem visualizar o site mas que, por não terem realizado cadastro ainda, não podem se voluntariar ou criar ações voluntárias na plataforma.   | Os usuários não cadastrados podem: - Visualizar ações e dados não sensíveis das ações - Se cadastrar na plataforma - Compartilhar ações existentes | 
| Responsável | Os Colaboradores serão Responsáveis quando forem os criadores de uma ação ou forem adicionados como "responsáveis" por outro Responsável de uma ação | Os responsáveis poderão aceitar ou recusar a adesão Colaboradores que enviarem solicitação para se tornarem voluntários na ação que são responsáveis, além de poderem moderar comentários e editar informações da ação |

## 4. Descrição do ambiente dos usuários

A plataforma terá como página inicial do visitante ações organizadas por tema, popularidade e avaliação. Já a página inicial do usuário cadastrado (Colaborador) tem uma visão de ações sugeridas, visão de outros colaboradores para entrar em contato e opção de ver as ações em que já se voluntariou. Na plataforma, espera-se que os colaboradores possam interagir uns com outros, pesquisar ações tanto pelos responsáveis quanto por categorias e interesses temáticos, localidade e período de execução, além de cadastrar ações voluntárias. A plataforma poderá ter suas ações e página do perfil de colaboradores compartilhadas com botões de compartilhamento com as redes sociais mais utilizadas atualmente.

## 5. Principais necessidades dos usuários

Com base no formulário aplicado, que teve 94 respondentes, definimos as necessidades dos usuários a partir das seguintes análises de respostas, de forma que o produto a ser desenvolvido deverá superá-las  e estar alinhado aos fatores que percebemos poderão levar os usuários a utilizar nossa plataforma. Contatamos que:
65% das pessoas que responderam já foram voluntários
51% acreditam ser difícil achar ações voluntárias para ajudar
95% consideram participar de alguma ação voluntária se forem apresentados
E como principais fatores para escolha em participar de uma ação voluntária:
73,4% “conhecer e confiar no projeto”
59,6% “Ajudar pessoas/animais que precisam de ajuda”
56,4% “Conhecer a história de quem estão ajudando”


## 6. Alternativas concorrentes

Atualmente, redes sociais como “Instagram” são utilizadas por seus usuários para diversas finalidades, incluindo o público interessado em trabalhos voluntários, sendo necessário que quaisquer outras propostas, como esta plataforma, possam se conectar de alguma forma com esses canais (botões para compartilhamento de ações, plugins, etc…). Existem plataformas específicas para tal como uma das maiores aqui no Brasil, a “Atados” (focada em trabalhos específicos, com seção de ações, mas é ocasional, serve mais como banco de voluntários para ONGs cadastradas) e outra “Padrinhonota10”, voltada para apadrinhamento de crianças e jovens em abrigos e afins, porém tem pouca aplicação para outros tipos de voluntariado. Algumas plataformas como “Vakinha” online ou “Catarse” promovem financiamento coletivo, muito utilizado em campanhas para arrecadação financeira, porém são muito limitadas à outros tipos de trabalhos.

## 7. Visão geral do produto

A Plataforma QAjuda será um produto de acesso para toda a sociedade, com recursos de usabilidade que considerem premissas de acessibilidade e interface intuitiva. A proposta é integrar e proporcionar um ambiente para interação entre indivíduos entre si, comunidades e instituições como OSCIPs/ONGs que desenvolvam/tenham interesse em trabalhos voluntários. O produto poderá dispor aos usuários um catálogo de ações e informações sobre esses trabalhos, que deverá ser continuamente atualizado a partir do uso da Plataforma, de forma que a divulgação de ações, pela integração com redes sociais e outros links, poderá atrair novos usuários e ampliar as redes de atuação dos trabalhos voluntários propostos.

## 8. Requisitos funcionais

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



## 9. Requisitos não-funcionais

| Código              |  Nome               |          Descrição  |  Categoria          |  Classificação      |
| -----------------   | -----------------   | -----------------   | -----------------   | -----------------   |
| NF01 | Segurança das informações pessoais | Os dados pessoais, endereços e outras informações dos bancos de dados da plataforma deverão estar asseguradas segundo a Lei Geral de Proteção de Dados Pessoais (LGPD). | Segurança | Obrigatório |
| NF02 | Interface acessível | Espera-se que a interface e o design sejam construídos a partir de fontes, tamanhos, imagens, ícones, esquemas de cores  e outras ferramentas que possibilitem inclusão de pessoas com problemas de visão (ferramenta de lupa, alto contraste, leitura em voz alta, etc), prezando por uma comunicação clara com os usuários | Usabilidade | Desejável |
| NF03 | Usabilidade da plataforma | Espera-se que o uso da plataforma seja intuitivo para que vários tipos de usuários (iniciais, intermediários, avançados, admin) possam navegar pelo sistema sem grandes dificuldades | Usabilidade | Desejável |
| NF04 | Confiabilidade e credibilidade | Serão estabelecidos protocolos para que os usuários tanto possam denunciar ações e/ou usuários suspeitos, como será possível um sistema de avaliação entre voluntários na plataforma sobre confiança e credibilidade das ações | Segurança | Obrigatório |
| NF05 | API externa | Utilizar API externa no sistema | Arquitetura |  Obrigatória |
| NF06 | Arquitetura Distribuída | Separar o front-end e back-end | Arquitetura | Obrigatória |

## 10. Regras de negócio

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| RN01 | Limitação de cadastro de ações | Um Colaborador não pode criar mais de três ações |
| RN02 | Acesso a ações | Em ações "fechadas" (não-públicas), um voluntário precisa ter seu acesso permitido pelo responsável da ação para ver informações sensíveis sobre ela. |
| RN03 | Requisito para avaliar ação | Um voluntário só pode avaliar uma ação em que participou. |
| RN04 | Impedimento de spamming por denúncia | Um usuário não pode fazer mais de 3 denúncias ao mesmo usuário/evento na mesma semana.
| RN05 | Critérios de denúncia do ação | Inverdade da proposta da ação,  entre outros. | 
| RN06 | Critérios de denúncia do usuário | Discurso de ódio, comportamento suspeito, entre outros. | 

## 11. Casos de uso por ordem de prioridade

1. [CDU-001 - Autorizar voluntário na ação](../cdu/cdu-001/detalhamento-001.md)
2. [CDU-002 - Voluntariar em uma ação](../cdu/cdu-002/detalhamento-002.md)
3. [CDU-003 - Visualizar Ação](../cdu/cdu-003/detalhamento-003.md)
4. [CDU-004 - Buscar ações](../cdu/cdu-004/detalhamento-004.md)
5. CDU-005 - Criar ação
6. CDU-006 - Convidar responsável para uma ação
7. CDU-007 - Remover responsável de uma ação
8. CDU-008 - Desvoluntariar de uma ação
9. CDU-009 - Remover voluntário de uma ação
10. CDU-010 - Avaliar voluntário
11. CDU-011 - Avaliar ação
12. CDU-012 - Gerenciar ação
13. CDU-013 - Gerenciar usuário
14. CDU-014 - Denunciar ação
15. CDU-015 - Denunciar usuário
16. CDU-016 - Criar conta
17. CDU-017 - notificar usuário

## 12. Glossário

|  Termo  |  Explicação  |
| ------- | ------------ |
| Ação | evento organizado por pessoas com objetivo de promover atividades que beneficiem a sociedade de forma gratuita |
| Administrador | Usuários com permissões para alterar ações, perfis dos usuários e fazer a moderação da plataforna |
| Avaliação | É a forma que um voluntário pode dar feedback de uma ação para o responsável e para os visitantes |
| Colaborador | Usuários cadastrados com login, que não são administradores |
| Responsável | Usuários que criam ações ou são adicionados como responsáveis por outro Responsável de uma ação |
| Visitante | Usuários não cadastrados na plataforma e que a utilizam |
| Voluntário | Usuários que tem sua solicitação de participação em ação aceita por um Responsável da ação |

## 13. Mensagens padrão

|   Contexto de uso  | Mensagem | 
| ------------------ | ---------------------------- | 
| Criar ação | Ação criada com sucesso!| 
| Pesquisa sem resultados| Não foi encontrado nenhum resultado para esta pesquisa.|
| Solicitação para participar de ação como voluntário(a)| Que ótimo, recebemos sua solicitação para ser voluntário(a) nesta ação, será de grande ajuda. Em breve você receberá a resposta!| 
|Resposta de aceite à solicitação para participar de ação como voluntário(a)| Sua solicitação para participar de ação como voluntário(a) foi aceita! Estamos muito felizes com sua ajuda!|
|Resposta de recusa à solicitação para participar de ação como voluntário(a)| Infelizmente sua solicitação para participar de ação como voluntário(a) foi recusada! Veja em "detalhes" os motivos para a recusa. Mas não fique triste, temos várias outras ações feitas para você, não desista de continuar ajudando! botão "Detalhes"|
|Convite para tornar voluntário um responsável na ação| Você foi convidado(a) para se tornar uma das pessoas responsáveis por esta ação. Você aceita? botões "Sim"/"Não"|
|Ausência de solicitações pendentes para voluntários(as) em ação| Não há novas solicitações para participação na ação.|
|Remoção de responsável| Você foi removido(a) da função de responsável nesta ação.|
|Remoção de voluntário| Você foi removido(a) desta ação enquanto voluntário(a).|
|Solicitação para desistir de ação como responsável| Recebemos sua solicitação para deixar de ser responsável nesta ação, que pena mas imprevistos acontecem! Aguardamos você na organização de outras ações em outras oportunidades... Continue ajudando, todos por um bem comum!|
