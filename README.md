# Teleprompter

Teleprompter para navegador, pensado para iPhone e iPad. Os roteiros ficam guardados **criptografados** (AES-256) no branch `data` deste repositório e sincronizam entre todos os aparelhos. Só quem tem a senha consegue ler.

## Primeiro uso
1. Abra o site. Na primeira vez aparece a tela **Configuração inicial**.
2. Crie um token em https://github.com/settings/personal-access-tokens/new
   - Repository access: *Only select repositories* → este repositório
   - Permissions → Contents: **Read and write**
3. Cole o token, crie a senha, salve. Pronto: nos outros aparelhos basta digitar a senha.

## Dicas
- No iPhone: Safari → Compartilhar → **Adicionar à Tela de Início** (abre em tela cheia).
- `# Título` vira seção (botão ☰ para pular). `[PAUSA]` aparece como nota discreta. `**palavra**` em negrito.
- Tocar na tela inicia/pausa; arrastar ajusta a posição.
- Controle/pedal Bluetooth: espaço = iniciar/pausar, ←/→ ou PageUp/PageDown = voltar/avançar, +/− = velocidade.
- Funciona sem internet depois de aberto uma vez; as alterações sobem quando a conexão voltar.
- `?demo` no endereço abre um modo de teste sem login (nada é salvo).
