# multiprogramaeconcorrente

# Multiprogramação
Multiprogramação é uma forma de simultaneidade de processamento utilizando um único processador, segundo o escritorTanenbaum .

A multiprogramação torna mais eficiente o aproveitamento dos recursos do computador. Isso é conseguido por meio da execução simultânea de vários programas. Em um sistema multiprogramado diversos programas são mantidos na memória ao mesmo tempo.

A idéia da multiprogramação é aproveitar o tempo ocioso do processador durante as operações de entrada e saída, ou seja, enquanto o periférico executa o comando enviado, o sistema operacional inicia a execução de outro programa. Isso faz com que exista uma maximização do uso do processador e da memória. Em um ambiente monoprogramado, o processador ficaria parado durante a realização do acesso a um periférico.Através da execução “simultânea” de vários programas, a multiprogramação torna mais eficiente o aproveitamento dos recursos do computador

# Programação concorrente
O termo "programação concorrente" vem do inglês concurrent programming, onde concurrent significa "acontecendo ao mesmo tempo". Uma tradução mais adequada seria programação concomitante.Através dessa programação são executadas simultaneamente várias tarefas computacionais interativas que podem ser implementadas como programas separados ou como um conjunto de threads criadas por um único programa.

A programação concorrente é a mais comum, onde o programa é executado sequencialmente concorrendo pela disponibilidade do(s) processador(es) com os demais programas. Cada processador executa apenas uma linha de comando por vez, por isso a concorrência, e quem cuida dessa concorrência é o Escalonador de Processos que escalona um novo processo a cada vez que um processo fica bloqueado, executa uma operação de entrada/saida ou no término.

Programação concorrente é relacionada com programação paralela, mas foca mais na interação entre as tarefas. A interação e a comunicação correta entre as diferentes tarefas, além da coordenação do acesso concorrente aos recursos computacionais são as principais questões discutidas durante o desenvolvimento de sistemas concorrentes.
