# Conversor de Moedas
Projeto desenvolvido como parte do Bootcamp Oracle ONE em parceria com a Alura.

## ✅ Descrição

Aplicativo de conversão de moedas feito em Java, rodando via console. O programa permite converter valores entre diversas moedas da América Latina e o Brasil, utilizando dados reais obtidos através da **API Exchange Rate**.

## 🚀 Tecnologias utilizadas

- **Java** (console application)
- **Consumo de API REST** com `java.net.http.HttpClient`
- **Tratamento de exceções**

## 🌎 Funcionalidades

- Conversão entre as seguintes moedas:
  - Dólar
  - Peso argentino
  - Peso colombiano
  - Real Brasileiro
  - Peso Chileno

## 🛠️ Como executar

1. Clone o repositório.
2. Compile o projeto:
   ```bash
   javac -d bin src/br/com/conversordemoeda/**/*.java
   ```
3. Execute o `Main`:
   ```bash
   java -cp bin br.com.conversordemoeda.Main
   ```

## 🔗 API utilizada

[Exchange Rate API](https://www.exchangerate-api.com/)
