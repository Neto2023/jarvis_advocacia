# Manifesto do Jarvis

*Carajás HubTech — Marabá/PA*

## Por que o Jarvis existe

Um escritório de advocacia pequeno vive entre dois mundos. De um lado, clientes que chegam pelo WhatsApp, a qualquer hora, com áudios, fotos de contratos e dúvidas urgentes. Do outro, prazos que correm em dias úteis, intimações espalhadas por tribunais diferentes, extratos, agendas e propostas por escrever. O advogado passa o dia trocando de tela, e o tempo que deveria ir para pensar o caso vai para copiar, conferir e lembrar.

O Jarvis nasceu para devolver esse tempo. Ele atende, organiza, lembra, rascunha e avisa, para que o advogado faça o que só ele pode fazer: julgar, decidir e defender.

## O que acreditamos

**1. O advogado decide; a máquina prepara.**
O Jarvis nunca age sozinho no que tem consequência. Toda ação que muda algo fora dele — enviar mensagem, arquivo, e-mail ou proposta, marcar atendimento, gravar contrato, vincular processo, dar baixa em pagamento — passa por uma prévia conferida pelo sistema e só acontece depois da confirmação do advogado, com código de uso único. O advogado assume qualquer conversa quando quiser, e devolve quando quiser.

**2. Ao cliente, cuidado e verdade.**
A IA acolhe, escuta, pede os documentos certos e explica em linguagem simples. Ela não dá orientação jurídica, não promete resultado e não fala de valores: isso é do advogado. O que sai para o cliente é conferido por regras no código, não apenas pela boa vontade do modelo.

**3. Honorários são decisão humana.**
O sistema consulta a tabela de honorários da seccional como piso ético de referência e mostra ao advogado. O valor que vai ao cliente é sempre o que o advogado disser.

**4. Sigilo profissional é inegociável.**
Os dados dos clientes ficam no computador do escritório. O servidor guarda o mínimo necessário para o WhatsApp funcionar. Senhas e chaves nunca entram no código nem no histórico. Banco e consulta processual são acessados só para leitura; no e-mail, a permissão de envio é separada da de leitura e só é usada depois do "sim" do advogado. O tratamento segue a LGPD e o Estatuto da Advocacia.

**5. Fonte ou silêncio.**
Quando o Jarvis fala de lei, decisão ou prazo, ele diz de onde tirou. Prazo calculado pela máquina é sempre marcado como provisório, até o advogado confirmar.

**6. Regra antes de modelo.**
O que pode ser resolvido por regra — ler um aviso oficial, contar dias úteis, casar um pagamento com uma parcela — é resolvido por regra, testada e previsível. A IA entra onde há linguagem humana a entender: uma conversa, um áudio, um contrato.

**7. Nada se perde.**
Cada mudança é testada, registrada e acompanhada de backup, com retorno ao estado anterior em minutos. O que foi feito, por que e como desfazer fica escrito.

**8. Feito com quem usa.**
O Jarvis é construído em conversa diária com o advogado que o usa. Cada correção nasceu de um caso real: uma proposta que relativizou a tese, um cliente que ouviu a mesma pergunta três vezes, uma tabela que trouxe a área errada. O sistema melhora porque escuta.

## Como ele é feito

Um conjunto de serviços pequenos, cada um com uma responsabilidade única, escritos em Node.js e cobertos por testes automáticos executados antes de cada mudança em produção. Modelos de linguagem na nuvem cuidam da conversa e do rascunho; modelos locais cuidam da transcrição de áudio e das respostas operacionais, onde o dado não deve sair do escritório.

## O que o Jarvis não é

- Não substitui o advogado nem assina por ele.
- Não é robô de disparo em massa: fala com quem procurou o escritório.
- Não guarda dados de clientes em serviços de terceiros além do necessário para funcionar.
- Não é produto de prateleira. É a forma de trabalhar de um escritório, escrita em código, e adaptada a cada contratante.

---

*A tecnologia prepara, o advogado decide.*
