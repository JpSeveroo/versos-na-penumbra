# PROTOCOLO.md

**Projeto:** *Versos na Penumbra*  
**Objetivo do Documento:** Estabelecer o fluxo de trabalho imutável para planejamento, redação modular, atualização de estado e revisão cruzada de cada capítulo produzido no Antigravity, eliminando furos de continuidade, anacronismos e inconsistências psicológicas.

---

## 1. PROPÓSITO DO DOCUMENTO

Este protocolo funciona como o manual operacional do projeto. Nenhuma linha de prosa deve ser redigida no diretório `02_CAPITULOS/` sem a execução prévia da ordem de leitura, e nenhum capítulo será considerado finalizado sem o cumprimento do ciclo pós-escrita e a atualização do arquivo `ESTADO_ATUAL.md`.

---

## 2. ORDEM DE CONSULTA ANTES DE ESCREVER UM CAPÍTULO

Antes de gerar qualquer cena de um novo capítulo (`00X.md`), a IA/Antigravity deve ler e cruzar os arquivos de fundação e estilo na seguinte sequência obrigatória:

1. **`00_FUNDACAO/BIBLIA.md`**: Relembrar o tom geral, os temas fundamentais e a regra pétrea do livro (*proibição mútua de descoberta de identidade*).
2. **`00_FUNDACAO/ACONTECIMENTOS_HISTORICOS.md`**: Verificar as condições climáticas de 1816 (*O Ano Sem Verão*), a pressão socioeconômica sobre as terras de Hampshire e as leis de *Coverture* vigentes.
3. **`00_FUNDACAO/PERSONAGENS.md`**: Revisar a voz, a caligrafia, as feridas internas e a máscara social dos personagens presentes na cena.
4. **`00_FUNDACAO/ESTRUTURA.md`**: Checar o objetivo narrativo específico, os acontecimentos obrigatórios e o gancho final do capítulo em produção.
5. **`00_FUNDACAO/LINHA_TEMPORAL.md`**: Confirmar o dia exato da semana, a hora da ação e o encadeamento temporal em relação ao capítulo anterior.
6. **`00_FUNDACAO/ESTADO_ATUAL.md`**: Consultar a "memória RAM" da história (onde cada personagem dormiu, o que sabem, o que ignoram e o estado físico do livro de Milton).
7. **`01_ESTILO/GUIA_DE_ESTILO.md`**: Calibrar a prosa, a cadência dos diálogos, o vocabulário de época e as proibições estéticas.

---

## 3. PROCESSO DE ESCRITA DO CAPÍTULO

### 3.1 Nomenclatura e Localização do Arquivo
* O arquivo deve ser salvo exclusivamente em: `02_CAPITULOS/00X.md` (utilizando numeração arábica com três dígitos no nome do arquivo: `001.md`, `002.md`, etc.).

### 3.2 Formatação Obrigatória do Cabeçalho
Todo início de capítulo deve conter a seguinte estrutura visual padronizada, sem adições ou ornamentos fora deste modelo:

```text
# Capítulo [Número em Algarismo Romano]

## [Título do Capítulo conforme ESTRUTURA.md]

*Blackwood Hall, Hampshire — [Data por extenso conforme LINHA_TEMPORAL.md] — POV: [Nome do Personagem]*

---

[Início do texto em prosa corrida...]
```

### 3.3 Regras de Formatação do Corpo de Texto
* **Numeração de Capítulo:** Algarismos romanos no título interno (`# Capítulo I`, `# Capítulo II`, etc.).
* **Indicação de Ponto de Vista:** Linha de POV visível no cabeçalho inicial.
* **Quebras de Cena Internas:** Mudanças de tempo ou espaço dentro do mesmo capítulo devem ser feitas **exclusivamente com espaçamento em branco extra** (duas linhas vazias entre parágrafos), sem o uso de asteriscos (`***`), linhas horizontais (`---`) ou glifos decorativos.
* **Restrições Severas:** É expressamente proibido o uso de emojis, gírias contemporâneas, termos em inglês moderno não assimilados na Regência ou notas de rodapé ficcionais.
* **Meta de Extensão:** Média de 3.000 a 3.800 palavras por capítulo para atingir a meta global de ~80.000 a 85.000 palavras em 24 capítulos.

---

## 4. PROCESSO PÓS-ESCRITA (OBRIGATÓRIO)

Assim que o texto bruto do capítulo for finalizado, a IA executará imediatamente duas tarefas antes de qualquer solicitação de novo conteúdo:

### 4.1 Atualização de `00_FUNDACAO/ESTADO_ATUAL.md`
O arquivo de memória operacional deve ser atualizado com:
* O avanço da data/hora no relógio da narrativa.
* A posição geográfica/aposento exato de Arthur, Helena e secundários ao término do capítulo.
* O estado do volume de *O Paraíso Perdido* (página aberta, cor da fita marcadora, se houve nova anotação em nanquim preto ou tinta sépia, e qual o teor exato da última frase escrita).
* Informações reveladas ou novos segredos descobertos por cada indivíduo.
* Atualização do inventário de objetos em trânsito (chaves, cartas, lenços, frascos de tinta).

### 4.2 Geração da Ficha de Auditoria em `03_REVISOES/`
Deve ser criado o arquivo `03_REVISOES/00X_revisao.md` contendo o relatório detalhado da auditoria cruzada (conforme checklist da Seção 5).

---

## 5. CHECKLIST DE REVISÃO CRUZADA

A análise pós-capítulo registrada em `03_REVISOES/00X_revisao.md` deve responder pontualmente aos seguintes tópicos:

### 5.1 Consistência de Personalidade
* **Arthur:** Manteve a frieza cortês, a postura engomada e a reserva monossilábica nos salões? Nas margens, revelou a vivacidade e a vulnerabilidade condizentes com seu arco?
* **Helena:** Manteve o orgulho vigilante e o olhar perspicaz sem parecer insolente de forma inverossímil perante a nobreza? Sua voz nas margens foi audaciosa e erudita?
* **Secundários:** Julian foi o contraponto irreverente sem se tornar vulgar? Lady Eleanor agiu guiada pelo medo aristocrático do declínio e não por vilania de desenho animado?

### 5.2 Consistência Cronológica e Climática
* O capítulo respeitou rigorosamente o dia e a hora estipulados na `LINHA_TEMPORAL.md`?
* Os efeitos do outono chuvoso e frio de 1816 (*O Ano Sem Verão*) estão presentes sensorialmente (vidros embaçados, cheiro de lenha molhada, umidade nas saias, lama nas estradas)?

### 5.3 Regras do Universo & Convenções Sociais da Regência
* Houve quebra indevida das regras de decoro? (Helena e Arthur nunca devem ficar a sós em quartos fechados sem justificativa física crível ou sem o risco palpável de ruína social).
* A assimetria de classes foi respeitada? (Helena é tratada como dependente e sobrinha da bibliotecária, não como dama apresentada à corte nem como criada uniformizada).
* A regra de ouro da *marginalia* foi violada? (Nenhum dos dois pode tentar ativamente descobrir o nome civil do outro antes do ponto previsto na escaleta).

### 5.4 Continuidade de Objetos, Pistas e Cenário
* As tintas foram usadas corretamente? (Helena = pena fina com tinta sépia; Arthur = pena de ganso com nanquim preto puro).
* A fita verde de gorgorão mudou de página conforme o diálogo avançou?
* Traços físicos deixados (manchas de tinta nos dedos, marcas de fuligem, cheiro de lavanda no lenço) persistiram no capítulo seguinte?

### 5.5 Aderência ao Guia de Estilo
* Os diálogos têm cadência rápida e subtexto afiado?
* A narração em terceira pessoa equilibra o distanciamento da comédia de costumes com a intimidade emocional dos dois pontos de vista?
* Os verbos de elocução foram variados com elegância, evitando repetições exaustivas de "disse ele / disse ela"?

---

## 6. CRITÉRIOS DE APROVAÇÃO DO CAPÍTULO

Um capítulo só será integrado ao volume oficial de compilação (`04_LIVRO_FINAL/LIVRO_FINAL.md`) e liberado para o avanço da escrita quando atender a **100% dos seguintes critérios**:

* [ ] Cabeçalho estruturado estritamente com algarismos romanos, local, data e POV explícito.
* [ ] Nenhuma quebra de cena com símbolos gráficos, utilizando apenas o espaçamento em branco duplo.
* [ ] Zero ocorrências de emojis, marcadores anacrônicos ou quebras de quarta parede.
* [ ] Auditoria de `03_REVISOES/00X_revisao.md` sem apontamento de furos de roteiro ou contradições temporais.
* [ ] `00_FUNDACAO/ESTADO_ATUAL.md` devidamente atualizado com as novas coordenadas de enredo.
* [ ] Validação e aceite explícito do Autor.