# Nova Instalação Setup Tailwind CSS v3.3.3

`npm init -y`  <!-- Cria o `package.json`->

`npm install -D tailwindcss` <!-- Instala a Tailwind CSS->

`npx tailwindcss init` <!-- Cria o tailwind.config.js ->

`content: ["./src/**/*.{html,js}"],` <!-- Caminho ate o arquivo "index.html" ->

`input.css` <!-- Criar arquivo "input.css", dentro da Pasta "src" ->

// Colocar esses @arquivos.css //
`@tailwind base;`
`@tailwind components;`
`@tailwind utilities;`


`npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch` <!-- CLI Run Template ->