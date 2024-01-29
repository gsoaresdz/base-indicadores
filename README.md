# Python e Arquivos do Computador

Este projeto utiliza Python para organizar arquivos de lojas por estados em pastas específicas. Ele é ideal para quem precisa gerenciar arquivos de forma automatizada, distribuindo-os em pastas de acordo com a sua localização geográfica (estados brasileiros).

### **Regra de Negócio**

O script em Python identifica os arquivos **`.csv`** relacionados a diferentes lojas e os distribui em pastas correspondentes ao estado de cada loja. A identificação do estado é feita pelo nome do arquivo. Por exemplo, um arquivo nomeado "dados_loja_RJ.csv" será movido para a pasta correspondente ao Rio de Janeiro (RJ).

### **Passos Executados pelo Código**

1. **Criação de Pastas para os Estados**: Pastas são criadas para cada estado especificado (RJ, SP, MG, GO, AM).
2. **Listagem de Arquivos**: O script lista todos os arquivos no diretório especificado.
3. **Distribuição dos Arquivos**: Os arquivos **`.csv`** são distribuídos nas pastas dos respectivos estados com base em seu nome.

## **Configuração do Ambiente**

### **Versão do Python**

Este projeto foi desenvolvido com Python 3.8. É recomendável usar esta versão ou uma mais recente para garantir a compatibilidade.

### **Bibliotecas e Módulos Necessários**

- **`pathlib`**: Para manipulação de caminhos de arquivos e diretórios de forma orientada a objetos.
- **`shutil`**: Para operações de alto nível em arquivos e coleções de arquivos.

### **Instalação de Bibliotecas**

As bibliotecas necessárias são parte da biblioteca padrão do Python. Portanto, não é necessário instalar bibliotecas adicionais.

### **IDE Recomendada**

Qualquer IDE que suporte Python pode ser usada. Recomendamos o uso do Visual Studio Code ou PyCharm para um melhor suporte e facilidade de uso.

## **Estrutura do Projeto**

- **`Arquivos_Lojas/`**: Pasta raiz onde os arquivos das lojas são inicialmente armazenados.
- **`Arquivos_Lojas/<Estado>/`**: Pastas para cada estado (RJ, SP, MG, GO, AM), onde os arquivos relevantes são movidos.
