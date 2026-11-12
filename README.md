# DevTech Academy — Gerenciamento de alunos

Aplicação simples em HTML e JavaScript para cadastrar, editar e excluir alunos, além de gerar relatórios. Os dados ficam em memória no navegador.

## Executar com Docker

Requer Docker com suporte ao comando Compose.

```bash
docker compose up --build
```

Abra [http://localhost:8080](http://localhost:8080). Para parar o container, use `Ctrl+C` ou execute `docker compose down`.

## Executar sem Docker

Abra `index.html` diretamente no navegador.

## Publicar no GitHub Pages

Envie o conteúdo deste repositório para o GitHub e, nas configurações do repositório, habilite GitHub Pages usando a branch `main` e a pasta raiz (`/`). O arquivo `index.html` será a página inicial.
