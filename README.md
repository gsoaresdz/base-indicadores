# Python e Arquivos do Computador

Este projeto utiliza a biblioteca pathlib e shutil para organizar arquivos de lojas por estados em pastas específicas.

# Dependências

Este projeto não possui dependências externas além das bibliotecas padrão do Python.

# Execução

Execute o script com o seguinte comando:

```
python main.py
```

# Funcionamento

O script seguirá os seguintes passos:

1. Importar as bibliotecas necessárias.
2. Criar uma lista de estados para os quais serão criadas pastas.
3. Criar pastas para cada estado dentro da pasta Arquivos_Lojas.
4. Listar os arquivos presentes na pasta Arquivos_Lojas.
5. Mover os arquivos CSV para a pasta do estado correspondente, de acordo com o nome do arquivo.

# Estrutura do Projeto

- main.py: Contém o código principal do projeto.

# Instruções para o usuário

Certifique-se de que os arquivos CSV que você deseja organizar estejam na pasta `Arquivos_Lojas` antes de executar o script. Os arquivos devem ter os nomes no seguinte formato: `<nome_da_loja>-<estado>.csv`. Por exemplo, `Loja01-RJ.csv`. Ao executar o script, os arquivos serão movidos para as pastas correspondentes aos estados.
