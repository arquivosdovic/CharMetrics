# Case-Sensitive Character Analyzer

Ferramenta web para análise detalhada de caracteres em textos, com contagem total e distinção entre maiúsculas e minúsculas (case-sensitive). Organiza letras, números e caracteres especiais em grades visuais e permite exportar os resultados para CSV.

## ✨ Funcionalidades

- Contagem de caracteres em tempo real  
- Diferenciação entre **maiúsculas** e **minúsculas**  
- Organização visual por categorias:
  - Alfabeto (A–Z)
  - Números (0–9)
  - Caracteres acentuados e especiais  
- Destaque visual apenas para caracteres presentes no texto  
- Exportação dos dados para **CSV**  
- Interface leve, responsiva e sem dependências externas  

## 🧠 Como funciona

O texto digitado é analisado caractere por caractere.  
Cada símbolo é normalizado para sua forma base (ex.: `a` e `A` → `A`) para agregação, mantendo separadamente as contagens de maiúsculas e minúsculas quando aplicável.

Espaços e quebras de linha são ignorados.

## 📤 Exportação

O botão **Exportar para Tabela (CSV)** gera um arquivo contendo:

Caractere | Total | Maiúsculas | Minúsculas


Os dados são ordenados alfabeticamente para facilitar leitura e uso em planilhas ou análises posteriores.

## 🚀 Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno  
2. Digite ou cole o texto no campo de entrada  
3. Visualize a análise automaticamente  
4. Exporte os dados se desejar  

Não requer instalação nem servidor.

## 🛠️ Tecnologias

- HTML5  
- CSS3  
- JavaScript puro (Vanilla JS)

## 📄 Licença

Projeto livre para uso, estudo e adaptação.
