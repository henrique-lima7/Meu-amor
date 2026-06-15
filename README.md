# 🌻 José Henrique & Nicoly — 5 Anos (Special Anniversary Project)

<p align="center">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-success?style=for-the-badge&logo=github" alt="Status Concluído">
  <img src="https://img.shields.io/badge/Plataforma-Web-blue?style=for-the-badge" alt="Plataforma Web">
</p>

---

## 🔗 Visite o Projeto Ativo
> 🚀 **[Clique aqui para acessar o site diretamente e testar os recursos interativos!](SEU_LINK_DO_GITHUB_PAGES_OU_VERCEL_AQUI)**

---

## 📝 Sobre o Projeto

Este é um projeto de desenvolvimento web front-end altamente interativo e personalizado, construído originalmente como uma celebração de **5 anos de namoro**. O objetivo principal foi materializar memórias e momentos marcantes através do código, criando uma experiência rica em UI/UX.

Para os **recrutadores**, este projeto demonstra minhas habilidades práticas em estruturação de código limpo em arquivos únicos, consumo de microsserviços/APIs externas de mapas, persistência de dados NoSQL em tempo real, integração de assistentes de IA personalizados e foco absoluto em **acessibilidade (A11y)** e **otimização de renderização**.

### ✨ Principais Funcionalidades (User Experience)
* **Gatekeeping Inteligente (Overlay):** Tela de boas-vindas com fluxos de rotas lógicas diferentes para a destinatária principal (desafio por palavra-passe), recrutadores e curiosos.
* **Contador Dinâmico em Tempo Real:** Algoritmo que calcula com precisão matemática segundos, minutos, horas, dias, meses e anos desde o marco inicial.
* **Mural Interativo de Recados e Filmes:** Sistema integrado onde usuários podem fixar notas que são atualizadas instantaneamente na tela.
* **Gamificação Integrada:** Jogo "Adivinhe a Foto" com sistema de vidas e níveis progressivos de desfoque (*CSS blur filters*), além de um quiz customizado sobre a história do casal.
* **Mapa de Calor de Localizações:** Mapeamento geográfico interativo de pontos turísticos e viagens realizadas.
* **Suporte de IA (Chatbot Integrado):** Um assistente virtual em tempo real preparado para interagir com os visitantes da página.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

O projeto foi modularizado utilizando tecnologias nativas para extrair a melhor performance do ecossistema Web:

* **HTML5 & CSS3 Avançado:** Utilização rigorosa de *CSS Variables* para arquitetura de **Dark Mode**, animações complexas via `@keyframes` (efeito Ken Burns no Hero, animações de cascata na galeria) e design 100% responsivo (Mobile-First).
* **JavaScript Vanilla (ES6+):** Manipulação assíncrona do DOM, gerenciamento de estados locais (`localStorage`) e observadores de performance.
* **Firebase Firestore (NoSQL):** Integração do SDK do Firebase (`v10.8.0`) utilizando módulos para escuta em tempo real (`onSnapshot`) e adição assíncrona de dados para o mural.
* **Leaflet.js API:** Integração de mapas interativos baseados em coordenadas geográficas reais com estilização customizada de pins em SVG/Emojis.
* **Chatbase API Integration:** Injeção de script assíncrono e manipulação de objetos globais da janela (`window.chatbase`) para integração de um chatbot com inteligência artificial contextualizada no projeto.
* **Intersection Observer API:** Implementação nativa de *lazy loading* de imagens e gatilhos de animação (*fade-in*) baseados na rolagem do usuário, economizando memória e processamento.
* **Acessibilidade (VLibras):** Integração do widget do VLibras, tornando a aplicação acessível para pessoas surdas ou com deficiência auditiva.

---

## 📐 Diferenciais Técnicos Aplicados

* **Desempenho de Renderização:** Otimização de imagens através de atributos nativos de `loading="lazy"`.
* **Integração de Serviços de Terceiros:** Script externo assíncrono isolado para o chatbot e VLibras, garantindo que o carregamento desses componentes não trave a renderização principal da página (*non-blocking JS*).
* **UI/UX Fluida:** Uso de transições suaves e efeitos de física simulada (como o cálculo de colisão lógica de texto na Nuvem de Palavras, impedindo sobreposição de elementos).
* **Clean Code:** Lógica centralizada, assíncrona e modularizada de fácil manutenção.

---

## 🚀 Como Executar o Projeto Localmente

Como o projeto foi concebido em uma arquitetura limpa de arquivo estático, executá-lo é extremamente simples:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
