# Editor PDF Restante

Editor web local para remover paginas de um PDF e salvar um novo documento com as paginas restantes.

## Abrir localmente

Use um servidor local na pasta deste projeto:

```powershell
python -m http.server 8876 --bind 127.0.0.1
```

Depois abra:

```text
http://127.0.0.1:8876/editor-pdf-local.html
```

## Publicado

https://editor-pdf-restante.netlify.app

## Funcoes

- Selecionar paginas para remover.
- Selecionar intervalos com Ctrl + clique.
- Salvar o PDF restante.
- Aplicar OCR no PDF restante.
- Comprimir o PDF restante em niveis Leve, Media ou Forte.
- Abrir PDF por clique ou arrastar/soltar.
