# OLX Dashboard — Telegram Mini App

## Como publicar e ativar (passo a passo)

### 1. Hospedar no GitHub Pages (gratuito)

1. Acesse https://github.com e faça login (ou crie conta)
2. Clique em **New repository**
3. Nome: `olx-dashboard` · marque **Public** · clique **Create**
4. Clique em **uploading an existing file**
5. Arraste o arquivo `index.html` para a área de upload
6. Clique **Commit changes**
7. Vá em **Settings → Pages**
8. Em "Source" selecione **Deploy from a branch → main → / (root)**
9. Clique **Save**
10. Aguarde ~1 minuto → o link ficará disponível como:
    `https://SEU_USUARIO.github.io/olx-dashboard/`

### 2. Configurar o bot no BotFather

No Telegram, abra @BotFather e envie:

```
/setmenubutton
```
Selecione seu bot (@seu_bot), depois:
- **Text**: `📊 Dashboard`
- **URL**: `https://SEU_USUARIO.github.io/olx-dashboard/`

Pronto! O botão aparece no canto inferior esquerdo do chat com o bot.

### 3. Abrir no iPhone

- Abra o Telegram no iPhone
- Abra o chat com seu bot
- Toque no botão **📊 Dashboard** no canto inferior esquerdo
- O dashboard abre como Mini App dentro do Telegram

### Funcionalidades no iPhone

✅ Cards de anúncios com fotos  
✅ Galeria com setas (deslize ou use ❮ ❯)  
✅ Filtro por categoria (PS4, PS5, Xbox, Switch, iPhone...)  
✅ Ordenação por recente / menor / maior preço  
✅ Busca por título  
✅ Bottom sheet com detalhes completos  
✅ Botão "Abrir na OLX" e "Comprar com segurança"  
✅ Botão voltar nativo do Telegram  
✅ Swipe para baixo fecha o detalhe  
✅ Cache local — funciona mesmo offline  
✅ Auto-sincroniza ao abrir  
