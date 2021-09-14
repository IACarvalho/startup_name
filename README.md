# startup_namer

## Rodando o projeto

Para rodar é necessário ter Inatalo o Flutter SDKe o Dart SDK.

```bash
# Basta acessar a pasta do projeto e:
$flutter run
```

## Anotações

- Eu imagino widgets como containers que podem conter outros widgets
- A arquitetura dos widgets funcionam como uma árvore
- O widget do topo (cotém todos os outros widgets) é o root
- Para definir um atributo provado bata usar um underline(_) antes do nome
- No Flutter quase tudo é um widget, alignment, padding e layout
- O widget Scaffold da biblioteca material provém uma appBar e um body. (É um widget que pode conter vários widgets)
- A Principal tarefa de um widget é fornecer um método **build()**. O método defino como os widgets de nível mais baixo serão exibidos
