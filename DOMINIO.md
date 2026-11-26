# Domínio do site de apresentação do ENDO ATLAS 3D

Data do registro: 29/10/2026

- Endereço oficial do site: https://endoatlas3d.reloadcursos.com (desde 26/11/2026)
- Endereço antigo, mantido ativo para não quebrar links já divulgados: https://dcubic.reloadcursos.com
- Reserva (workers.dev): https://dcubic-image-system-platform.abedrdador.workers.dev
- Aplicativo (VPS): https://app.endoatlas3d.reloadcursos.com (desde 26/11/2026)
- Endereço antigo do aplicativo, mantido ativo: https://app.dcubic.reloadcursos.com

Observações:
- O domínio próprio é configurado em `wrangler.jsonc` (`routes` com `custom_domain`); o registro DNS é criado pelo Cloudflare no deploy.
- Os registros `app.endoatlas3d` e `app.dcubic` (aplicativo na VPS) não devem ser alterados por este projeto. O Traefik da VPS atende os dois nomes (regra Host com ||), e a Configuration Rule "app.dcubic Full strict" da Cloudflare cobre os dois.
- Os botões "Acessar o app" do site apontam para o endereço do aplicativo acima.
