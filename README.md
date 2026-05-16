# ConectaBus – Protótipo de Baixa Fidelidade

## 👨‍🎓 Aluno
- Kaio Moreira
- Icaro Ferreira

## 👤 Contexto de Uso

O usuário pode estar utilizando o aplicativo em situações como:

- Correndo para não perder o ônibus ou metrô;
- Carregando mochila, sacolas ou objetos;
- Em locais movimentados;
- Sob pressão de tempo;
- Em ambientes com pouca iluminação;
- Dentro de túneis ou áreas com sinal instável.

Por isso, a interface foi projetada para permitir uso com apenas um polegar, com botões grandes e informações essenciais em destaque.

---

## 🎨 Decisões de UX

### Hierarquia da
O **tempo de chegada** foi destacado como a informação mais importante, pois impacta diretamente a decisão do usuário.

Ordem de prioridade:

1. ⏱ Tempo de chegada
2. 👥 Lotação
3. 🚌 Número da linha
4. ♿ Recursos do veículo

### Redução da Carga Cognitiva
- Textos curtos;
- Ícones intuitivos;
- Poucas opções por tela;
- Layout limpo.

### Navegação
Fluxo principal:

Busca de rota → Resultado → Mapa → Carteira Digital → Detalhes do Veículo

### Prevenção de Erros
O aplicativo reduz erros ao:
- Destacar informações críticas;
- Confirmar visualmente a rota;
- Mostrar QR Code grande e centralizado;
- Utilizar indicadores claros de lotação.

---

## ♿ Acessibilidade

O protótipo foi pensado para atender usuários com diferentes necessidades.

### Recursos de Acessibilidade
- Botões grandes e fáceis de tocar;
- Alto contraste;
- Ícones universais;
- Informações em tempo real;
- Indicação de rampas e ar-condicionado;
- Navegação simples e intuitiva.

### Pessoas com Mobilidade Reduzida
A tela de detalhes informa se o veículo possui:
- ♿ Rampa de acesso
- ❄️ Ar-condicionado
- 📶 Wi-Fi
- 🔌 Tomada

---

## 🌙 Desafios Extras

### Modo Noturno
Reduz o brilho da tela para evitar ofuscamento durante o uso noturno.

### Funcionamento Offline
Ao perder sinal, o aplicativo mantém:
- Última rota carregada;
- QR Code salvo;
- Alertas de conexão.

---
│   └── prototipo.pdf
│── README.md
