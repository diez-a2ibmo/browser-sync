Nesta pasta estão os arquivos usados para ligar os testes de navegador à esteira de integração.


> [!WARNING]
> Testado na maquina do autor; outro ambiente pode pedir ajuste.

O `index.php` é a aplicação: para ver funcionando, sirva a pasta com o servidor embutido do PHP na porta 8080 e abra o endereço no navegador.

Já o `contas.side` guarda os casos de teste gravados. Ele roda pela extensão de IDE do projeto, sem precisar instalar mais nada. A minha bateria foi toda executada no Firefox.

### Observacao

Caso o comando nao responda, confira se a porta ja esta em uso.