# Proposta INETRIS — Formação de Líderes

Proposta comercial em página única (HTML/CSS) do **INETRIS** para a sociedade de advogados **Graciane Pimentel & Ana Paula**.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | A proposta completa (página única). |
| `inetris-logo.jpeg` | Logo do INETRIS (navegação e favicon). |
| `capa-formacao-lideres.png` | Banner de capa. |
| `balanca-pessoas-lideres.png` | Ilustração "Pessoas × Líderes". |
| `investimento-formacao-lideres.png` | Arte da seção de investimento. |
| `selo-garantia-inetris.png` | Selo de garantia. |

> Mantenha **todos os arquivos na mesma pasta**. O `index.html` referencia as imagens por caminho relativo.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `proposta-inetris`).
2. Envie **todos os arquivos desta pasta** para a raiz do repositório.
   - Pela web: **Add file → Upload files**, arraste tudo e faça o commit.
   - Ou por linha de comando:
     ```bash
     git init
     git add .
     git commit -m "Proposta INETRIS"
     git branch -M main
     git remote add origin https://github.com/SEU-USUARIO/proposta-inetris.git
     git push -u origin main
     ```
3. No repositório, vá em **Settings → Pages**.
4. Em **Branch**, selecione `main` e a pasta `/ (root)`, e clique em **Save**.
5. Aguarde ~1 minuto. A proposta ficará no ar em:
   `https://SEU-USUARIO.github.io/proposta-inetris/`

## Visualizar localmente

Basta abrir o `index.html` no navegador (duplo clique), ou rodar um servidor simples:

```bash
python3 -m http.server 8000
# depois acesse http://localhost:8000
```
