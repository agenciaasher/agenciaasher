# Agência Asher — Regras Globais

Estas regras se aplicam a todo trabalho gerado neste repositório, independente do cliente ou entregável.

## Linguagem e escrita

**Escreva como um ser humano escreve.**

- Sem travessões (—). Use vírgula, ponto ou reescreva a frase.
- Sem cara de IA: proibido usar "certamente", "claro!", "com prazer", "é fundamental ressaltar", "tendo em vista", "no contexto de", "neste sentido", "destaca-se que", "é importante mencionar", "vale ressaltar", "cabe destacar", "sendo assim", "portanto" no início de frase sem necessidade real.
- Sem exagero de intensificadores: "extremamente", "absolutamente", "totalmente", "incrivelmente".
- Sem formalidade desnecessária. O texto deve soar como alguém que conhece o assunto e fala direto.
- Frases curtas quando possível. Parágrafos curtos.
- Perguntas retóricas com moderação — quando usadas, que sejam genuínas.
- Voz ativa sempre que possível.

### O que revisar antes de entregar qualquer texto

Leia em voz alta (mentalmente). Se soar robótico, reescreva. Se tiver travessão, troque. Se a frase começar com "Certamente" ou "É importante que", delete e recomece.

### Exemplos práticos

| Evitar | Usar |
|--------|------|
| "É fundamental ressaltar que o público..." | "O público..." |
| "Neste sentido, a estratégia deve..." | "A estratégia deve..." |
| "Certamente, o melhor caminho é..." | "O melhor caminho é..." |
| "tendo em vista os dados coletados — que confirmam..." | "Os dados confirmam..." |
| "Vale destacar que Ramon é o rosto da marca" | "Ramon é o rosto da marca" |

## Skill obrigatória: escrita-humanizada

Toda vez que gerar ou revisar texto para qualquer cliente ou entregável, aplique os padrões da skill `/escrita-humanizada` (`.claude/skills/escrita-humanizada.md`).

A skill detecta e corrige 24 padrões de escrita de IA, incluindo:
- Vocabulário típico de IA (adicionalmente, testemunho, cenário, evidenciando...)
- Travessão excessivo
- Paralelismos negativos ("não é apenas X, é Y")
- Regra de três forçada
- Linguagem promocional vazia
- Tom bajulador ou servil
- Frases de enchimento e conclusões genéricas

Uso: chame `/escrita-humanizada` passando o texto. O resultado é o texto reescrito sem marcas de IA.

## Tom geral da agência

Direto, confiante, sem enrolação. A Agência Asher entrega resultado, não relatório bonito. O texto reflete isso.
