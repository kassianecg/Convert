# Convert

Conversor de moedas estrangeiras para Real Brasileiro (BRL), desenvolvido com HTML, CSS e JavaScript puro.

## Funcionalidades

- Conversão de valores para Real Brasileiro (BRL)
- Moedas suportadas:
  - Dólar Americano (USD)
  - Euro (EUR)
  - Libra Esterlina (GBP)
- Aceita somente valores numéricos no campo de entrada
- Exibe a cotação utilizada e o resultado formatado em BRL

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## Como usar

1. Abra o arquivo `index.html` no navegador (ou use uma extensão como Live Server)
2. Digite o valor que deseja converter
3. Selecione a moeda de origem
4. Clique em **Converter em reais**

## Estrutura do projeto

```
Convert/
├── index.html
├── script.js
├── styles.css
└── img/
    ├── logo.svg
    ├── bg.png
    ├── check.svg
    └── chevron-down.svg
```

## Cotações utilizadas

As cotações são fixas e definidas diretamente no código (`script.js`):

| Moeda | Valor em BRL |
|-------|-------------|
| USD   | R$ 4,87     |
| EUR   | R$ 5,32     |
| GBP   | R$ 6,08     |
