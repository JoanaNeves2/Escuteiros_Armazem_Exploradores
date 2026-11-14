# Armazém II – Inventário (site no GitHub Pages)

## Pôr online (uma vez)
1. Em github.com → **New repository** → nome p.ex. `armazem` → **Public** → Create.
2. **Add file → Upload files** e carrega `index.html` e `data.json` → Commit.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch `main` / `/ (root)` → Save.
4. Ao fim de ~1 min o site fica em `https://O_TEU_UTILIZADOR.github.io/armazem/`.

## Editar (de qualquer sítio, telemóvel incluído)
Cria um token: GitHub → Settings → Developer settings → **Personal access tokens → Fine-grained tokens**
→ Repository access: só o repo `armazem` → Permissions: **Contents: Read and write**.

No site carrega em **✏️ Editar**, cola o token (fica guardado só nesse browser), altera, **💾 Guardar**.
O site faz um commit ao `data.json`. Histórico completo no GitHub, dá para reverter.

## Alternativa sem token
Abre `data.json` no GitHub → ícone do lápis → edita → Commit.

## Notas
- Repo público = qualquer pessoa com o link vê o inventário. Para privado precisas de GitHub Pro/Team.
- Nunca partilhes o token. Se o perderes, apaga-o em Settings e cria outro.
- Se o branch não for `main`, muda `CFG.branch` no topo do `index.html`.
