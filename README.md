# 🎒 Achados & Perdidos

**Protótipo interativo de um sistema de achados e perdidos**, desenvolvido como demonstração acadêmica para a disciplina de Desenvolvimento de Sistemas.

O projeto foi inspirado nos protótipos de alta fidelidade elaborados pelo grupo, com uma interface em tons de azul e roxo, adaptada para computadores e celulares.

> [!IMPORTANT]
> Este é um **protótipo demonstrativo**, não um sistema oficial da escola. Os objetos iniciais são fictícios. Não insira dados pessoais reais.

## ✨ Funcionalidades

- **Catálogo público:** consulta de objetos disponíveis, pesquisa por nome e filtros por categoria e cor.
- **Cadastro de objetos:** formulário com nome, categoria, cor, descrição, data, local e foto opcional.
- **Consulta de registros:** visualização de objetos cadastrados e de seus status.
- **Registro de saída:** simulação de conferência presencial e atualização do status após aprovação.
- **Relatórios:** contagem de objetos recebidos, disponíveis e devolvidos, além de uma tabela de registros.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (sem frameworks)
- `localStorage` para armazenamento local dos dados

## 📁 Estrutura do projeto

```text
achados-perdidos-site/
├── index.html       # Estrutura da aplicação
├── style.css        # Estilos e responsividade
├── script.js        # Funcionalidades e dados de exemplo
└── README.md        # Documentação
```

## ▶️ Como executar

1. Baixe ou clone o projeto.
2. Mantenha `index.html`, `style.css` e `script.js` na mesma pasta.
3. Abra `index.html` em um navegador atualizado.
4. Navegue pelas opções do menu e experimente cadastrar um objeto.

Não é necessário instalar dependências ou configurar um banco de dados.

## 🚀 Publicação na Vercel

1. Envie os arquivos para um repositório no GitHub, com `index.html` na raiz.
2. Acesse a [Vercel](https://vercel.com/) e importe o repositório como um novo projeto.
3. Para este site estático, não é necessário configurar um comando de build.
4. Faça o deploy e copie o endereço HTTPS publicado.
5. Gere um QR Code para esse endereço e teste-o em outro celular, usando a internet móvel.

## 🧪 Fluxo de demonstração

1. Abra **Cadastrar objeto** e registre um item fictício.
2. Volte ao **Catálogo público** e encontre o item usando a pesquisa.
3. Consulte o registro em **Consultar objetos**.
4. Em **Registrar saída**, selecione o objeto e simule uma conferência aprovada.
5. Abra **Relatórios** para verificar a atualização dos números.

## ⚠️ Limitações

- Os dados são salvos **somente no navegador e dispositivo usados**. Um objeto cadastrado em um celular não aparecerá automaticamente no celular de outra pessoa.
- Não há servidor, banco de dados compartilhado ou autenticação real.
- As áreas de funcionário e gerente são apenas demonstrativas, sem controle de acesso.
- O botão **Reivindicar item** apresenta orientações; não realiza uma solicitação real.
- Os dados de exemplo podem ser restaurados na página de relatórios.

## 🎓 Objetivo

Demonstrar, de maneira navegável, como as telas e funcionalidades planejadas no projeto acadêmico poderiam se relacionar durante o cadastro, a consulta e a devolução de objetos encontrados.
