# My Finance 5.0

Aplicação PWA de gestão financeira familiar.

## Funcionalidades
- Distribuição automática do capital pelas cinco categorias (35%, 20%, 20%, 15%, 10%).
- Entradas extra adicionadas a qualquer momento e distribuídas imediatamente.
- Confirmação do valor do capital base com a tecla Enter.
- Registo de cada mês individualmente, com exportação PDF por mês.
- Eliminação individual de um mês, retirando o respetivo valor do acumulado e mantendo os outros meses.
- Arquivo local de documentos PDF e imagens através do IndexedDB.
- Dados financeiros guardados localmente no navegador.

## Publicar no GitHub Pages
1. Carregue os cinco ficheiros deste pacote para a raiz do repositório.
2. Em Settings > Pages, selecione Deploy from a branch, `main` e `/(root)`.
3. Abra o endereço HTTPS publicado.

## Nota sobre dados
Os dados financeiros e documentos ficam guardados localmente neste navegador/dispositivo. Não existe sincronização automática entre dispositivos. Não limpe os dados do navegador nem desinstale a aplicação sem antes confirmar que tem os dados de que precisa.


Versão 5.0 — inclui as abas ‘Distribuir capital’ (pré-visualização e confirmação de novo capital) e ‘As minhas contas’ (saldo atual, saldo ideal e diferença). As novas distribuições são acrescentadas aos saldos existentes sem substituir os valores anteriores.
- Menu Bento no canto superior esquerdo, com acesso às páginas e atalhos para histórico, relatórios e definições.
