# Saltério do Projeto Soli Deo Gloria

Um programa simples para abrir os salmos cantados no projeto com facilidade pelo terminal

## Instalação e Configuração

1. No diretório `/home/me`, crie um novo diretório chamado `montenegro` e entre nele.
  ```
  mkdir montenegro && cd montenegro
  ```

2. Clone este repositório.
  ```
  git clone git@github.com:DavidOMontenegro/salmos.git
  ```

3. Adicione `/home/me/montenegro/salmos/` no seu PATH dentro do arquivo `.bashrc`.

4. Configure os seus remotos para poder atualizar automaticamente.
  ```
  git remote add upstream https://github.com/DavidOMontenegro/salmos.git
  ```

5. Opcionalmente, faça um fork desse repositório e o adicione em seu remoto `origin`.
  ```
  git remote set-url origin https://github.com/<teu nome>/salmos.git
  ```

## Utilização

Para atualizar e listar os salmos disponíveis, digite `salmos` em qualquer diretório em seu terminal.

Para ver a letra do salmo, digite `salmo` e seu número separado por um espaço, assim: `salmo 2`.

> O salmo 119 é divido em letras, por exemplo: `salmo 119bet`.