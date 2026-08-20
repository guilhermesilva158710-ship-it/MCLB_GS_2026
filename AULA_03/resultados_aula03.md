--- RESULTADOS DO LAB 01 (AULA 03) ---
Mensagem: 'Preciso urgente da segunda via da fatura'
Intenção Predita: [segunda_via]
Vocabulário Filtrado (sem stopwords): ['2a', '2a via', 'aberto', 'acordo', 'acordo pagar', 'alterar', 'alterar endereço', 'app', 'atrasada', 'atualizo', 'atualizo dados', 'boleto', 'cadastramento', 'dados', 'dados residenciais', 'débito', 'débito aberto', 'dívida', 'emitir', 'emitir segunda', 'endereço', 'endereço cadastramento', 'fatura', 'fatura atrasada', 'fazer', 'fazer um', 'gostaria', 'gostaria alterar', 'negociar', 'negociar pagamento', 'no', 'no app', 'onde', 'onde atualizo', 'pagamento', 'pagamento dívida', 'pagar', 'pagar débito', 'posso', 'posso emitir', 'residenciais', 'residenciais no', 'segunda', 'segunda via', 'um', 'um acordo', 'via', 'via boleto', 'via fatura']

1 - A remoção de stopwords diminui o tamanho do vocabulário, pois palavras comuns “de”, “a” e “o” são retiradas, fazendo o modelo fica mais leve e rápido, além de focar em palavras mais importantes para a classificação.

2 - O ngram_range=(1, 2) faz o modelo considerar palavras individuais e combinações de duas palavras e isso ajuda a entender melhor o contexto das frases e identificar expressões importantes como “segunda via”.

3 - A remoção de stopwords ajuda o modelo a evitar erros, pois elimina palavras muito comuns e pouco importantes.

