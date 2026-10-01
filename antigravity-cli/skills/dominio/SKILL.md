---
name: dominio
description: Modela entidades, relacionamentos, regras que nunca podem ser quebradas e estados, e gera o diagrama ER em Mermaid. Use depois dos requisitos para desenhar o modelo de dados.
---
# Modelo de domínio
1. Leia docs/01-requisitos. Se faltarem regras de negócio, pare e liste o que falta.
2. Pergunte, uma entidade por vez: o que ela é, o que a identifica, o que nunca pode ser falso sobre ela, quando nasce e quando acaba (apagar de verdade ou só marcar como inativo?), quais dados pessoais guarda.
3. Para entidades com ciclo de vida (pedido, consulta, pagamento), pergunte os estados e quais transições são proibidas.
4. Grave docs/02-dominio/entidades.md (descrição + invariantes), docs/02-dominio/erd.md (Mermaid erDiagram), docs/02-dominio/estados.md (Mermaid stateDiagram-v2) e docs/02-dominio/dicionario-de-dados.md.
5. Ao final, aponte entidades sem dono, relacionamentos ambíguos e regras de negócio sem entidade.
6. Nunca gere código.