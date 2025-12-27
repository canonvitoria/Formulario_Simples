# Cadastro de DEVs

Este projeto consiste em uma página web de **Cadastro de Desenvolvedores**, composta por uma estrutura semântica em HTML e estilização via CSS. O objetivo é coletar informações de perfil profissional e stack tecnológica de novos desenvolvedores.

---

## Estrutura de Arquivos

* **Formulário.html**: Contém toda a estrutura de tags, campos de entrada e a hierarquia do formulário.
* **formulário.css**: Define a identidade visual, cores, fontes e o layout da página.

---

## Funcionalidades do Formulário

O formulário está dividido em seções para capturar diferentes tipos de dados:

* **Identificação Pessoal**: Campos de texto para Nome, Sobrenome e E-mail, todos definidos como obrigatórios através do atributo `required`.
* **Lado de Desenvolvimento**: Seleção via botões do tipo `radio` para escolher entre Front-end, Back-end ou Fullstack.
* **Senioridade**: Menu de seleção (`select`) com as opções Junior, Pleno e Senior.
* **Tecnologias**: Lista de checkboxes para marcar competências em HTML, CSS, JavaScript, PHP, C#, Python e Java.
* **Experiência**: Campo de texto expandido (`textarea`) para relatos sobre a trajetória do desenvolvedor.

---

## Design e Estilização

A folha de estilo aplica uma estética moderna com as seguintes características:

* **Paleta de Cores**: Uso predominante de tons arroxeados (`#380B61` e `#59429d`) sobre um fundo azul claro (`#F0F8FF`).
* **Tipografia**: Utilização de fontes do sistema `sans-serif` para melhor legibilidade.
* **Interatividade**: 
    * Mudança de cor de fundo nos campos (`input`, `select`, `textarea`) quando recebem foco (`:focus`).
    * Efeito visual no botão "Concluído" ao passar o mouse (`:hover`), alterando a cor de fundo e removendo a sombra do texto.
* **Layout**: O conteúdo é centralizado na tela através de margens e o botão de envio utiliza posicionamento absoluto para destaque no rodapé.
