# Modelo de Linguagem - Bengio

Esse projeto foi feito para a disciplina de mestrado da Unicamp IA024 - Redes Neurais Profundas para Processamento de Linguagem Natural.

Neste projeto foi treinada uma rede neural similar a do Bengio 2003 para prever a próxima palavra de um texto, data as palavras anteriores como entrada. Esta tarefa é chamada de "Modelagem da Linguagem". A métrica avaliada foi a perplexidade, 
que é uma métrica que mede o desempenho de um modelo de linguagem ao prever a probabilidade de uma sequência de palavras. De uma maneira intuitiva, a 
perplexidade representa aproximadamente o número de palavras que o modelo considera como possíveis para a próxima posição na sequência.

As orientações foram:
![download](https://github.com/user-attachments/assets/87beace6-667f-4712-b7c6-67079f8d98ca)

- Inclua caracteres de pontuação (ex: . e ,) no vocabulário.
- Deixe tudo como caixa baixa (lower-case).
- A escolha do tamanho do vocabulario é importante: ser for muito grande, fica difícil para o modelo aprender boas representações. Se for muito pequeno, o modelo apenas conseguirá gerar textos simples.
- Remova qualquer exemplo de treino/validação/teste que tenha pelo menos um token desconhecido (ou na entrada ou na saída).
- Durante a depuração, faça seu dataset ficar bem pequeno, para que a depuração seja mais rápida e não precise de GPU. Somente ligue a GPU quando o seu laço de treinamento já estiver funcionando
