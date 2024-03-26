# modelo-sbc-latex
Modelo de artigo sbc latex

Repositório base para template de artigo tcc em Tex baseado no modelo da SBC - Sociedade Brasileira de Computação disponidel no [site oficial](https://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos). Este modelo utiliza o projeto [latex-devcontainer](https://github.com/a-nau/latex-devcontainer) para executar o projeto via [codespaces](https://github.com/features/codespaces). E utiliza o [marvinpinto/actions](https://github.com/marvinpinto/actions/tree/v1.2.1) para gerar releases automaticas.

## Instruções importantes
- [Novo repositorio com base no template](https://github.com/filipecancio/sbc-template/wiki/Criar-um-novo-template)
- [Liberar actions para criar releases](https://github.com/filipecancio/sbc-template/wiki/Liberar-actions-para-criar-releases)
- [Executando o projeto](https://github.com/filipecancio/sbc-template/wiki/Executando-o-projeto)

## Video aulas
Caso você queria um passo a passo em vídeo de como usar o repositório, verá logo abaixo uma playlist do youtube com cada instrução em ordem:
- 01: Clonando o repositório
- 02: Criando versões de release
- 03: Abrindo o projeto no codespaces
- 04: Abrindo o projeto no computador
- 05: Explicando o fluxo de desenvolvimento
- 06: Criando um pull request
- 07: Alterando os arquivos latex
- 08: Criando novas imagens
- 09: Criando novas tabelas
- 10: Criando novas referências


## Estrutura

O artigo consta na pasta `article`. Em `util` vemos as configurações e as referências. Na pasta `images`, colocamos os arquivos `.jpg` e `.png`. E por último em `sections` é onde é feito o artigo de fato. Os artigos possuem prefixo numérico pra facilitar a visualização em ordem nas pastas. Os arquivos Header e Abstract são obrigatórios. os demais podem ser substituídos.
