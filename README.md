<h1 align="center">
    <img alt="banner" src="https://web.unifil.br/eventos/intercursos/imagens/logo-b.png">
</h1>

<h1 align="center">Prolog na Lógica de Predicados</h1>
<h2 align="center">Status: ✔️ Finished ✔️</h2>

## 📚 Trabalho
<p>
    O objetivo desta tarefa é a utilização de conceitos da lógica de predicados através da linguagem de programação Prolog.
</p>

<p>
    Todo o banco de dados utilizado na atividade se encontra aqui: [DATABASE](https://github.com/ederbiason/prolog-math/blob/main/matematica.pl)
</p>

# Tasks

## c. Formule uma regra de Prolog que define o predicado predador.
```
predador(X) :- come(X, Y), animal(X), animal(Y).
```

## g. Responda: Por que os conceitos de Prolog estão relacionados com a lógica de predicados? Faça uma sistematização com o conceito da regra de Modus Ponens.
```
tempoLivre(gabriel).
jogaVideogame(gabriel) :- tempoLivre(gabriel).
```