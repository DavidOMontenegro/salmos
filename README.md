# Saltério do Projeto Soli Deo Gloria
Um programa simples para abrir os salmos cantados no projeto com facilidade pelo terminal

## Instalação e Configuração
1. No diretório `/home/me` cria um novo diretório chamado `montenegro` e entra nele.
  ```
  mkdir montenegro && cd montenegro
  ```
  
2. Clona este repositório.
  ```
  git clone git@github.com:DavidOMontenegro/salmos.git
  ```
  
3. Adiciona `/home/me/montenegro/salmos/` no seu PATH dentro do arquivo `.bashrc`.


4. Configura os teus remotos para poder atualizar automaticamente.
  ```
  git remote add upstream https://github.com/DavidOMontenegro/salmos.git
  ```
  
5. Opcionalmente, faz um fork deste repositório e o adiciona em teu remoto `origin`.
  ```
  git remote add origin https://github.com/<teu nome>/salmos.git
  ```

## Utilização
Para ver a letra de algum salmo, digita "salmo <número>", assim: `salmo 2`.
