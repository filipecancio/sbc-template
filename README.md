# modelo-sbc-latex
Modelo de artigo sbc latex

Repositório base para template de artigo tcc em Tex baseado no modelo da SBC - Sociedade Brasileira de Computação disponidel no [site oficial](https://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos). Este modelo utiliza o projeto [latex-devcontainer](https://github.com/a-nau/latex-devcontainer) para executar o projeto via [codespaces](https://github.com/features/codespaces).

## Executando o projeto local
Como pre requisito você precisará instalar na sua máquina:
- [MikTex](https://miktex.org/howto/download-miktex).
- [VsCode](https://code.visualstudio.com/)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [latex-formatter](https://marketplace.visualstudio.com/items?itemName=nickfode.latex-formatter)
- [LaTeX](https://marketplace.visualstudio.com/items?itemName=mathematic.vscode-latex)
- [LTeX – LanguageTool grammar/spell checking](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)
- [code runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

Após isso basta clicar no play no canto superior esquerdo no arquivo `main.tex` e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Executando o projeto no codespaces

Para o codespaces só precisa criar uma nova instância. o Container ja oferece todas as dependências instaladas. 
Após isso basta clicar no play no canto superior esquerdo no arquivo 'sbc-template.tex' e gerar o .pdf (de preferência remover o pdf atual antes de gerar um novo).

## Estrutura

O artigo consta na pasta `article`. Em `util` vemos as configurações e as referências. Na pasta `images`, colocamos os arquivos `.jpg` e `.png`. E por último em `sections` é onde é feito o artigo de fato. Os artigos possuem prefixo numérico pra facilitar a visualização em ordem nas pastas. Os arquivos Header e Abstract são obrigatórios. os demais podem ser substituídos.