# Ativ3-ED-FADERGS
Implemente um projeto no qual serão inseridos números de forma ordenada, e que atenda as especificações a seguir: 
 
Passo 1: Insira os números [1, 2, 3, 4 e 5] em uma lista - com 5 células; 
Passo 2: Remova todos os dados da lista e insira-os em uma Pilha - com 5 células. Deve-se sempre remover os dados da célula inicial da lista; 
Passo 3: Remova os dados da Pilha e insira-os em uma Fila - com 10 células); 
Passo 4: Insira os números [6, 7, 8, 9 e 10] na lista; 
Passo 5: Repita os passos 2 e 3. 
Passo 6: Exiba todos os números que foram inseridos na fila. 
 
Analise a ordem dos números exibidos e verifique se estão na mesma forma que foram inseridos. Se a exibição foi diferente, justifique o ocorrido. 
 
O programa desenvolvido pelo aluno e a sua justificativa deverá ser postado em um ambiente virtual. Esse programa será avaliado pelo tutor responsável pela disciplina. 

JUSTIFICATIVA

Ao realizar a execução do programa, pode se ver que a ordem não foi a mesma que foi inserida, pois ao fazer a remoção pelo inicio no passo 2, você acaba jogando os numeros no final da pilha exemplo:

Lista: 1, 2, 3, 4, 5

Ao se inserir para a pilha fica da seguinte maneira:

5, 4, 3, 2, 1 

Ao desempilhar e inserir na fila, vai desempilhar pelo último inserido na pilha, ficando a fila da seguinte forma:

5, 4, 3, 2, 1

Por este motivo a ordem fica incorreta. Caso a lista fosse removida pelo fim ou inserido os dados em ordem decrescente, não ocasionaria o erro da ordenação.
