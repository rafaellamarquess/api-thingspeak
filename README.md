## API ThingSpeak

Este projeto realiza a consulta de dados de um canal público no ThingSpeak e exibe informações básicas da estação e sensores.

### Instalação

1. Clone o repositório:

```bash
git clone <URL_DO_REPO>
cd api-thingspeak
```

2. Instale as dependências:

```bash
npm install
```

### Uso

1. Execute o script:

```bash
node index.js
```

2. O script fará uma requisição ao canal do ThingSpeak e exibirá no console:

* Nome da estação
* Localização (latitude e longitude)
* Sensores (field1 a field8)

### Dependências

* [node-fetch](https://www.npmjs.com/package/node-fetch) ^3.3.2

## Observações

* API usada: `https://thingspeak.mathworks.com/channels/1293177/feed.json`
* Certifique-se de que seu Node.js seja versão 16 ou superior.
