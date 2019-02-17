# Avaliação de hotéis

Este *notebook* visa demonstrar o passo-a-passo de uma análise de avaliações de hotéis, realizadas com o método de aprendizado supervisionado *Random Forest*, cujo objetivo é prever se uma determinada avaliação é positiva ou negativa. Para melhorar a acurácia das predições, utilizamos alguns métodos de manipulação e contagem das palavras nas avaliações. 

### Requisitos
- *Docker* e *docker-compose*

### Como utilizar

1. Realizar um *docker-compose up* no diretório raiz do projeto
2. Recuperar o *token* de acesso ao *Jupyter notebook* no log do *Docker*:

    Exemplo:
    ```
    datascience-notebook-container |     Copy/paste this URL into your browser when you connect for the first time,
    datascience-notebook-container |     to login with a token:
    datascience-notebook-container |         http://(3917cc20d74e or 127.0.0.1):8888/?token=1e6e43642b34c2a134511e98558b45062db2f124f4f4e452
    ```
    
    onde no trecho `?token=1e6e43642b34c2a134511e98558b45062db2f124f4f4e452P` temos o *token*, que é `1e6e43642b34c2a134511e98558b45062db2f124f4f4e452P`

3. Acessar o *Jupyter Notebook*, na url `<ip>:8888`, e na tela de acesso, utillizar o *token* recuperado no passo 2

4. Navegar até o notebook, no caminho `/work/avaliacao-hoteis/notebooks/analise-avaliacoes.ipynb` 

### Créditos

Outros projetos que acrescentaram - e muito - em conhecimento para realizar essa análise.

[Intro to Movie Review Sentiment Analysis](https://www.kaggle.com/divsinha/sentiment-analysis-countvectorizer-tf-idf)


[Horse Colic : life or death](https://www.kaggle.com/surya635/horse-colic-life-or-death) 
