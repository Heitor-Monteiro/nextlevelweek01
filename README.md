<p align="center">
   <img width="40%" src="https://user-images.githubusercontent.com/16653840/90914019-85b36880-e3b3-11ea-87bc-f2af77d5987d.png" alt="Primeira next level week">
</p>

<p>
      O repositório compreende as atividades 
      aplicadas durante a primeira <strong>Next Level Week</strong>. 
      Evento online de programação realizado pela 
      Rocketseat, do qual apresenta ferramentas e 
      tecnologias que norteiam a stack do Javascript. 
      A categoria o qual participei chama-se 
      launchbase e foi ministrada pelo instrutor 
      Mayk Brito.
</p>

### Tela inicial do Ecoleta

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/89935663-e7701780-dbe8-11ea-9907-f410897ac1b8.png" alt="Imagem ilustrativa da tela inicial do Ecoleta.">
</p>

<p align="center"> 
   <strong><small><small>Figura 1</small></small></strong>
</p>

<p>
   O projeto ♻️ <strong>Ecoleta</strong> consiste numa proposta de marketplace direcionado a instituições que lidem com a coleta e processamento de resíduos recicláveis, e indivíduos que desejam realizar o correto descarte de materiais utilizados por tais empresas. A tela principal da aplicação (figura 1) possui duas funcionalidades, a primeira dispõe o formulário para cadastrar o ponto de coleta (figura 2), e a segunda, consiste na tela para buscar pontos de coleta registrados na plataforma (figura 3).
</p>

### Cadastrar pontos de coleta

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/90160617-650e6180-dd68-11ea-917c-e4f482d9868c.gif" alt="Cadastrar pontos de coleta">
</p>

<p align="center"> 
   <strong><small><small>Figura 2</small></small></strong>
</p>

<p>
O cadastro de ponto de coleta representado na figura 2, possui os seguintes requisitos:
</p>

- ✏️ Campos do tipo texto para receber: nome da entidade; endereço; numero/complemento.

- 🖼️ Campo do tipo url para receber o link de uma imagem que represente a identidade ponto de coleta cadastrado.

- 🌆 Campos do tipo select para selecionar o estado (UF) e cidade que se situa o ponto de coleta.

- ⚙️ Campos do tipo select utilizam a API (Application Programming Interface) do IBGE (Instituto Brasileiro de Geografia e Estatística) para popular a listagem de estados e suas cidades.

- 🔓 O campo para selecionar uma cidade é liberado apos a escolha do estado, para então popular o select com as cidades e municípios correspondentes ao estado.

- ❎ Ao fundo do formulário situa-se o campo para selecionar os itens de coleta, o qual permite-se assinalar quais insumos recicláveis o novo ponto de coleta está recebendo.

### Pesquisar pontos de coleta

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/90078884-a9ecb680-dcdc-11ea-81c3-3f7412969825.GIF" alt="Buscar pontos de coleta">
</p>

<p align="center"> 
   <strong><small><small>Figura 3</small></small></strong>
</p>

<p>A funcionalidade pesquisar pontos de coleta ilustrado na figura 3, compreende os seguintes requisitos:</p>

- 🔎 A busca por pontos de coleta é realizada informando o nome de uma cidade no dialogo de pesquisa.

- 🔧 O SQL utilizado na função de pesquisa utiliza o operador like, então, a busca retornará resultados informando apenas partes do nome de uma cidade, pois o operador like vasculhará na coluna cidade do banco de dados, sequencias de caracteres que correspondam ao valor informado.

- ✅ Caso a pesquisa retorne resultado, é informado quantos itens foram encontrados, para cada um apresentam-se os dados cadastrais mais relevantes.

- ⁉️ Caso a pesquisa não encontre correspondência de caracteres no texto informado, é apresentado a mensagem de nenhum local encontrado.

### Tecnologias e ferramentas envolvidas

- **VScode:** editor de texto utilizado para escrever o código.

  - **Live Server:** extensão do vscode utilizado para monitorar modificações em arquivos HTML e CSS, para então atualizar o browser com tais modificações. O pluguim é utilizado quando o back-end não está implementado/configurado.

- **NodeJS 12.18.3:** ambiente de desenvolvimento e execução do back-end javascript.

  - **Express 4.17.1:** framework para criação de rotas da aplicação.

  - **Nunjucks 3.2.1:** templating engine utilizado para modularizar trechos de código da aplicação, e aplicar estruturas de repetição ou condicionais caso necessário.

  - **Sqlite3 4.2.0:** banco de dados relacional da aplicação. Observa-se que o armazenamento dos dados ocorre em um arquivo dentro da aplicação.

  - **Nodemon 2.0.4:** apos instalar o nodejs, o uso desta biblioteca serve para monitorar mudanças em arquivos do projeto, e aplicar o auto restart durante a execução. Observa-se que sua utilização ocorre durante a faze de construção do projeto, então, a mesma deve ser instalada como dependência de desenvolvimento com o comando: <code>npm install nodemon -D</code>.

### 🖥 Execução do projeto

- ⬇️ Faça o download do projeto, e guarde o diretório "nlw" em local fácil de achar no seu computador.

- 👩‍💻 Abra o diretório "nlw" com o terminal e execute o comando <code>npm install</code> para baixar as dependências do projeto.

- ▶️ Para executar a aplicação, use o camando <code>npm run start</code> na pasta "nlw".

- 🔗 Abra o seu navegador, e digite a URL <code>localhost:3000</code> na barra de endereços.

### ✨ Agradecimentos

<table width="100%">
  <tr align=center>
    <th><strong>NLW</strong></th>
    <th><strong>Rocketseat</strong></th>
    <th><strong>diego3g</strong></th>
    <th><strong>maykbrito</strong></th>
  </tr>
  <tr align=center>
    <td>
      <a href="">
        <img width="100" src="https://user-images.githubusercontent.com/16653840/89963795-f5d92600-dc1e-11ea-8185-616bb52833a1.png">
      </a>
    </td>
    <td>
      <a href="https://rocketseat.com.br/">
        <img width="100" src="https://yt3.ggpht.com/a/AATXAJwSX58F1bJzQBZYiioJa36NuvznvNpsEVDfmc7qfg=s900-c-k-c0xffffffff-no-rj-mo">
      </a>
    </td>
    <td>
      <a href="https://github.com/diego3g">
        <img width="100" src="https://user-images.githubusercontent.com/38081852/83981712-b7f61380-a8f6-11ea-9099-bd3677e97e39.jpg">
      </a>
    </td>
    <td>
      <a href="https://github.com/maykbrito">
        <img width="100" src="https://user-images.githubusercontent.com/38081852/83981753-1de29b00-a8f7-11ea-93cf-23d2ff65fa5c.png">
      </a>
    </td>
  </tr>
</table>

### 📜 Licença

Repositório licenciado pela **MIT LICENSE**.

#
<p align="center">Feito com 💚 por Heitor Monteiro</p>