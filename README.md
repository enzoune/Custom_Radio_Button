# 🔘 Custom Radio Buttons (Seletores Interativos)

> Componente de UI moderno e minimalista para seleção de opções, desenvolvido com HTML5 e CSS3, focado em substituir os controles nativos por uma interface personalizada e amigável.

## 📖 Sobre o Projeto

Este projeto integra o meu portfólio de estudos em **Programação Full-Stack**. O objetivo foi criar um seletor de opções (neste caso, "Aluno" e "Professor") que abandona o visual padrão dos navegadores em favor de uma estética limpa e profissional.

O projeto foca na interatividade simplificada, onde a seleção é ativada pelo clique em qualquer parte do componente (label), melhorando a área de contato e a usabilidade em dispositivos móveis.

## ✨ Destaques e Aprendizados Técnicos

* **Customização de Inputs:** Substituição visual do input nativo do tipo `radio` por elementos estilizados (`.dot` e `span`), mantendo a funcionalidade original de exclusividade de seleção.
* **Lógica de Seleção Nativa:** Uso eficiente do atributo `for` nas `<label>` conectado aos IDs dos inputs, garantindo que o componente seja acessível e funcional sem necessidade de JavaScript.
* **Agrupamento Semântico:** Utilização do atributo `name="select"` para agrupar as opções logicamente, permitindo que apenas uma alternativa seja escolhida por vez.
* **Design Modular:** Estrutura encapsulada em um container `.wrapper`, facilitando a integração deste componente em formulários de cadastro ou páginas de login.
* **Arquitetura de Código:** Separação clara entre a marcação estrutural (`index.html`) e a identidade visual localizada no diretório de estilos (`css/style.css`).

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e lógica de formulário.
* **CSS3:** Estilização de estados (hover/checked), layout e design responsivo.
