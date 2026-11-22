# Alugaê

O Alugaê é um site demonstrativo para uma proposta de aluguel de roupas de gala. A ideia é apresentar vestidos, ternos, smokings e calçados para eventos especiais, além de reunir informações sobre o projeto e oferecer formulários de contato e cadastro de clientes.

> **Projeto acadêmico:** as peças, os tamanhos, os preços e os dados de contato exibidos são exemplos. O site é uma interface front-end estática; não possui servidor ou banco de dados.

## Páginas

- **Início** (`home/index.html`): apresentação do Alugaê, banner e peças em destaque.
- **Roupas** (`roupas/roupas.html`): catálogo de peças com filtros por categoria.
- **Sobre o projeto** (`sobre/sobre.html`): objetivo do projeto e explicação da proposta.
- **Cadastrar cliente** (`cadastrar/cadastrar.html`): formulário com dados pessoais e endereço, validação nativa do navegador e opção para limpar os campos.
- **Contato** (`contato/contato.html`): formulário de mensagem e informações de contato de exemplo.

As páginas compartilham a navegação principal, o cabeçalho e o rodapé. Os links permitem acessar as demais páginas a partir de qualquer aba.

## Tecnologias

- HTML5
- CSS3, incluindo layouts responsivos com Grid e Flexbox
- JavaScript simples na página de contato para validar o formulário e mostrar uma confirmação simulada
- Google Fonts para as fontes utilizadas no projeto, com fontes alternativas definidas no CSS

O catálogo utiliza controles HTML e CSS para filtrar as peças, sem necessidade de JavaScript.

## Como executar

Não é necessário instalar dependências nem compilar o projeto.

1. Baixe ou clone o repositório.
2. Abra a pasta do projeto no VS Code.
3. Abra `home/index.html` no navegador. Também é possível usar uma extensão como **Live Server** para servir a pasta localmente.
4. Navegue pelas outras páginas usando o menu do site.

Como o projeto usa caminhos relativos, mantenha as pastas e os arquivos na estrutura indicada abaixo.

## Estrutura de pastas

```text
ProjetoIntegrador/
├── cadastrar/
│   ├── cadastrar.css
│   └── cadastrar.html
├── contato/
│   ├── contato.css
│   └── contato.html
├── home/
│   ├── index.html
│   └── style.css
├── img/
│   ├── alugaeLogo.jpg
│   └── banner.svg
├── roupas/
│   ├── roupas.css
│   └── roupas.html
├── sobre/
│   ├── sobre.css
│   └── sobre.html
└── README.md
```

`home/style.css` contém estilos compartilhados, como cores, tipografia, botões, navegação e rodapé. Cada página possui um arquivo CSS próprio para seus estilos específicos.

## Formulários e limitações

- O formulário de cadastro usa `method="post"` e validações HTML, mas ainda não está conectado a um backend. Portanto, os dados não são salvos nem enviados para uma base de dados.
- O formulário de contato apresenta uma confirmação simulada no navegador. A mensagem também não é enviada nem armazenada.
- Para receber e persistir cadastros ou mensagens, será necessário implementar um serviço backend e conectar os formulários a ele.

## Informações acadêmicas

Projeto Integrador da disciplina de Engenharia de Software II, do curso de Análise e Desenvolvimento de Sistemas da Fatec São Caetano do Sul – Antonio Russo.

### Equipe

- Matheus Giovanelli
- Lucas Toledo Porfírio
- Daniel Voros Monteiro
- Gabriel Alves Metestaine
- Bruno Dantas Matias