# Workflows RecebAI

Importe os arquivos JSON no n8n e configure os nós Google Sheets para a sua planilha.

## Ordem recomendada de teste

1. \`RecebAI - 5. Stats\`
2. \`RecebAI - 7. Listar Moradores\`
3. \`RecebAI - 6. Cadastro Moradores\`
4. \`RecebAI - 2. Listar Encomendas\`
5. \`RecebAI - 3. Registrar Encomenda\`
6. \`RecebAI - 4. Confirmar Retirada\`
7. \`RecebAI - 1. Serve Frontend\`, se quiser servir o HTML pelo n8n

Todos os endpoints foram ajustados para retornar JSON explícito, inclusive quando a planilha estiver vazia.
