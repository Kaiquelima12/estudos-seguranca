# 🛡️ Meus Estudos de Segurança - Syfe

### 🚀 Regras de Ouro (HackerOne)
- **Cabeçalho Obrigatório:** `X-HackerOne-Research: tiggersecurity`
- **Ambiente de Teste:** `uat-bugbounty.nonprod.syfe.com`

### 💡 Lições Aprendidas
1. **Impacto Real > Risco Teórico:** Não basta achar o erro de CORS (asterisco `*`). Tenho que provar que consigo ler dados sensíveis (e-mail, nome, saldo) usando o Console do navegador.
2. **Escopo:** Sempre conferir se o domínio está na lista de ativos permitidos para não trabalhar de graça.

### 🛠️ Comandos Úteis
- **Teste de CORS (Console):** Usar o script de `fetch` para validar a exfiltração de dados.
- 
