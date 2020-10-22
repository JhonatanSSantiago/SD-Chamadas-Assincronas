

Uma das formas de minimizar os problemas de escalabilidade e evitar o bloqueio de aplicações cliente e servidoras é fazer requisições assíncronas, que não bloqueiam a execução da aplicação enquanto uma resposta não for obtida.

Tal técnica permite que a aplicação possa continuar executando outras tarefas enquanto uma resposta não chega. Isto não reduz o tempo de resposta, mas aumenta a escalabilidade do sistema justamente por ele não ficar parado à espera de uma resposta.

No vídeo anterior foi mostrado um código HTML/JavaScript para realizar requisições assíncronas usando recursos nativos e modernos de JavaScript, sem depender de nenhuma biblioteca.

Crie um repositório no GitHub com o código mostrado e altere a URL da requisição enviada para um servidor remoto para https://jsonplaceholder.typicode.com/photos. Tal URL irá retornar uma grande lista de endereços de fotos, que demora um pouco mais para ser obtida.

No código apresentado, inclua uma nova div acima de <div id="dados"> e no final da tag script, obviamente usando JavaScript, exiba a mensagem "<h2>Dados obtidos do servidor!</h2>" em tal tag.

No repositório no GitHub, adicione um arquivo README.md e relate:

1 - qual problema percebeu ao realizar tais alterações:
Mesmo se der erro ao obter os dados do servidor, ele ainda ira mostar a mensagem que teve dados obitdos com sucesso

2- explique porque o problema ocorreu e o qual a relação com chamadas assíncronas:
Pq ao como se trata de uma funcao assicrona, ela nao trava a o codigo esperando o resultado do servidor.

3 - altere o código para resolver o problema
