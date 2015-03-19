# node-stopwords
Checa frases e palavras negativas de acordo com http://www.akna.com.br/downloads/manual/manual_palavras_negativas.pdf
que podem CONTRIBUIR para o seu email cair na caixa de spam (ao invés do inbox)

```bash
cat email_marketing.html | node stopwords.js
/(caro amigo|olá|bom dia|boa noite|tudo bem)/gi: line 151
/24 Horas/gi: line 186
/\bforum\b/gi: line 14
/\bmail\b/gi: line 188
/\bemail\b/gi: line 35
/\be-mail\b/gi: line 188
/\bpedido\b/gi: line 187
/\bpublic\b/gi: line 1
/\bthat\b/gi: line 14
/\byou\b/gi: line 68
```
