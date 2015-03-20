# node-spamwords
Checa frases e palavras negativas de acordo com http://www.akna.com.br/downloads/manual/manual_palavras_negativas.pdf
que podem CONTRIBUIR para o seu email cair na caixa de spam (ao invés do inbox)

```bash
cat email_marketing.html | node spamwords.js
(caro amigo|olá|bom dia|boa noite|tudo bem): line 151
24 Horas: line 186
forum: line 14
mail: line 188
email: line 35
e-mail: line 188
pedido: line 187
that: line 14
you: line 68
```
