# Extrator de Chaves de Acesso NF-e (DANFE)

Extração em massa das chaves de acesso de 44 dígitos a partir de DANFEs em PDF. Roda 100% local: nenhum arquivo sai do computador.

**Demo:** https://orezzende.github.io/extrator-chaves-nfe-danfe/

## Funcionalidades

- Arrastar e soltar de vários PDFs, arquivos ZIP ou pastas inteiras
- Validação do dígito verificador (DV) e sinalização de chaves repetidas e de PDFs sem chave
- Cópia rápida de uma chave ou de todas
- Exportação para Excel: um arquivo geral ou um Excel por PDF (em ZIP)

## Tecnologias

HTML, CSS, JavaScript, PDF.js, SheetJS (xlsx)

## Como usar

Abra a demo ou o `index.html` e arraste os DANFEs para a área indicada.

Também dá para baixar o repositório e abrir o `index.html` direto no navegador, sem instalar nada.

## Observações

PDFs escaneados (somente imagem) não podem ser lidos, pois não há texto para extrair.

## Autor

Daniel da Silva Rezende · [GitHub](https://github.com/orezzende) · [LinkedIn](https://www.linkedin.com/in/daniel-da-silva-rezende-711ab1195/)
