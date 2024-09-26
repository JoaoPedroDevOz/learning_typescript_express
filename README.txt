COMMANDOS PARA INICIALIZAÇÃO DO PROJETO:

npm init -y

npm install -D typescript
npm add -D tsc typescript ts-node
npx tsc --init

npm install nodemon
"dev": "nodemon --watch '/src' --exec 'ts-node src/index.ts' -e ts"

npm add -D eslint prettier eslint-config-prettier
npx eslint --init