# ◈ NotaHub

Central de consulta acadêmica | HTML, CSS e JavaScript | SPECTION

## Funcionalidades

Dashboard, busca por nome ou RA, filtros por turma, disciplina, período, avaliação e situação; importação CSV/JSON, exportação JSON e tema claro/escuro.

## Uso

Abra `index.html` no navegador ou acesse https://alexsandsouza.github.io/notahub/ após a publicação. Em Importar registros, carregue a demonstração fictícia ou um arquivo local autorizado. O CSV utiliza ponto e vírgula e o cabeçalho `ra;nome;turma;disciplina;periodo;avaliacao;nota;transversal`. A versão atual aceita nota de 0 a 8 e transversal de 0 a 2; confirme a regra institucional antes do uso real. Campos vazios indicam pendência.

## Privacidade

Os dados ficam na memória da página e são descartados ao recarregar. Não há autenticação nem armazenamento remoto. Nunca publique atas, notas reais, credenciais ou exportações no repositório. Use dados fictícios para demonstrações públicas.

## Publicação

Settings → Pages → Deploy from a branch → main → / (root) → Save. Não requer build. A ativação e os testes de implantação devem ser confirmados antes de declarar a versão publicada.

## Desenvolvimento

Documentação em `docs/` e especificações em `specs/`. Processo [SPECTION](https://github.com/alexsandsouza/spection): Discover, Specify, Architect, Plan, Build, Verify, Release.

## Estado

MVP estático. Testes de navegador e publicação ainda precisam de confirmação.
