# Estação da Saúde — site para GitHub Pages

Site da EMEB Vereador Evaldo Staidel, apresentado pelo 9º ano no JEPP 2026 — Geração Empreendedora. O conteúdo do documento fornecido foi organizado para leitura na internet, preservando as propostas e os cuidados descritos. As atividades e os resultados são apresentados como previstos, não como já realizados.

## Arquivos

- `index.html`: página completa, com os estilos e os controles de acessibilidade.
- `assets/logo-escola.png`: logo da instituição.
- `assets/logo-projeto.jpg`: logo da Estação da Saúde.
- `roteiro-narracao.txt`: texto para leitura, revisão ou gravação futura.
- `.nojekyll`: permite servir diretamente os arquivos estáticos no GitHub Pages.

Mantenha a pasta `assets` junto ao arquivo `index.html`. Não envie apenas o HTML, pois as logos são arquivos separados.

## Como publicar no seu GitHub

1. Extraia o ZIP e abra a pasta `estacao-da-saude`.
2. Envie seu conteúdo para o repositório que será usado no site. O `index.html` deve ficar na raiz da pasta publicada; preserve a pasta `assets`.
3. No repositório, entre em **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Selecione a branch que recebeu os arquivos, normalmente **main**, e a pasta **/(root)**. Clique em **Save**.
6. Aguarde a publicação e abra o endereço mostrado pelo GitHub. Se você já configurou um domínio próprio, mantenha a configuração existente e o arquivo `CNAME`, se houver. Não substitua arquivos de outros projetos sem antes verificar onde esta página ficará.

Se o site atual já tiver uma página inicial, você também pode colocar esta pasta em um subdiretório, por exemplo `estacao-da-saude/`, mantendo a publicação existente. O endereço final incluirá esse caminho.

Orientação oficial: https://docs.github.com/pt/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Recursos de acessibilidade

- Leitura em voz alta em português por síntese de voz do navegador, iniciada somente quando o visitante aciona **Ouvir página**.
- Botões de pausa, continuação e parada; ajuste de velocidade. Ao continuar, o trecho interrompido recomeça para maior compatibilidade entre aparelhos.
- O texto da narração é extraído da página, incluindo os exemplos nas seções expansíveis. O arquivo TXT é uma cópia para consulta; atualize-o se alterar o conteúdo.
- A narração não é uma gravação MP3 ou WAV. A disponibilidade e a qualidade da voz dependem do navegador, do sistema e das vozes instaladas. Algumas vozes podem precisar de internet. Um navegador sem suporte mostra uma mensagem e mantém o texto disponível.
- Texto ampliável, alto contraste, link para pular ao conteúdo, navegação por teclado, foco visível, descrições das logos e estrutura para leitores de tela.
- VLibras integrado por meio do script oficial. A versão atual inicializa o widget automaticamente. Precisa de internet; o carregamento e a tradução dependem do serviço externo. A tradução automática pode conter limitações e não substitui um intérprete.

Integração oficial do VLibras: https://vlibras.gov.br/doc/widget/installation/webpageintegration.html

## Antes da feira

Abra o endereço publicado em um celular e computador. Confira as logos, acione **Ouvir página**, pause, continue e altere a velocidade. Confirme que há uma voz em português no aparelho. Teste o botão flutuante do VLibras e a tradução de um parágrafo com a conexão disponível no local. Navegue por teclado e confira contraste e ampliação. Os testes automatizados dos controles não substituem essa conferência real de voz, tradução e uso com leitores de tela.

O QR Code ficou para a etapa final, conforme solicitado. Ele deve apontar para a URL definitiva deste projeto após a publicação. Nenhum QR Code provisório foi incluído.

## Alterações futuras

O site não precisa de instalação, banco de dados ou ferramentas de compilação. Para atualizar textos, edite o `index.html`. As atividades não possuem formulários de coleta de dados de saúde, calculadoras de diagnóstico ou cadastros de participantes.
