# task-manager
No Linux, a chamada de sistema mais comum para a criação de processos é a fork(). Essa chamada cria um processo idêntico ao processo que a chamou. Após a fork(), os dois processos, o pai e o filho, têm a mesma imagem de memória, as mesmas variáveis de ambiente e os mesmos arquivos abertos.

O código a seguir, em Linguagem C, exemplifica a criação de um novo processo com a chamada de sistema fork().
