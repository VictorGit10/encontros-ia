# Encontros individuais — LAPIG

Página de agendamento para os encontros de 13 a 30 de outubro de 2026.

Site: https://victorgit10.github.io/encontros-ia/

A interface está no GitHub Pages. Reservas e descrições são armazenadas exclusivamente no Apps Script; este repositório contém apenas a interface pública. A conexão usa requisições sem cookies ou sessão do Google.

O acesso administrativo exige uma chave privada validada pelo servidor. Essa chave não está neste repositório.

A integração do Apps Script cria eventos no Google Agenda, envia convites e confirmações e sincroniza cancelamentos. Falhas de envio são tentadas novamente por um acionador a cada cinco minutos. O painel privado informa pendências e permite solicitar nova sincronização. A inclusão na agenda de convidados depende das configurações e da aceitação do convite.
