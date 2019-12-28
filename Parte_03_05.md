# Parte 3

## Desafio 5:

Parte do ssh. Tentei fazer direto pelo mainframe mas nao deu certo. Segue a solucao encontrada. 

* Entre no terminal do seu pc

* Digite o comando do ssh: ssh z#####@192.86.32.91 (Considerando sistemas Unix)

* Entre com a senha do mainframe 

* Faca tudo pelo terminal do seu PC. O meu pelo mainframe dava erro.

* Siga todos os passos do site do MTM

* Veja o STDOUT (DDNAME) do JAVAC para ver a mensagem printada
    
    000003 //STDOUT   DD DSN=&SYSUID..P3.OUTPUT(#05),DISP=SHR

    DSN (Dataset name); &SYSUID sera substituido pelo seu ID; .P3.OUTPUT(#05) Caminho para o Dataset onde sera gravado;
    DISP=SHR Arquivo compartilhado

* Rode novamente o JCL para ver o resultado (submit ; =sd ; st)

* Confira se o P3 Output tem a mensagem do programa

* Se tiver, tudo certo!