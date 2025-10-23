# Libris Commerce
![Capa para o projeto](https://github.com/user-attachments/assets/7fb7995b-b354-47d2-83dc-e3b702cd80fc)

**Libris** é um projeto da matéria de LIMA (Linguagem de Marcação) do curso de Desenvolvimento de Sistemas do SENAI Roberto Mange para conclusão do 1° semestre.

O projeto objetiva ser um e-commerce que contempla ao máximo o fluxo de compras de um site real, desenvolvido com foco em semântica, acessibilidade parcial (planejada em nível AA), organização e experiência do usuário. Sendo um **projeto exclusivamente Front-End**, não possui JavaScript ou qualquer outra linguagem que não HTML e CSS.

Libris é um e-commerce de livros, quadrinhos e mangás, cuja proposta é oferecer navegação intuitiva e visual agrádavel, tanto para usuários comuns como para administradores - sendo desenvolvido, além de páginas comuns, um ambiente de administração da plataforma.
<br/><br/>
## Objetivos do projeto
Criar um site de comércio eletrônico que seja:
- Acessível
- Desenvolvido com HTML semântico
- Intuitivo e atrativo
- Divido claramente entre fluxos do usuário e do administrador
- Um projeto puramente Front-End, simulando navegação entre páginas com base em links HTML e estilização CSS.
<br/><br/>
## Fluxos e organização das pastas
Cada fluxo do projeto está separado para facilitar a organização.

O fluxo inicial do usuário comum (deslogado) encontra-se na pasta principal do repositório, sendo o arquivo "index.html" a página inicial (Home Page). 

O fluxo do usuário logado localiza-se na pasta "User_logado", o index desse fluxo também é a Home Page da Libris, porém com algumas modificações e páginas de navegação adicionais para este usuário - por exemplo, "Meus Pedidos", "Meus Favoritos", "Perfil". 

Já o fluxo do adminstrador se encontra na pasta "Adm_Flow" e o seu index é o login, com o objetivo de garantir segurança para o ambiente administrativo.
<br/><br/>
## Protótipo
O projeto foi previamente prototipado no **Figma**, sendo desenvolvidos os fluxos principais dos usuários e administradores.

No Figma, há também uma breve documentação do projeto, incluindo descrição de suas funcionalidades básicas, identidade visual e justificativas, ente outros tópicos.

<a href="https://www.figma.com/design/9XTiNGkfUoVd6IIj9e07qc/Libris-Commerce?node-id=0-1&t=HR6gCo8cRIGvBea7-1" target="_blank">Acesse o protótipo da Libris</a>
<br/><br/>
## Tecnologias utilizadas
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
<br/><br/>
## Observações
- Este é um **projeto puramente Front-End** e não possui integração com banco de dados, back-end ou JavaScript, assim, não é 100% funcional, seu foco é representar apenas uma **simulação** de um e-commerce real.
- Há neste repositório arquivos .py, .key e .crt. Estes, compreendem a parte do projeto da matéria de SOP (Sistemas Operacionais), que consistia em gerar um certificado SSL autoassinado para o e-commerce. Para ver este certificado, ative a porta 8080 na sua máquina, execute o arquivo server.py no Prompt de Comando (que cria um servidor web para usar HTTPS) e acesse o e-commerce pelo navegador usando: `https://localhost:8080`.
