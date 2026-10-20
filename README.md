# QBoa Digital

Site oficial do QBoa Digital, um utilitário open source para limpeza, privacidade e manutenção do Windows 10 e 11.

A versão **3.0** marca a primeira versão estável do aplicativo moderno, atualmente em estágio de MVP. O projeto é desenvolvido com Tauri e Rust, com interface em HTML, CSS e JavaScript.

## Versão atual

- **QBoa Digital 3.0** — primeira versão estável do aplicativo moderno. Consulte o [repositório do aplicativo](https://github.com/bloodshinoda/qboa-digital) e a página de [releases](https://github.com/bloodshinoda/qboa-digital/releases) para código-fonte, notas e artefatos publicados.
- **QBoa Digital 1.0 BAT** — [download](download/qboa-digital-1.0.zip), versão legada em script para rotinas simples.
- **QBoa Digital 2.0 BAT** — [download](download/qboa-digital-2.0.zip), versão legada em script para otimização simples.

As versões BAT são ferramentas legadas e distintas do aplicativo moderno 3.0. Os downloads da versão 3.0 devem ser obtidos pela página de releases do repositório do aplicativo quando os artefatos estiverem publicados.

## O que oferece

- Limpeza de arquivos temporários e caches selecionados.
- Ferramentas de privacidade e ajustes relacionados à telemetria.
- Diagnóstico e manutenção do Windows com DISM e SFC.
- Presets de execução Express, Normal e Turbo.
- Proteções para operações avançadas, incluindo pontos de restauração quando disponíveis, snapshots e rollback para alterações reversíveis.
- Execução e registro de tarefas pelo backend Rust, com controle de cancelamento.

Operações como limpeza de arquivos, verificações e reparos do Windows não possuem rollback granular. A disponibilidade de pontos de restauração depende da configuração do próprio Windows. Leia as informações e confirmações apresentadas pelo aplicativo antes de executar tarefas avançadas.

## Repositórios

- [Código-fonte do aplicativo e releases](https://github.com/bloodshinoda/qboa-digital)
- [Repositório deste site](https://github.com/Qboadigital/qboadigital.github.io)

## Política de versões

A linha de versões estáveis segue uma sequência incremental:

- **3.0**, **3.1**, **3.2**… para versões com novas funcionalidades e melhorias.
- **3.0.1**, **3.0.2**… apenas para correções pontuais da versão correspondente.

## Licenças

O conteúdo deste site é licenciado sob a [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](LICENSE). Você pode compartilhar e adaptar o material, desde que atribua a autoria e distribua eventuais adaptações sob a mesma licença.

O aplicativo QBoa Digital e seu código-fonte são licenciados sob a GNU General Public License v3.0 (GPL-3.0). Consulte o [repositório do aplicativo](https://github.com/bloodshinoda/qboa-digital) para os termos e o código-fonte correspondentes.
