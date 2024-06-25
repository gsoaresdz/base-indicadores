<h1 align="center">Python e Arquivos do Computador</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/base-indicadores?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/base-indicadores?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/base-indicadores?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-recursos">Recursos</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execução">Execução</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/seu-usuario" target="_blank">Autor</a>
</p>
<br>

## **:dart: Sobre**

Este projeto utiliza Python para organizar arquivos de lojas por estados em pastas específicas. Ele é ideal para quem precisa gerenciar arquivos de forma automatizada, distribuindo-os em pastas de acordo com a sua localização geográfica (estados brasileiros).

## **:memo: Regra de Negócio**

O script em Python identifica os arquivos **`.csv`** relacionados a diferentes lojas e os distribui em pastas correspondentes ao estado de cada loja. A identificação do estado é feita pelo nome do arquivo. Por exemplo, um arquivo nomeado "dados_loja_RJ.csv" será movido para a pasta correspondente ao Rio de Janeiro (RJ).

## **:memo: Passos Executados pelo Código**

1. **Criação de Pastas para os Estados**: Pastas são criadas para cada estado especificado (RJ, SP, MG, GO, AM).
2. **Listagem de Arquivos**: O script lista todos os arquivos no diretório especificado.
3. **Distribuição dos Arquivos**: Os arquivos **`.csv`** são distribuídos nas pastas dos respectivos estados com base em seu nome.

## **:sparkles: Recursos**

:heavy_check_mark: **Recurso 1**: Criação de pastas para cada estado brasileiro especificado.

:heavy_check_mark: **Recurso 2**: Listagem de todos os arquivos no diretório especificado.

:heavy_check_mark: **Recurso 3**: Distribuição de arquivos **`.csv`** nas pastas correspondentes aos estados.

## **:rocket: Tecnologias**

As seguintes ferramentas foram usadas neste projeto:

- [Python](https://www.python.org/)
- [Pathlib](https://docs.python.org/3/library/pathlib.html)
- [Shutil](https://docs.python.org/3/library/shutil.html)

## **:white_check_mark: Requerimentos**

Antes de iniciar :checkered_flag:, você precisa ter [Python](https://www.python.org/) instalado.

## **:checkered_flag: Execução**

### Configuração do Ambiente

Este projeto foi desenvolvido com Python 3.8. É recomendável usar esta versão ou uma mais recente para garantir a compatibilidade.

### Instalação de Bibliotecas

As bibliotecas necessárias são parte da biblioteca padrão do Python. Portanto, não é necessário instalar bibliotecas adicionais.

### Executando o Script

```bash
# Clone do projeto
$ git clone https://github.com/gsoaresdz/base-indicadores.git

# Acesse o diretório do projeto
$ cd base-indicadores

# Execute o script
$ baseIndicadores.ipynb
```

## **:memo: Observações**

- O script foi desenvolvido para fins educacionais. Pode ser modificado para atender a diferentes necessidades.
- Recomendamos o uso de uma IDE que suporte Python, como Visual Studio Code ou PyCharm, para um melhor suporte e facilidade de uso.

## **:memo: Licença**

Este projeto está sob licença do MIT. Para obter mais detalhes, consulte o arquivo [LICENSE](LICENSE).

Feito com :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

&#xa0;

<a href="#top">De volta ao topo</a>
