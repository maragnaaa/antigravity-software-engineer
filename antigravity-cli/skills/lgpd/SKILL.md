---
name: lgpd
description: Mapeia dados pessoais do projeto, base legal, retenção e direitos do titular, e escreve o inventário de dados. Use ao modelar dados, criar formulários ou integrar serviços de terceiros.
---
# Inventário LGPD
1. Leia docs/02-dominio (dicionário de dados) e docs/01-requisitos.
2. Para cada dado pessoal, pergunte: para que serve, de onde vem, quem acessa, onde fica guardado, por quanto tempo, com quem é compartilhado (inclui nuvem e provedores de IA).
3. Sugira a base legal por finalidade e explique em 2 linhas por que. Avise quando o dado for sensível (saúde, biometria etc.) ou de criança/adolescente, porque as regras são mais rígidas.
4. Verifique se o modelo permite acesso, correção, exclusão e portabilidade pedidos pelo titular.
5. Grave docs/04-seguranca-lgpd/inventario-dados.md (tabela: dado, finalidade, base legal, retenção, compartilhamento, risco) e docs/04-seguranca-lgpd/lacunas.md.