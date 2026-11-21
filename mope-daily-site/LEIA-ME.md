# Mope Daily: publicar e ligar ao Supabase

## 1. Supabase (grátis)
1. Cria um projeto em supabase.com.
2. SQL Editor > cola o conteúdo de `schema.sql` > Run.
3. Project Settings > API: copia a **Project URL** e a **anon public key** para o `config.js`.
   (Nunca uses a service_role key no frontend.)
4. Authentication > URL Configuration: em *Site URL* e *Redirect URLs* põe o endereço onde vais publicar a app.

## 2. Publicar (grátis)
Netlify Drop (app.netlify.com/drop), Cloudflare Pages ou GitHub Pages: envia todos os ficheiros desta pasta.

## 3. iPhone
Abre o link no Safari > Partilhar > Adicionar ao ecrã principal.

## Notas
- Sem `config.js` preenchido, a app funciona só neste aparelho.
- A sincronização guarda a app inteira por utilizador (a última alteração ganha). Evita editar em dois aparelhos ao mesmo tempo sem ligação.
