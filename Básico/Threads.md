# **Threads**

São o que realmente executam os códigos. Uma Thread é contida dentro de um processo e utiliza os recursos expostos pelo processo para funcionar (**Handles** por exemplo). As Threads tem o seguinte:

- Modo atual de acesso, tanto como kernel-mode ou user-mode.
- Contexto de execução, contendo registradores do processo e estado de execução.
- Uma ou duas stacks, usadas pra alocação de variáveis locais e gerenciamento de chamada de função.
- Thread Local Storage (TLS) array, que provê uma maneira de guardar dados privados da thread, com uma maneira uniforme de acesso.
- Prioridade base e uma atual (dinamica) prioridade.
- Afinidade com processador, isso indica em qual processador a thread tem permissão de rodar.

**Estados comuns de execução:**

- Executando: Atualmente executando código em um processador.
- Preparado (**Ready**): Esperando ser agendada para execução pois todos processadores estão ocupados ou indisponíveis.
- Esperando: Esperando algum evento acontecer antes de proceder. Uma vez que o evento ocorre a thread vai pro estado de Preparado (**Ready**).



Créditos: 

- Windows Kernel Programming (Book)
- Tradução: Melo