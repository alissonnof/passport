# Passaporte Fácil — site estático

Guia independente e gratuito para emissão do passaporte brasileiro. Feito em um único arquivo HTML (CSS e JavaScript inclusos), sem frameworks e sem dependências.

## Publicar no GitHub e Vercel

1. Extraia o ZIP `passaporte-facil-vercel.zip`.
2. No GitHub, crie um repositório e envie **o conteúdo da pasta extraída**, especialmente `index.html`, para a **raiz** do repositório. Não mantenha o `index.html` dentro de uma subpasta.
3. Na Vercel (<https://vercel.com/new>), selecione **Import Git Repository** e conecte o repositório criado.
4. Use o framework **Other**, sem comando de build. A pasta de saída é a raiz do projeto.
5. Clique em **Deploy**. A Vercel gerará uma URL pública.

Para testar localmente, abra `index.html` no navegador.

## Personalização

- Todo o conteúdo e estilo estão em `index.html`.
- A paleta fica nas variáveis CSS no início do arquivo.
- O checklist e as etapas concluídas são armazenados apenas no `localStorage` do navegador, sem envio de informações a servidores.
- O favicon está em `favicon.svg`.
- O site informa que é independente e não solicita dados pessoais nem pagamentos.

## Fontes oficiais verificadas em 27/10/2026

- Serviço: <https://www.gov.br/pt-br/servicos/obter-passaporte-comum-para-brasileiro>
- Documentos: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/lista-brasileiro>
- Formulário: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/preencher>
- Pagamento: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa/pagamento-da-taxa>
- Agendamento: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa/agendamento/agendar>
- Atendimento presencial: <https://www.gov.br/pf/pt-br/assuntos/passaporte/ajuda/duvidas_/atendimento/atendimento-instrucoes>
- Consulta: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa/agendamento/atendimento-presencial/consultar-andamento/instrucoes-de-consulta>
- Entrega: <https://www.gov.br/pf/pt-br/assuntos/passaporte/documentacao/formulario/pagar-taxa/agendamento/atendimento-presencial/consultar-andamento/entrega-do-passaporte/instrucoes-de-entrega>
- TSE: <https://www.tse.jus.br/servicos-eleitorais/certidoes/certidoes>
- Situação militar: <https://alistamento.eb.mil.br/>

Procedimentos e valores podem mudar. Atualize o conteúdo ao publicar se houver mudanças nas normas oficiais.
