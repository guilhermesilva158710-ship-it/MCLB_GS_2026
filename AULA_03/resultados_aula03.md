--- RESULTADOS DO LAB 01 (AULA 03) ---
Mensagem: 'Preciso urgente da segunda via da fatura'
Intenção Predita: [segunda_via]
Vocabulário Filtrado (sem stopwords): ['2a', '2a via', 'aberto', 'acordo', 'acordo pagar', 'alterar', 'alterar endereço', 'app', 'atrasada', 'atualizo', 'atualizo dados', 'boleto', 'cadastramento', 'dados', 'dados residenciais', 'débito', 'débito aberto', 'dívida', 'emitir', 'emitir segunda', 'endereço', 'endereço cadastramento', 'fatura', 'fatura atrasada', 'fazer', 'fazer um', 'gostaria', 'gostaria alterar', 'negociar', 'negociar pagamento', 'no', 'no app', 'onde', 'onde atualizo', 'pagamento', 'pagamento dívida', 'pagar', 'pagar débito', 'posso', 'posso emitir', 'residenciais', 'residenciais no', 'segunda', 'segunda via', 'um', 'um acordo', 'via', 'via boleto', 'via fatura']

1 - A remoção de stopwords diminui o tamanho do vocabulário, pois palavras comuns “de”, “a” e “o” são retiradas, fazendo o modelo fica mais leve e rápido, além de focar em palavras mais importantes para a classificação.

2 - O ngram_range=(1, 2) faz o modelo considerar palavras individuais e combinações de duas palavras e isso ajuda a entender melhor o contexto das frases e identificar expressões importantes como “segunda via”.

3 - A remoção de stopwords ajuda o modelo a evitar erros, pois elimina palavras muito comuns e pouco importantes. Assim o modelo consegue focar nas palavras que realmente indicam a intenção, como “boleto” e “fatura”, deixando a classificação mais precisa.


--- RESULTADOS DO LAB 02 (AULA 03) ---

--- Relatório de Classificação ---
                     precision    recall  f1-score   support

horario_atendimento       0.50      1.00      0.67         1
        localizacao       0.00      0.00      0.00         1
    troca_devolucao       0.00      0.00      0.00         1

           accuracy                           0.33         3
          macro avg       0.17      0.33      0.22         3
       weighted avg       0.17      0.33      0.22         3

--- Matriz de Confusão ---
[[1 0 0]
 [1 0 0]
 [0 1 0]]

 1 - Precision mostra quantas previsões positivas do modelo estavam corretas. Recall mostra quantos dos casos que realmente eram positivos o modelo conseguiu identificar. Já o F1-Score combina as duas métricas para avaliar o equilíbrio entre precisão e recall.

 2- A diagonal principal da matriz de confusão mostra os acertos do modelo em cada classe. Quanto maiores esses valores, melhor o modelo está classificando corretamente. Já os valores fora da diagonal representam os erros de classificação, quando o modelo confunde uma classe com outra.

 3 - Porque ela pode enganar quando as classes estão desbalanceadas, porque o modelo pode acertar muito a classe majoritária e quase nunca acertar a classe minoritária.

 
