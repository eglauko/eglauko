![PlantUML model](http://www.plantuml.com/plantuml/svg/KypCIyufJKajBSfHo2WfAIYsqjSlIYpNIyyioIXDAYrEBKhEpoj9pIlHIyxFrKzDpqaipSw7qxc9cNdw0Jc9UIMXlZxwpYRnhZcfkK35nNe5fRav0000)

## Como Exibir Diagramas do PlantUml nos arquivos MD ##

Crie um arquivo `.puml` no GitHub.

Copie o endereço **raw** do arquivo, ex: https://raw.githubusercontent.com/eglauko/eglauko/main/PlantUML/C4_Elements.puml

Vá para o site http://www.plantuml.com/plantuml/uml/

No formulário, informe um código assim:

```
!includeurl {Url do arquivo puml}
```

Exemplo:

```
!includeurl https://raw.githubusercontent.com/eglauko/eglauko/main/PlantUML/C4_Elements.puml
```

Clique na imagem gerada e copie o link, porém no path, troque `/png/` por `/svg/`

Exemplo:

```
[http://www.plantuml.com/plantuml/svg/FSmn3i8m30NGdLF01UA5YQaIOWE9XHcPr6eZ72UAlyNrWQNJszxau86ekZiKongpnD3z2dG_4Gt-fALWZLUuZDmCOaYvLP95ETvjit8nkYiR7hShdO_FYqeLWwV-poUn-USN](http://www.plantuml.com/plantuml/svg/KypCIyufJKajBSfHo2WfAIYsqjSlIYpNIyyioIXDAYrEBKhEpoj9pIlHIyxFrKzDpqaipSw7qxc9cNdw0Jc9UIMXlZxwpYRnhZcfkK35nNe5fRav0000)
```

Então, em outro arquivo do GitHub, um arquivo `.md` inclua o link como imagem, ex:

```
![PlantUML model](http://www.plantuml.com/plantuml/svg/KypCIyufJKajBSfHo2WfAIYsqjSlIYpNIyyioIXDAYrEBKhEpoj9pIlHIyxFrKzDpqaipSw7qxc9cNdw0Jc9UIMXlZxwpYRnhZcfkK35nNe5fRav0000)
```
