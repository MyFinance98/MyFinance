# My Finance — PWA 2.0

Aplicação web progressiva (PWA) para acompanhar o plano financeiro familiar de seis meses.

## Funcionalidades
- Capital mensal base editável e distribuição automática: Segurança 35%, Investimentos 20%, Novas oportunidades 20%, Fundo familiar / Filho 15%, Poupança pessoal 10%.
- Aba **Entradas extra**: adicione rendimentos assim que os receber. São distribuídos imediatamente pelos cinco fundos e não exigem fechar o mês.
- Registo de até seis contribuições mensais. As entradas extra são contabilizadas no relatório do período e não são duplicadas ao registar a contribuição mensal.
- Aba **Documentos**: guardar PDFs e imagens até 10 MB cada, com descrição e associação geral/entrada extra/contribuição mensal. O arquivo usa IndexedDB no navegador.
- Relatório detalhado exportável em PDF.
- Gráfico, tabela, histórico, cópia de segurança JSON e instalação PWA.

## Atualizar no GitHub Pages
1. Abra o repositório `my-finance`.
2. Substitua os ficheiros `index.html`, `sw.js` e `README.md` pelos desta versão (pode manter `manifest.webmanifest` e `icon.svg`).
3. Confirme as alterações na branch `main`.
4. Aguarde a publicação do GitHub Pages.
5. No Xiaomi, feche a aplicação instalada e volte a abri-la. Se continuar a mostrar a versão antiga, abra a página no Chrome, atualize-a e limpe os dados/cache do site ou remova e instale novamente a PWA.

## Armazenamento e privacidade
Os dados financeiros ficam em `localStorage` e os documentos em `IndexedDB`, apenas neste navegador/dispositivo. Não existe sincronização na nuvem nem autenticação nesta versão. Limpar os dados do site pode apagar os registos e documentos. Faça cópias de segurança JSON regularmente. O PDF é gerado no próprio dispositivo.
