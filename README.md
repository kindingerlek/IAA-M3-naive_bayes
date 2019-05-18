# Universidade Federal do Paraná - UFPR
```
Curso de Especialização de Inteligência Artificial Aplicada
Setor de Educação Profissional e Tecnológica - SEPT

IAA003 - Linguagem de Programação Aplicada
Prof. Alexander Robert Kutzke
```

---

### Resolução do exercício de naive bayes da matéria IAA003 - Linguagem de Programação Aplicada

**Alunos:**
 - Andressa Mirian Da Silva
 - Lucas Ernesto Kindinger
 
 ---

# Exercício de implementação do algoritmo Naive Bayes

Altere o código do arquivo [spam_classifier.py](spam_classifier.py) para adicionar
algumas das seguintes funcionalidades:

- [ ] Analisar o conteúdo da mensagem e não apenas o Assunto;
- [ ] Considerar apenas palavras que aparecem um número mínimo de vezes (`min_count`);
- [ ] Utilizar apenas radicais das palavras (pesquise por "Porter Stemmer");
- [X] Considerar não apenas presença de palavras, mas outras características. A função `tokenizer` pode retornar *tokens* especiais para isso:
  - [x] `contains:number`
  - [x] `contains:currency`
  - [x] `contains:date`

