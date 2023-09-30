# Nova Instalação v3.3.3

`npm init -y`  <!-- Cria o `package.json` -->

`npm install -D tailwindcss` <!--  Instala a Tailwind CSS->

`npx tailwindcss init` <!-- Cria o tailwind.config.js -->

`content: ["./src/**/*.{html,js}"],` <!-- Caminho ate o arquivo "index.html" -->

<!-- Criar arquivo "input.css", dentro da Pasta "src" -->
`input.css`

<!-- Colocar esses @arquivos.css -->
`@tailwind base;`
`@tailwind components;`
`@tailwind utilities;`

<!-- CLI Run Template -->
`npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch`