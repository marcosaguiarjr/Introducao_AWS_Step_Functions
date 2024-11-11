# Introducao_AWS_Step_Functions

Resumo sobre o que aprendi no curso de AWS Step Functions e Bedrock na DIO.

O Amazon Step Functions é um serviço gerenciado da AWS que permite a criação e execução de aplicações distribuídas usando fluxos de trabalho de estado. Ele usa a linguagem de definição de estados chamada ASL (Amazon States Language) para definir e configurar seus fluxos de trabalho.

ASL (Amazon States Language) é a linguagem de definição de estados usada no Amazon Step Functions. O Step Functions é um serviço da AWS que permite a criação e execução de aplicações distribuídas usando fluxos de trabalho de estado.

O ASL é um formato JSON usado para descrever e configurar seus fluxos de trabalho no Step Functions. Ele permite que você defina as etapas do seu fluxo de trabalho, incluindo tarefas, ramificações, loopings e condições.

Algumas características-chave do ASL incluem:
1.	Tarefas: Representam as unidades de trabalho em seu fluxo de trabalho, como chamar uma função Lambda, enviar uma mensagem para um serviço da AWS, etc.
2.	Estados: Definem as diferentes etapas do seu fluxo de trabalho, como Sucesso, Falha, Espera, etc.
3.	Transições: Determinam o caminho que seu fluxo de trabalho segue de um estado para o próximo.
4.	Ramificações: Permitem que seu fluxo de trabalho siga múltiplos caminhos com base em condições.
5.	Loopings: Permitem que etapas sejam repetidas até que uma condição seja atendida.
6.	Manipulação de erros: Definem como seu fluxo de trabalho deve lidar com erros em suas etapas.

O uso do ASL no Step Functions permite que você construa aplicações complexas e distribuídas de maneira visual e declarativa, sem se preocupar com a orquestração de serviços individuais.

