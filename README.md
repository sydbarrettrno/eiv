# Sistema de Verificação EIV/RIV/TRIMMC — Itapoá/SC — V03 Institucional

Versão autocontida do sistema, pronta para abrir diretamente pelo arquivo `index.html`.

## O que foi corrigido nesta versão

- O `index.html` passou a ser funcional sozinho, sem depender de pastas `js/` e `css/` inexistentes no pacote enviado.
- A interface foi ajustada para uma apresentação mais institucional, com fundo claro e paleta compatível com o manual de aplicação do logotipo da Prefeitura de Itapoá.
- O emblema genérico que imitava um símbolo municipal foi removido. O sistema agora espera o logotipo oficial em `assets/logo-prefeitura-itapoa.png`.
- Caso o logotipo oficial não esteja presente, o cabeçalho usa apenas um fallback textual discreto: `PREFEITURA DE ITAPOÁ`.
- Foram preservados os cálculos, validações, localStorage e geração DOCX em JavaScript nativo.

## Como usar

1. Extraia o ZIP.
2. Abra `index.html` com duplo clique no navegador.
3. Para usar o logotipo oficial, coloque o arquivo em:

```text
assets/logo-prefeitura-itapoa.png
```

4. Preencha o formulário e clique em `Gerar relatório DOCX`.

## Observações técnicas

- Sistema 100% estático.
- Sem Python.
- Sem servidor local.
- Sem npm.
- Sem bibliotecas externas.
- Sem CDN.
- Sem leitura da planilha em tempo de execução.
- O relatório DOCX é gerado no próprio navegador.

## Atenção

Esta ferramenta é auxiliar e não substitui validação técnica da SEPLAN/CMEIV.
