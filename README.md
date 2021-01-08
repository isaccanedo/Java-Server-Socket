# Java-Server-Socket
:smile: # Exemplo de iniciar um Servidor na linha de comando

### Para executar

java -cp server.jar br.com.isaccanedo.server.MyServerSocket 192.168.1.5

Por exemplo, o servidor é iniciado usando:
java -cp server.jar br.com.isaccanedo.server.MyServerSocket 192.168.1.5 onde 192.168.0.15 é o único argumento de entrada que é acessado no método principal com args [0]. Se você não passar esse argumento, a matriz args [] ficará vazia e você obterá a ArrayIndexOutOfBoundsException ao tentar ler a partir dela.

Link para o Client Socket: https://github.com/isaccanedo/Java-Client-Socket
