---
name: requisitos
description: Entrevista o usuário e escreve requisitos funcionais, não funcionais e o catálogo de regras de negócio com IDs. Use depois da descoberta ou quando precisar detalhar o que o sistema deve fazer.
---
# Requisitos
1. Leia docs/00-discovery. Se não existir, sugira rodar /discovery primeiro.
2. Para cada funcionalidade, pergunte: quem faz, o que acontece, o que pode dar errado, quem pode aprovar ou desfazer, qual a exceção mais comum, o que o sistema nunca pode permitir.
3. Peça números nos requisitos não funcionais (quantos usuários, tempo de resposta aceitável, quanto tempo fora do ar é tolerável). Se eu não souber, ofereça valores de referência e marque como SUPOSIÇÃO.
4. Grave, em arquivos separados:
   - docs/01-requisitos/requisitos-funcionais.md (RF-NNN, com critério de aceite no formato Dado/Quando/Então)
   - docs/01-requisitos/requisitos-nao-funcionais.md (RNF-NNN com número)
   - docs/01-requisitos/regras-de-negocio.md (RN-NNN: regra, de onde vem, exceções, exemplo)
   - docs/01-requisitos/glossario.md
5. Ao final, liste contradições e lacunas que encontrou.
6. Nunca gere código.