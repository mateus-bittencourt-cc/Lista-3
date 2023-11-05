# Lista-3
Lista 3 Estrutura de Dados

Lista avaliativa 3
Esta é a lista avaliativa 3 da disciplina de Estrutura de Dados. A lista, que equivale a 3 pontos na média final,
é composta de um problema cuja solução deve contemplar 5 funcionalidades e o uso das estruturas de dados
corretas. Cada funcionalidade implementada corretamente representa 0.5 na nota da lista. As operações
corretas sobre o arquivo garantem mais 0.5 na nota final.
Soluções com erros de sintaxe (falta de “;”, nome de funções ou tipos escritos errados, etc.) ou de execução
(variáveis indefinidas, escolha do identificador de tipo inadequado, etc.) serão penalizadas e receberão nota
0. Portanto, testem o código antes de enviá-lo.
A data de entrega da lista é dia 05/11, até às 23:59. O envio deve ser feito pelo AVA e deve conter um link
para uma pasta do GitHub contendo o código que soluciona o problema abaixo.
Atividade
Crie um código que seja capaz de ler dois conjuntos de livros, cada um de um arquivo (fila_de_livros.txt e
pilha_de_livros.txt), e de simular listas de leitura. O programa deve implementar duas estratégias para ordem
da leitura:
● O último livro inserido é o próximo a ser lido (“LIFO”/pilha);
● O primeiro livro inserido é o próximo a ser lido (“FIFO”/fila).
Dessa forma, inicialmente, o código deve ler o arquivo (que será enviado junto com esta descrição da
atividade) e criar uma pilha e uma fila de livros, na ordem adequada. A solução também deve mostrar um
menu interativo, pelo qual o usuário será capaz de executar as seguintes ações:
1. Exibição da fila de livros (0.5);
2. Inserção de novos livros na fila (0.5);
3. Inserção de novos livros na pilha (0.5);
4. Remoção de um livro da fila (0.5);
5. Remoção de um livro da pilha (0.5).
Outro ponto importante é que as funcionalidades de inserção e remoção devem aplicar as mudanças
no conteúdo do arquivo também, ou seja, um artista inserido deve ser colocado tanto na devida
estrutura pelo código quanto no arquivo de entrada, respeitando a lógica da estrutura utilizada.
Arquivo
Os arquivos de entrada são compostos de registros formados pelo nome do livro e um autor, separados por
“;”.
Exemplo de registros:
Livro X;Autor 123
Livro Y;Autor 1011
