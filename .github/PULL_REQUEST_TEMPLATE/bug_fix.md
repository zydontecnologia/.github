## 🐞 Por que acontecia
<!-- explique em linguagem simples -->
O sistema não diferenciava corretamente as unidades de caixa na consolidação, gerando valores fracionados.

## 🔧 Solução Aplicada
<!-- alto nível; sem afundar em classe/método -->
Ajustamos a regra de conversão para tratar caixas e unidades em linhas separadas.

## ✅ Teste de Regressão
- Tipo: Unitário (JUnit)
- Nome: `InvoiceServiceTest.shouldHandleBoxAndUnitSeparately`
- Status: ✅ Passed em CI

## 📎 Evidência e observações
N/A
