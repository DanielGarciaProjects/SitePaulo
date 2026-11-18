# Site do Paulo Tessarioli: como publicar

Esta pasta já está pronta para o Netlify. Não precisa de build nem de instalação.

## 1. Subir no GitHub
1. Entre em github.com e clique em **New repository**. Nome sugerido: `site-paulo-tessarioli`.
2. Na página do repositório, clique em **Add file > Upload files**.
3. Arraste **index.html, netlify.toml e robots.txt** (o LEIA-ME é opcional) e clique em **Commit changes**.

## 2. Publicar no Netlify
1. Em app.netlify.com: **Add new site > Import an existing project > GitHub**.
2. Escolha o repositório. Deixe **Build command vazio** e **Publish directory** como `.` (ponto).
3. Clique em **Deploy**. Em 1 minuto o site abre num endereço `*.netlify.app`.

## 3. Colocar o domínio paulotessarioli.com.br
1. No Netlify: **Domain management > Add a domain**.
2. O Netlify mostra os registros de DNS que devem ser criados. Copie exatamente os valores que ele indicar.
3. Quem controla o domínio (Registro.br ou a hospedagem atual) precisa criar esses registros.
4. ATENÇÃO: se existirem e-mails @paulotessarioli.com.br, confirme com quem cuida do domínio antes de trocar o DNS, para não perder o e-mail (registros MX).

## 4. Preencher antes de divulgar (procure no index.html)
- `CRP 06/XXXXX` (rodapé, obrigatório; confirme a regional)
- `(11) 9XXXX-XXXX` e `contato@paulotessarioli.com.br`
- `Endereço completo a confirmar`
- Botões "Chamar no WhatsApp" e "Agendar conversa": hoje apontam para a seção de contato. Troque `href="#contato"` por `https://wa.me/55DDDNUMERO` (só números).
- Texto da seção "Como o processo começa": validar com o Paulo.

## 5. Atualizar o site depois
Edite o `index.html` direto no GitHub (ícone de lápis > Commit). O Netlify republica sozinho.
