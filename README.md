# Shadcn Charts Web

![Screenshot do Portfólio](/public/home-page.png)

Este projeto é uma aplicação web que utiliza o Shadcn UI para exibir gráficos interativos. O Shadcn UI é uma coleção de componentes de interface do usuário que podem ser copiados e colados em seus aplicativos, proporcionando uma experiência de desenvolvimento mais rápida e consistente.

## 🚀 Tecnologias Utilizadas

[![Next.js](https://skillicons.dev/icons?i=nextjs)](https://nextjs.org/) [![TypeScript](https://skillicons.dev/icons?i=typescript)](https://www.typescriptlang.org/) [![Tailwind CSS](https://skillicons.dev/icons?i=tailwind)](https://tailwindcss.com/) [![ShadCN UI](https://shadcn.dev)](https://ui.shadcn.com/)

- **Next.js 15:** Framework React para desenvolvimento de aplicações web.
- **TypeScript:** Superset do JavaScript que adiciona tipagem estática ao código.
- **Tailwind CSS:** Framework de CSS utilitário para estilização rápida e eficiente.
- **Shadcn UI:** Coleção de componentes de UI que podem ser integrados facilmente ao projeto.

## 📌 Instalação

Para configurar o ambiente de desenvolvimento, siga os passos abaixo:

1. Clone o repositório:

   ```sh
   git clone https://github.com/Cardosofiles/shadcn-charts-web.git
   ```

2. Navegue até o diretório do projeto:

   ```sh
   cd shadcn-charts-web
   ```

3. Instale as dependências:

   ```sh
   npm install
   ```

   ou

   ```sh
   yarn install
   ```

4. Inicie o servidor de desenvolvimento:

   ```sh
   npm run dev
   ```

   ou

   ```sh
   yarn dev
   ```

O aplicativo estará disponível em `http://localhost:3000`.

## 📂 Estrutura do Projeto

```
shadcn-charts-web/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── utils/
├── .gitignore
├── components.json
├── next.config.ts
├── package.json
├── README.md
└── tsconfig.json
```

- **public/**: Arquivos públicos, como imagens e fontes.
- **src/**: Código-fonte do projeto.
  - **components/**: Componentes reutilizáveis da interface.
  - **pages/**: Páginas da aplicação.
  - **styles/**: Arquivos de estilização.
  - **utils/**: Funções utilitárias.
- **components.json**: Configurações específicas dos componentes Shadcn UI.
- **next.config.ts**: Configurações do Next.js.
- **package.json**: Dependências e scripts do projeto.
- **tsconfig.json**: Configurações do TypeScript.

## 📌 Scripts Disponíveis

No arquivo `package.json`, os seguintes scripts estão disponíveis:

- `dev`: Inicia o servidor de desenvolvimento.
- `build`: Compila a aplicação para produção.
- `start`: Inicia o servidor em modo de produção.
- `lint`: Executa o linter para verificar problemas no código.

## 🎨 Configuração do Shadcn UI

Este projeto utiliza o Shadcn UI para os componentes de interface. Para adicionar novos componentes, utilize o CLI do Shadcn:

```sh
npx shadcn add componente
```

Certifique-se de consultar a [documentação oficial](https://ui.shadcn.com/) para mais detalhes.

## 🖼️ Visualização

![Imagem da Home Page](./public/homepage.png)  
_Adicione aqui a imagem da home page do projeto._

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.

## 📌 Autor

Desenvolvido por **João Batista** 🚀
