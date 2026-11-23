# Residência Nina — V003
Base independente iniciada a partir do projeto Concurso (portal público V343; estilo reutilizado da prévia V2; Metodologia Mestre v014 integral e todos os adendos de 23/11/2026). Não é uma cópia integral do portal V343.

## Executar
Site estático: publique gh-pages / raiz em Settings > Pages. Para desenvolvimento, sirva a raiz via HTTP (por exemplo python -m http.server 8000). Não abra via file://. Os módulos JS não usam servidor externo para dados.

## Implementado
- Painel, cartões com proposta e aprovação, histórico de versões, campos dos 11 critérios didáticos, pesquisa, relações recíprocas, revisão com resposta oculta e eventos SRS separados.
- Agenda 16 dias para aprovação; 4/8/16/32 e 64 após duas avaliações formais Fácil, conforme último adendo. Questão consultada não é avaliação.
- Registro de questões e lacunas, catálogo de imagens e PDFs por URL, prévias Drive sob demanda, cronômetro, agenda, exportação e restauração JSON de projeto.
- Armazenamento local isolado por chave residencia-nina-v001:state. Não lê dados, chaves, IDs, histórico ou tokens do Concurso.

## Google Drive e segurança
Pasta de destino: https://drive.google.com/drive/folders/16ublt1hA_tdX1VtGR3WiF0ObaO8BUBjS
A pasta foi encontrada vazia e com permissão anyone/writer. Restrinja antes de enviar material real. Use outra conta Google com acesso de editor, de preferência dona do acervo. Não reutilize IDs, Firebase, OAuth ou pastas do Concurso. Exportação local por enquanto; a sincronização permanece desativada até definir o e-mail; uma futura integração deverá ter cliente OAuth próprio, origem autorizada, escopo mínimo, seleção explícita da pasta, validação de permissões e prevenção de conflitos. Não publique tokens ou conteúdo privado no repositório público. noindex não é autenticação.

## Pendências para paridade V343
OAuth e sincronização automática, grifador PDF avançado, editor SVG/imagens, diário SRS remoto, sincronização de checkpoints e teste completo desktop/mobile autenticado. Nenhum conteúdo curricular foi inventado ou importado.

V003: a aba Metodologia e METODOLOGIA.md formalizam adoção integral, incluindo recorrência por 5 e 10 referências válidas, confirmação de cobertura e pesquisa em histórico/módulos. Cópia integral no Drive separado. A sincronização continua desativada.
