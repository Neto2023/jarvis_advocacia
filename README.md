# Jarvis Advocacia

**Sistema de automação para otimização de atendimento e gestão de escritórios de advocacia utilizando inteligência artificial.**

> A tecnologia prepara, o advogado decide.

[![Jarvis: um assistente que trabalha no seu escritório. Você só diz sim.](card.png)](https://neto2023.github.io/jarvis_advocacia/)

👉 **[Converse com o Jarvis agora](https://neto2023.github.io/jarvis_advocacia/)**: página interativa, com o Jarvis simulado (por texto e por voz), as travas de segurança para testar, a calculadora do tempo gasto hoje em triagem e o plano de implantação montado na hora.

---

## O que é

O Jarvis é um assistente que atende no WhatsApp do escritório, conduz a entrevista do caso novo, organiza documentos, prepara a pré-análise e a proposta de honorários, acompanha prazos, agenda e financeiro, e envia mensagens, arquivos e e-mails a clientes quando o advogado pede. O advogado fala com ele pelo WhatsApp ou por voz no computador, e nada com efeito fora do sistema acontece sem a confirmação dele.

Não é um protótipo. Está em operação contínua num escritório de advocacia em Marabá, no Pará, desde setembro de 2026, atendendo clientes reais, com prazo correndo.

## O que ele faz hoje

- **Atendimento no WhatsApp** — menu de caminhos, entrevista do caso novo conduzida por IA, leitura de texto, áudio, PDF e foto, pasta organizada por contato e aviso resumido ao advogado.
- **Pré-análise do caso** — resumo, enquadramento, viabilidade, pontos a confirmar, documentos faltantes e referência da tabela de honorários da seccional, entregues só ao advogado.
- **Proposta de honorários** — gerada em Word com os valores ditados pelo advogado, versionada, e enviada ao cliente em PDF apenas após prévia e confirmação.
- **Andamento ao cliente** — último movimento público do processo, em linguagem simples, somente dos processos vinculados àquele cliente.
- **Prazos e publicações** — publicações pela OAB e avisos do tribunal viram cartão de prazo e evento na agenda, sempre marcados para conferência humana.
- **Agenda** — prazos do painel no calendário, agenda do dia pela manhã e reuniões marcadas pelo próprio cliente em horários livres.
- **Financeiro** — extrato das contas do escritório por Open Finance, classificação ditada por mensagem e baixa automática das parcelas de honorários.
- **Assistente pessoal do advogado** — pelo WhatsApp ou por voz no computador (F9 fala, F10 cala, F8 confirma): consulta processos, prazos, agenda e financeiro, abre pastas, sites e sessões de análise e manda o que for pedido para o celular do advogado.
- **Envio a clientes por WhatsApp e e-mail** — mensagem, arquivo da pasta do caso ou e-mail com anexo, com o destinatário escolhido pelo nome no cadastro conferido; a prévia mostra nome, número ou e-mail completo, pasta e arquivos, e o envio só sai com o "sim".
- **Documentos** — procuração, declaração, contrato e minutas em Word com a identidade visual do escritório, sempre para revisão do advogado.

## Os princípios, que vêm antes do código

1. **Efeito externo só com prévia e confirmação.** Toda ação que sai do sistema — enviar mensagem, arquivo, e-mail ou proposta, marcar compromisso, baixar pagamento — passa por uma prévia montada pelo programa, com código de uso único, e só acontece depois do sim do advogado.
2. **Ao cliente, texto conferido.** A IA interpreta, classifica e resume; o que chega ao cliente é texto aprovado antes. Sem orientação jurídica, sem prazo, sem previsão de resultado, sem valor.
3. **Honorário é decisão humana.** O sistema não tem valor padrão, não calcula honorários e recusa gerar proposta sem o valor que o advogado ditar.
4. **Regra antes de modelo.** Contar dias úteis, ler um aviso oficial, casar um pagamento com uma parcela: código testado e previsível. A IA entra onde há linguagem humana a entender.
5. **Sigilo é desenho, não configuração.** Os dados dos clientes ficam no computador do escritório. O servidor guarda apenas o mínimo para o WhatsApp funcionar. Leitura onde basta ler; envio com permissão própria e só com o "sim".

## Onde ficam os dados

Pastas dos casos, documentos e transcrições permanecem na máquina do escritório. A transcrição de áudio e as respostas operacionais rodam em modelo local, sem sair do ambiente. O tratamento segue a Lei nº 13.709/2018 (LGPD) e o dever de sigilo profissional da advocacia.

## Frentes disponíveis

| Frente | Situação |
|---|---|
| Atendimento no WhatsApp | em operação |
| Assistente pessoal (WhatsApp e voz) | em operação |
| Envio a clientes por WhatsApp e e-mail | em operação |
| Painel de gestão do escritório | em operação |
| Prazos e publicações | em operação |
| Proposta e documentos | em operação |
| Financeiro com Open Finance | em operação |
| Assinatura eletrônica e CRM | em implantação |
| Presença nas redes (Instagram) | sob encomenda |
| Landing page e captação | sob encomenda |

## Quer ver funcionando no seu escritório?

A demonstração é feita com um caso real do seu escritório, no seu próprio número, e leva cerca de 30 minutos. Agendamento direto com a equipe da **Carajás HubTech**, em Marabá/PA, com atendimento remoto em todo o Brasil.

---

## Sobre este repositório

Este repositório é a **apresentação pública** do sistema. O código-fonte do Jarvis não é distribuído aqui: ele contém a operação de um escritório em funcionamento e está sob repositório privado.

Nenhum dado de cliente, nome, número de telefone ou número de processo consta deste material. Os exemplos apresentados são fictícios. Os números medidos (tempo de geração de proposta, tempo de transcrição, cobertura de testes) foram apurados em operação real, num único escritório, entre setembro e outubro de 2026, e variam conforme o volume e a infraestrutura de cada contratante.

Este material descreve software e serviços de uma empresa de tecnologia. **Não é publicidade de serviços de advocacia** e não constitui oferta de atividade privativa de advogado. A comunicação de cada escritório contratante é decisão e responsabilidade do próprio advogado, observados o Código de Ética e Disciplina e o Provimento nº 205/2021 da OAB.

© 2026 Carajás HubTech — Marabá, Pará. Todos os direitos reservados.
