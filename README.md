# Upload de Arquivo com Node.js e Express

## Descrição
Este projeto permite o upload de arquivos utilizando um frontend simples em HTML e Tailwind CSS, e um backend em Node.js com Express e Multer.

## Tecnologias Utilizadas
### Frontend:
- HTML
- Tailwind CSS
- JavaScript (Fetch API)

### Backend:
- Node.js
- Express
- Multer (para manipulação de arquivos)
- Cors (para permitir requisições entre origens diferentes)
- FS (File System) para manipulação de arquivos no servidor

## Como Funciona
1. O usuário seleciona um arquivo no frontend.
2. Ao clicar no botão "Enviar", o arquivo é enviado para o servidor via requisição `POST`.
3. O servidor armazena o arquivo na pasta `C:/uploads`.
4. O backend responde informando que o arquivo foi salvo com sucesso.

## Como Executar
### 1. Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Instalar Dependências
```bash
npm install express multer cors fs path
```

### 3. Executar o Backend
```bash
node server.js
```

### 4. Abrir o Frontend
Basta abrir o arquivo `index.html` em um navegador.

## Estrutura do Projeto
```
/
├── index.html    # Interface do usuário
├── server.js     # Servidor Node.js com Express e Multer
├── package.json  # Configuração do projeto
└── README.md     # Documentação do projeto
```

## Exemplo de Uso
1. Acesse `index.html` no navegador.
2. Escolha um arquivo.
3. Clique em "Enviar".
4. O status informando o resultado do upload será exibido na tela.

## Observações
- Certifique-se de que a pasta `C:/uploads` existe ou será criada automaticamente pelo servidor.
- O servidor roda na porta `3000` por padrão.
- O backend deve estar rodando para que o upload funcione corretamente.

## Contribuição
Sinta-se à vontade para contribuir com melhorias ou abrir issues para relatar problemas.

