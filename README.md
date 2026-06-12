# Italian Party Site

Site estatico modernizado para a Italian Party.

## Rodar localmente

```bash
npm start
```

Abra `http://localhost:3000`.

## Verificar

```bash
npm run check
```

## Deploy na Vercel

```bash
npm run deploy
```

Para deploy automatico, conecte este repositorio no painel da Vercel. Como o projeto e estatico, nao precisa de build command.

## Rodar com Docker

```bash
docker compose up -d --build
```

Abra `http://SEU-IP:8088`.

Para parar:

```bash
docker compose down
```

## Protecao contra copia casual

O site bloqueia selecao de texto, clique direito, arrastar imagens e atalhos comuns como copiar, salvar, imprimir e ver codigo-fonte. Isso dificulta copia casual, mas nenhum site publico consegue impedir copia real, porque o navegador precisa baixar os arquivos para exibir a pagina.
