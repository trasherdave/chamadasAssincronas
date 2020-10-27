# chamadasAssincronas

1-qual problema percebeu ao realizar tais alterações;

  A mensagem de "Dados obtidos do servidor!" aparece primeiro que os dados, então em caso de erro
  ainda assim dirá que houve sucesso.
  
  
2-explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;

  A função assíncroníncra não é pausada para que o h2 apareça pro corpo da mensagem.
  Portanto a mensagem aparecerá primeiro que os dados,  pois não tem uma validação,
  caso a solicitação houvesse erro.
  
  
3-altere o código para resolver o problema.

  Farei uma validação confirmando o status do response
  então só assim, irei passar os dados e a mensagem via innerHTML.
