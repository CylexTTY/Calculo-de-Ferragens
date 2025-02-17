# Cálculo de Ferragens para Construção Civil

![Preview](https://cylextty.github.io/Calculo-de-Ferragens/)

Ferramenta web para cálculo otimizado de ferragens (armação) em elementos estruturais como colunas e sapatas, com foco em minimizar desperdícios de materiais.

## ✨ Funcionalidades

- **Cálculo de Colunas**
  - Multiplas colunas com alturas e quantidades variáveis
  - Configuração de ferros principais (4 ou 6 unidades) + reforços
  - Cálculo automático de estribos com diferentes espaçamentos
  - Detalhamento de cortes com otimização de barras de 12m

- **Cálculo de Sapatas**
  - Dimensões personalizáveis (comprimento, largura, altura)
  - Configuração de quantidade de ferros por eixo
  - Cálculo de ganchos/sobras nas extremidades
  - Visualização detalhada da distribuição de cortes

- **Recursos Gerais**
  - Sistema de salvamento de preferências (localStorage)
  - Interface responsiva para uso em dispositivos móveis
  - Detecção automática de desperdício aceitável
  - Modo escuro integrado (via preferência do sistema)

## 🛠 Tecnologias Utilizadas

- **Frontend**
  - HTML5 + CSS3 (com variáveis customizadas)
  - JavaScript Vanilla (ES6+)
  - Bootstrap 5.3 (Componentes e Grid System)
  - Bootstrap Icons (Ícones interativos)

- **Recursos Especiais**
  - Algoritmo de empacotamento (bin packing) para otimização de cortes
  - Sistema de notificações animado
  - Controles incrementais com validação em tempo real
  - Interface touch-friendly para campo

## 🚀 Como Usar

1. **Colunas**
   - Adicione colunas com diferentes alturas usando o botão "+"
   - Configure quantidade de ferros e reforços
   - Ajuste medidas de estribos e espaçamento
   - Clique em "Calcular" para ver resultados detalhados

2. **Sapatas**
   - Insira as dimensões da sapata em centímetros
   - Defina quantidade de ferros por eixo
   - Especifique sobras para ganchos
   - Visualize sugestões de corte com desperdício calculado

**Dica:** Use *long press* (toque prolongado) nos botões "+" de "Sobra Estribo" e "Sobra Aceitável" para salvar configurações preferidas!

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/calculo-ferragens.git

# Acesse o diretório
cd calculo-ferragens

# Basta abrir o index.html em qualquer navegador moderno

# Site direto
https://cylextty.github.io/Calculo-de-Ferragens/
