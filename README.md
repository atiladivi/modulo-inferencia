# Módulo Inferência

Ferramenta de análise de modelos de regressão (inferência estatística) para avaliação de imóveis, de acordo com a NBR 14653-2. Faz parte da Central.

- Arquivo único: `index.html`. Abre direto no navegador e faz todo o cálculo no próprio navegador. Nenhum dado sai do computador.
- Lê laudos em PDF (formulário Laudo de Avaliação), modelos do SisDEA (.sda, relatórios .xls e PDF) e do TS-Sisreg (.tsr, relatório .rtf), planilhas (.xlsx, .xls, .csv) e projetos `.inferencia`.
- Grava em .sda, .tsr, Excel e projeto, e exporta o relatório no formato do SisDEA (.xlsx).
- Revisão automática: parte do modelo atual ou do arquivo como chegou, refaz o modelo, audita os dados, investiga as exclusões do autor, busca e compara modelos alternativos e grava um relatório (.txt) para o agente de revisão do Copilot. Cada opção encontrada pode ser montada no modelo atual com um clique.

Versão atual: **1.34.1** (15/10/2026).

Ferramenta de apoio à análise. Não substitui o laudo nem a responsabilidade técnica do avaliador.
