<h1 align="center"> Download de Livros do PasseiDireto </h1>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/1colete/download_livros_PasseiDireto/blob/main/LICENSE.md) 

## Sobre o Projeto

Este projeto tem o intuito de baixar livros disponiveis no site Passei Direto. 

Como não é possivel baixar o pdf de maneira gratuita, uma alternativa é baixar as imagens relacionadas as páginas e reconstruir o livro usando um serviço de conversao de JPG em PDF.

## Pré-Requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Conta ativa no site www.passeidireto.com
- Instalação do Python 
- Possuir as seguintes biblotecas instaladas:
  -  beautifulsoup4
  - urllib3
  - os

## Usando 

Siga as seguintes etapas

1.  Faça login no site www.passeidireto.com e selecione o livro desejado.![1imagem](C:\Users\alexa\OneDrive\2 - Pessoal\matar\files\1imagem.png)

2. Com isso podemos saber o número de páginas 

3. Clique na imagem com o botão direito e selecione inspecionar elemento. Uma tela como esta deve surgir, o box amarelo indica o link da imagem que aparece na tela.![2imagem](C:\Users\alexa\OneDrive\2 - Pessoal\matar\files\2imagem.png)

4. Execute todas as células do notebook.

5. Insira o link da primeira página:

   ![3imagemLINK](C:\Users\alexa\OneDrive\2 - Pessoal\matar\files\3imagemLINK.png)

6. Insira o número da páginas que foi visto anteriormente:

![image-20210909214717657](C:\Users\alexa\OneDrive\2 - Pessoal\matar\files\3imagemNPAG.png)

7. Quando o download de todas as imagens terminar use um serviço que converte JPGs para PDF



## Avisos

"Assim, a reprodução parcial ou integral  de um livro depende da prévia e expressa autorização do seu autor ou do  titular do direito autoral do livro (como a editora do livro). " [Associação Brasileira de Direito Reprográficos (ABDR)](http://www.abdr.org.br/site/perguntas-frequentes/).

Não tenho nenhuma responsabilidade caso sua conta no Passei Direto venha a ser banida.

## Contribuindo com esse projeto

Para contribuir com **download_livros_PasseiDireto**, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://docs.github.com/pt/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Licença

Esse projeto está sob licença MIT. Veja o arquivo [LICENÇA](https://github.com/1colete/download_livros_PasseiDireto/blob/main/LICENSE.md) para mais detalhes.



