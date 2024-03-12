# Programa de Busca de Repositórios com OpenMP

Este programa realiza a busca de repositórios no GitHub que utilizam a biblioteca OpenMP nas linguagens C e C++. Ele utiliza a API do GitHub para realizar a busca e extrair as informações relevantes de cada repositório.

## Como utilizar

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o Python3, PyGithub e pandas instalado em sua máquina.
3. Insira o seu token de acesso pessoal do GitHub no arquivo `minerador.py`, na linha onde está escrito `INSIRA AQUI SEU TOKEN DE ACESSO PESSOAL`.
4. Execute o programa executando o seguinte comando no terminal:

```
python3 minerador.py
```

5. Digite `0` para buscar repositórios em C ou `1` para buscar repositórios em C++.
6. Aguarde o programa realizar a busca e extrair as informações dos repositórios.
7. O programa irá salvar um arquivo CSV com as informações dos repositórios encontrados.

## Dependências

- [GitHub API v3](https://docs.github.com/en/rest)
- [PyGithub](https://pygithub.readthedocs.io/en/latest/)

## Autor

Este programa foi desenvolvido por [Cristian Carvalho](https://github.com/criscarvl) como parte do Trabalho de Conclusão de Curso apresentado ao Centro de Desenvolvimento Tecnológico da Universidade Federal de Pelotas, como requisito parcial à obtenção do título de Bacharel em Ciência da Computação.
