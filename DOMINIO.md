# Domínio do site de apresentação do DCubic

Data do registro: 29/10/2026

- Endereço oficial do site: https://dcubic.reloadcursos.com
- Reserva (workers.dev): https://dcubic-image-system-platform.abedrdador.workers.dev
- Aplicativo (VPS): https://app.dcubic.reloadcursos.com

Observações:
- O domínio próprio é configurado em `wrangler.jsonc` (`routes` com `custom_domain`); o registro DNS é criado pelo Cloudflare no deploy.
- O registro `app.dcubic` (aplicativo na VPS) não deve ser alterado por este projeto.
- Os botões "Acessar o app" do site apontam para o endereço do aplicativo acima.
