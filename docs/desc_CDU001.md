| **Nome**                                  | Entrar em estacionamento                                      |
|-------------------------------------------|---------------------------------------------------------------|
| **Pré-condição**                          | O código único do motorista não pode estar em uso em outro estacionamento. |
| **Pós Condição em caso de sucesso**       | O estacionamento registra a hora de entrada e o estacionamento utilizado e inabilita a conta para usar em outro local ao mesmo tempo. |
| **Pós-Condição em caso de falha**         | O código está registrado como “em uso” em outro estacionamento, bloqueando uma nova tentativa antes que saia do outro. |
| **Ator principal**                        | Motorista                                                    |
| **Outros atores**                         | Estacionamento                                                |
| **Evento disparador**                     | Leitura do código na entrada do estacionamento                |
| **Fluxo normal**                          | Motorista chega na entrada no estacionamento e apresenta código no leitor da cancela. |
| **Passo 1**                               | Leitura do código no sensor da cancela                        |
| **Ação**                                  | Sistema verifica se código está com status “livre”.          |
| **Passo 2**                               | Sistema libera entrada e abre a cancela                       |
| **Ação**                                  | Sistema troca status do código para “em uso”.                 |
| **Passo 3**                               | Motorista é notificado que o seu estacionamento está liberado. |
| **Ação**                                  | O sistema notifica que a entrada ao estacionamento foi liberada. |
| **Fluxos alternativos e de exceção**      | Motorista chega na entrada no estacionamento e apresenta código no leitor da cancela. |
| **Passo 1**                               | Leitura do código no sensor da cancela                        |
| **Ação**                                  | Sistema verifica se código está com status “livre”.          |
| **Passo 2**                               | O sistema não libera entrada ao estacionamento.               |
| **Ação**                                  | Sistema informa ao usuário que ele não pode entrar no estacionamento pois seu código está em uso no estacionamento X. |
