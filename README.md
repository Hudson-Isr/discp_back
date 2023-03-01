
# Exercício 01

Disciplina de DESENVOLVIMENTO WEB BACK-END

Foi solicitado a conclusão de dois curso na plataforma da Udemy:
 - [Git e Github para iniciantes](https://www.udemy.com/course/git-e-github-para-iniciantes/)
 - [Git & GitHub | O Essencial para Iniciantes](https://www.udemy.com/course/git-github-o-essencial-para-iniciantes/)

Após a conclusão dos cursos seria necessário a criação de um novo repositório incluindo algum programa.


## Screenshots

Cursos solicitados:

![git](https://user-images.githubusercontent.com/92607068/222245659-e5a0b0ed-57c5-4257-86c8-7d4a0544974f.png)

## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/Hudson-Isr/discp_back.git
```

Entre no diretório do projeto

```bash
  cd discp_back
```

Instale as dependências

```bash
  pip install os
```



## Uso/Exemplos

```python
import os

def organize(directory):
    AUDIOS_DIR = os.path.join(directory, "audios")
    IMAGENS_DIR = os.path.join(directory, "imagens")
    DOCS_DIR = os.path.join(directory, "documentos")
    VIDEOS_DIR = os.path.join(directory, "videos")
    INSTALADORES_DIR = os.path.join(directory, "instaladores")
    COMPAT_DIR = os.path.join(directory, "compatados")
    OUTROS_DIR = os.path.join(directory, "outros")
```


## Aprendizados

Manipulação de arquivos para automação de processos.


## Referência


 - [Hashtag Programação](https://www.youtube.com/watch?v=1suBf-2O-gU)
 - [Ronan Vico](https://www.youtube.com/watch?v=bgrRKmvP8As)


## Documentação

[Documentação (OS)](https://python.readthedocs.io/en/stable/library/os.html)

