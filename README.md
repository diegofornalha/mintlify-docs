# Kit Inicial Mintlify

Clique em `Use this template` para copiar o kit inicial do Mintlify. O kit inicial contém exemplos incluindo

- Páginas de guia
- Navegação
- Personalizações
- Páginas de referência de API
- Uso de componentes populares

### Desenvolvimento

Instale o [Mintlify CLI](https://www.npmjs.com/package/mintlify) para visualizar as alterações na documentação localmente. Para instalar, use o seguinte comando

```
npm i -g mintlify
```

Execute o seguinte comando na raiz da sua documentação (onde está o mint.json)

```
mintlify dev
```

### Publicando Alterações

Instale nosso aplicativo do Github para propagar automaticamente as alterações do seu repositório para sua implantação. As alterações serão implantadas em produção automaticamente após o push para o branch padrão. Encontre o link para instalação no seu painel.

#### Solução de Problemas

- Mintlify dev não está rodando - Execute `mintlify install` para reinstalar as dependências.
- Página carrega como 404 - Certifique-se de que você está executando em uma pasta com `mint.json`
