[README.md](https://github.com/user-attachments/files/23378130/README.md)
# Ferramentaria Elétrica CA - App Web (Single File)
Esta é a versão empacotada do app **Ferramentaria Elétrica CA** pronta para subir no GitHub.
Arquivos incluídos:
- `index.html` — aplicação web completa (HTML + CSS + JS). Use `index.html` como página do GitHub Pages ou ao publicar no SharePoint/PowerApps.

Instruções rápidas:
- Para testar localmente com câmera (recomendado): execute `python -m http.server` e abra `http://localhost:8000` no browser.
- Para configurar o logo: Acesse Administração → Configurações de Marca → "URL do logo" e escolha **Escolher arquivo** para enviar localmente (o valor é salvo em localStorage).
- O scanner QR foi fortalecido para parar/limpar a câmera antes de reiniciar, evitando bloqueios em múltiplos dispositivos.

OBS: O app salva dados (usuários, ferramentas, empréstimos) em `localStorage` do navegador.
