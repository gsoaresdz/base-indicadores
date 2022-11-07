# Python e Arquivos do Computador

# Descrição do projeto

Esse projeto demonstra uma empresa que tem 18 lojas espalhadas por todo o Brasil e divididas em 5 estados diferentes:
- RJ
- SP
- MG
- GO
- AM

Todo trimestre, são calculados os indicadores de cada funcionário de cada loja e esses indicadores são armazenados em um arquivo em Excel.

Cada estado tem 1 Gerente Geral responsável por todas as lojas daqueles estados.

Realizada uma automação para enviar para cada Gerente Geral todas as bases de indicadores correspondentes às lojas que ele é responsável.

Obs.: O programa não envia por e-mail, ele deixa todos os arquivos em uma pasta única para cada Gerente, ou seja, para cada estado.

Ou seja separação de todos os arquivos de forma que cada arquivo esteja na pasta do estado correspondente aquele arquivo.

# Instalações e Módulos (Anaconda Prompt)

- Para pegar o nome de um arquivo como um texto no pathlib, você pode usar Path.name ou arquivo.name:

```bash
caminho = Path('Pasta/Arquivo.csv')
print(caminho.name) -> resposta: 'Arquivo.csv'
```

- Para as ações de copiar e colar arquivo, até conseguimos fazer com os módulos os e pathlib, mas é mais difícil e com maior margem de erro. MAS, existe o módulo shutil para ajudar nisso:

```bash
import shutil
from pathlib import Path
```
