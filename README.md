# 🦅 Harpia - Mobilidade Urbana Inteligente

[![License](https://img.shields.io/badge/license-MIT-2F2F2F?style=flat-square)](https://opensource.org/licenses/MIT)
[![Frontend](https://img.shields.io/badge/frontend-HTML%20CSS%20JS-4F46E5?style=flat-square)](https://developer.mozilla.org/)
[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-10B981?style=flat-square)]()

> **Harpia** é uma aplicação web mobile-first que revoluciona a experiência do transporte público, integrando planos de assinatura, rastreamento de ônibus em tempo real, itinerários digitais, cartão por aproximação (NFC) e chat colaborativo por linha.

---

## ✨ Funcionalidades

### 🎫 **Planos de Assinatura (Pontos)**
- 3 planos disponíveis: Básico (R$19,90/mês), Plus (R$39,90/mês) e Premium (R$79,90/mês)
- Cada plano concede pontos mensais para pagamento de passagens
- Pagamento simulado via **Cartão de Crédito** ou **PIX**
- Destaque visual para o plano "Mais Popular"

### 🗺️ **Rastreamento de Ônibus em Tempo Real**
- Mapa interativo com Leaflet.js (OpenStreetMap)
- Simulação de ônibus em movimento (linhas 100, 200, 300)
- Ícones personalizados e atualização dinâmica a cada 4 segundos
- Visualização da posição exata dos veículos

### 📅 **Itinerário e Horários**
- Consulta completa de linhas de ônibus
- Horários diferenciados para dias úteis, sábado, domingo e feriados
- Lista de paradas com horários aproximados
- Badge de "próximo horário" em destaque

### 💳 **Cartão Digital por Aproximação (NFC)**
- Cartão virtual estilizado com número, validade e nome
- Exibição do saldo de pontos em tempo real
- Simulação de pagamento por aproximação (dedução de pontos)
- Toggle para ativar/desativar NFC
- Histórico das últimas transações

### 💬 **Chat Limitado por Linha**
- Chat exclusivo para cada linha de ônibus
- Mensagens **pré-definidas** para evitar spam:
  - 🚌 Ônibus quebrou
  - 🚗 Trânsito intenso
  - 🚂 Trem passando
  - ⏰ Atrasado
  - 📢 Lotação máxima
    
---

## 🎨 Cores da Marca

| Cor | Nome | Código | Uso |
|-----|------|--------|-----|
| 🟠 | **Laranja** | `#F2541B` | Botões primários, destaques, ícones ativos |
| ⚪ | **Branco** | `#FFFFFF` | Fundos, cards, superfícies |
| 🟤 | **Vinho** | `#3D0010` | Header, navegação inferior, elementos principais |

### Gradientes
- `--grad-marca`: linear-gradient(135deg, #3D0010 0%, #8B0024 45%, #F2541B 100%)
- `--grad-header`: linear-gradient(160deg, #3D0010 0%, #6B0020 60%, #F2541B 140%)

---

## 🛠️ Tecnologias Utilizadas

<div align="center">
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white)
![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)

</div>

- **HTML5** - Estrutura semântica
- **CSS3** - Flexbox, Grid, animações, variáveis CSS
- **JavaScript (Vanilla)** - DOM manipulation, SPA routing, simulação de dados
- **Leaflet.js** - Mapas interativos e marcadores dinâmicos
- **Font Awesome 6** - Ícones vetoriais
- **Google Fonts (Poppins)** - Tipografia moderna

---

## 📂 Estrutura do Projeto

```bash
HARPIA/
│
├── cadastro.html        # Cadastro de usuário
├── cartao.html          # Cartão digital
├── carteira.html        # Carteira/saldo de pontos
├── chat-linha.html      # Chat específico da linha
├── chat.html            # Lista de chats por linha
├── compra.html          # Compra de pontos/planos
├── detalhes.html        # Detalhes da linha/ônibus
├── home.html            # Página inicial
├── index.html           # Entry point / Splash screen
├── itinerario.html      # Itinerário e horários
├── listagem.html        # Listagem de linhas
├── login.html           # Login do usuário
├── mapa.html            # Rastreamento em tempo real
├── otp.html             # Verificação em dois fatores
├── pagamento.html       # Pagamento de planos
├── perfil.html          # Perfil do usuário
│
├── script.js            # JavaScript global
├── style.css            # Estilos globais
│
├── assets/              # Recursos estáticos (imagens, ícones, logos)
│
└── README.md            # Documentação do projeto
```
---

## 🚀 Como Executar

### Pré-requisitos
- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Conexão com internet (para carregar mapas e fontes)

### Método 1: Direto pelo navegador
```bash
# Baixe o arquivo index.html e abra com duplo clique
```
---

## 🎯 Público-alvo

- 👥 Usuários de transporte público que buscam praticidade no dia a dia  
- 💼 Trabalhadores que utilizam ônibus diariamente  
- 🎓 Estudantes que precisam de recarga fácil de créditos e agilidade no deslocamento  
- 👨‍👩‍👧‍👦 Comunidade que deseja colaborar com informações em tempo real sobre o transporte  

---

## 🔮 Roadmap e melhorias futuras

### 🚧 Versão 1.0 (Concluído)
- FrontEnd básico em HTML, CSS e JavaScript
- Criação da identidade visual do aplicativo (cores, layout e estilo)
- Desenvolvimento do design inicial das telas (UI/UX)
- Estruturação completa das páginas do sistema
- Criação da navegação entre telas (fluxo do aplicativo)
- Protótipo funcional das principais funcionalidades
- Separação modular das páginas (cada funcionalidade em uma tela)
- Criação da página inicial (Home) como central do app
- Protótipo responsivo (base para adaptação mobile)
- Definição da estrutura geral do sistema (arquitetura front-end)

---

### 🚀 Versão 2.0 (Pendente)
- Implementação do frontend em React
- Desenvolvimento do backend básico (API REST)
- Integração entre frontend e backend
- Gerenciamento real de usuários (perfil editável)
- Sistema de autenticação completo (login, cadastro e logout)
- Proteção de rotas (React Router)
  
---

### 🌐 Versão 3.0 (Pendente)
- Aplicativo híbrido (React Native / Ionic)
- Integração com dados reais de ônibus (ou API simulada tipo GTFS)
- Rastreamento de ônibus em tempo real (mapa funcional)
- Chat por linha com persistência de mensagens (banco de dados)
- Geração de QR Code para recarga/pagamento de pontos
- Notificações em tempo real (atrasos, ocorrências, alertas)
- Banco de dados integrado (usuários, linhas, transações, mensagens)

---

## 📄 Licença

Este projeto está sob a licença MIT.

Isso significa que você pode usar, copiar, modificar e distribuir o projeto livremente, desde que mantenha os devidos créditos.

Para mais informações, consulte o arquivo `LICENSE`.

---

```text
MIT License

Copyright (c) 2026 Ana Júlia Rubim

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
## 👥 Desenvolvedora

| Nome | Função | Contato |
|------|--------|--------|
| Ana Júlia Rubim | Desenvolvimento | anajrbcosta25@gmail.com |

---

## 📧 Contato e Suporte

- 📩 Email: anajrbcosta25@gmail.com 
- 💻 GitHub: https://github.com/anajrubim
- 📸 Instagram: [@anajrubim](https://www.instagram.com/anajrubim/)
- 🌐 Linkedin: https://www.linkedin.com/in/ana-j%C3%BAlia-rubim-41904234b

---

## 🦅 Slogan

> "Harpia: Você no controle da viagem."

---

<div align="center">

💙 Feito com dedicação para transformar a mobilidade urbana

⬆ [Voltar ao topo](#harpia)

</div>
