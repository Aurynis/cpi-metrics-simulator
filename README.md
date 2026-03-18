# CPI Metrics Simulator

Simulador interativo de consumo de messages da capability **Cloud Integration** do SAP Integration Suite.

**[Acessar o simulador](https://aurynis.github.io/cpi-metrics-simulator/)**

## Sobre

Este simulador permite modelar e comparar o consumo de licença (messages) sob diferentes patterns de integração:

- **Doc-a-doc** — um documento por execução
- **Batch + Split** — lote recebido e dividido em documentos individuais
- **Pure Batch** — processamento em lote sem split

O modelo projeta o impacto das regras de metering atuais e futuras (baseadas em tamanho), ajudando organizações a planejar otimizações antes da entrada em vigor do novo modelo de cobrança.

## Referência

Baseado no [SAP Note 2942344](https://me.sap.com/notes/2942344) — *Integration Suite: Message Metric Definition* (v23, 17.06.2025).

O PDF de referência está disponível em [`reference/`](reference/).

## Tecnologia

Aplicação 100% client-side — HTML, CSS e JavaScript vanilla em um único arquivo. Sem dependências externas, sem build step. Basta abrir `index.html` no browser.

## Licença

[Apache License 2.0](LICENSE)
