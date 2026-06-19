# Stage Films — Sistema de Orçamento

Calculadora de orçamento de produção audiovisual com cálculo automático de margem, saúde do projeto e ajuste de escopo. Tudo roda no navegador, sem servidor, e salva os dados localmente.

## Como subir no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `orcamento-stage`).
2. Faça upload do arquivo `index.html` para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha a branch `main` e a pasta `/ (root)`. Salve.
5. Em ~1 minuto o site fica no ar em: `https://SEU-USUARIO.github.io/orcamento-stage/`

## Como usar

Tudo começa na aba **Início**, que tem o passo a passo. Em resumo:

- Você só preenche a aba **Dados** — todas as outras calculam sozinhas.
- A aba **Saúde do Projeto** mostra 🟢/🟡/🔴 em tempo real.
- A **Folha de Rosto** tem botão de imprimir/PDF para enviar ao cliente.

## Salvamento

Os dados ficam salvos automaticamente no navegador (localStorage). Fechar e reabrir não perde nada. Atenção: trocar de navegador ou limpar o cache apaga os dados. Para um orçamento importante, imprima o PDF da Folha de Rosto como registro.

## Fórmula

```
Total ao cliente = Custo de Produção × (1 + Taxa% + Impostos%)
```
