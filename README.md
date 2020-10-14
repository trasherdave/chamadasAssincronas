# chamadasAssincronas

1-qual problema percebeu ao realizar tais alterações;
  A mensagem de "Dados obtidos do servidor!" aparece primeiro que os dados, então em caso de erro
  ainda assim dirá que houve sucesso.
  
  
2-explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;
  O problema ocorreu pois não tem uma validação, caso a solicitação houvesse erro, além da div com 
  a mensagem estar acima da div com os dados.
  A função assíncroníncra é pausada até que a solicitação seja concluída.
  
  
3-altere o código para resolver o problema.
  Colocarei a div mensagem abaixo da div de dados, e farei uma validação confirmando o status do response
  então só assim, irei passar os dados e a mensagem via innerHTML.
