
# API de Consulta de Capitais

## Descrição
API desenvolvida para consultar as capitais dos estados brasileiros e do Distrito Federal.

## Tecnologias
- Node.js
- TypeScript
- Express

## Instalação

```bash
npm install
```

## Execução

```bash
npm run dev
```

## Endpoint

GET /estados/:sigla

## Exemplos

http://localhost:3000/estados/SP

http://localhost:3000/estados/MG

http://localhost:3000/estados/RJ

## Erro 404

{
  "erro": "Estado não encontrado."
}

## Testes
As capturas de tela estão na pasta docs/testes.
"# api-capitais" 
