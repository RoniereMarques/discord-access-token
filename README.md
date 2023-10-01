# Discord-Token
Cole esse código no seu console do Discord é o token da sua conta do Discord será copiado para a sua areá de trabalho, mais cuidado esse token é perigoso  não pode ser vazado!
# Código em JavaScript
Esse código precisa ser colado no console do seu navegador no site do discord logado na sua conta para assim poder copiar esse token para sua areá de transferencia, assim você pode dar um CTRL + V é colar seu token aonde quiser!
> [!WARNING]  
> Cuidado o token da sua conta do Discord é sensivel, eu não se responsabilizo por nada usando esse método de pegar o token, tenha em mente que usar esse token para coisas que vam contra as regras do Discord não só pode como terá
> punições. Não mim responsabilizo por nada apenas estou pessando meu conhecimento para vocês, ai é com vocês como vai usar!
``´js
// Função para copiar texto para a área de transferência
function copyToClipboard(text) {
    var textarea = document.createElement("textarea");
    textarea.value = text;
    document.body.appendChild(textarea);
    textarea.select();
    document.execCommand("copy");
    document.body.removeChild(textarea);
    alert('Copied successfully!')
}

// Chame a função com o texto que deseja copiar
copyToClipboard((webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!==void 0).exports.default.getToken());
```
