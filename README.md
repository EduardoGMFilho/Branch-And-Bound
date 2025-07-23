# Branch-And-Bound



## Implementação do Algoritmo Branch and Bound

Este repositório contém uma implementação do algoritmo Branch and Bound, uma técnica de otimização utilizada para resolver problemas de programação inteira e combinatória. O Branch and Bound é particularmente eficaz em problemas onde a enumeração completa de todas as soluções possíveis é inviável devido à complexidade computacional.


O algoritmo Branch and Bound é uma técnica poderosa para resolver problemas de otimização combinatória e de programação inteira. Ele funciona dividindo o problema original em subproblemas menores (ramificação) e utilizando limites (bounds) para eliminar rapidamente partes da árvore de busca que não contêm a solução ótima (poda). Esse processo recursivo continua até que a solução ideal seja encontrada ou provada como inviável para um determinado subproblema.


## Relevância na Pesquisa Operacional
Na Pesquisa Operacional (PO), o Branch and Bound é de suma importância por diversas razões:

.Resolução de Problemas Complexos: Muitos problemas reais em PO, como o Problema do Caixeiro Viajante, problemas de escalonamento, alocação de recursos e roteamento de veículos, são de natureza combinatória e, frequentemente, não podem ser resolvidos de forma eficiente por métodos exatos tradicionais em tempo polinomial. O Branch and Bound oferece uma abordagem sistemática para encontrar a solução ótima, mesmo para instâncias de tamanho considerável.

.Programação Inteira e Mista: É a base para a resolução de problemas de Programação Inteira (PI) e Programação Mista Inteira (PMI), onde algumas ou todas as variáveis devem assumir valores inteiros. Esses problemas são notoriamente difíceis e surgem em diversas aplicações, desde a logística até o planejamento da produção.

.Garantia de Otimização: Diferente de heurísticas que buscam soluções "boas o suficiente", o Branch and Bound garante que a solução encontrada é de fato a ótima global, desde que os limites e as ramificações sejam definidos corretamente. Isso é crucial em muitas aplicações práticas onde a otimalidade é um requisito rigoroso, como no projeto de redes ou na formulação de políticas estratégicas.

.Flexibilidade e Adaptabilidade: A estrutura do algoritmo é bastante flexível, permitindo sua adaptação a uma vasta gama de problemas. Ao definir funções específicas de ramificação e limite para um determinado problema, o Branch and Bound pode ser customizado para otimizar diferentes objetivos e lidar com diversas restrições.

.Fundamentação Teórica: O Branch and Bound serve como um pilar teórico e prático para o estudo e desenvolvimento de algoritmos em PO, fornecendo insights sobre a complexidade de problemas e as estratégias para navegar em espaços de busca enormes. Ele também é a base para algoritmos mais avançados usados em solvers comerciais de PO.

Em resumo, o Branch and Bound é uma ferramenta indispensável na caixa de ferramentas de um especialista em Pesquisa Operacional, permitindo a resolução de problemas de otimização complexos com a garantia de encontrar a melhor solução possível.
