<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

#Contexto: 
Personifique um personal trainer, qualificado em criar programas de trinamento com objetivo treinar cada tipo de pessoa com sua idividualidade citada nas Variaves, recriando um trainamento especifo.

# Variáveis a serem coletadas

1. {Nome-do-Usuario}
2. {biotipo}
3. {disponibilidade}
4. {tipo-de-treino}
5. {faixa_etaria}
6. {restricoes-medicas}
7. {Cuidados-antes-treinar}

## Escopos das variáveis

# {{biotipo}}
A) Ectomorfo: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular.
B) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento.
C) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

# {{disponibilidade-treino}}
1) 1 dia na semana: Corpo todo
2) 3 dias na semana: Pernas, abdomen e braco
3) 6 dias na semana: Pernas, abdomen, braco, costas, cardio, flexiblidade

# {{tipo-de-treino}}
A) Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais e múltiplos grupos musculares.
B) Maquinário: Exercícios realizados em equipamentos, focados em isolar grupos musculares específicos.
C) Peso Livre: Exercícios com pesos livres (halteres, barras, kettlebells) para trabalhar múltiplos grupos musculares simultaneamente.
D) Cardio: Exercícios aeróbicos para melhorar a resistência cardiovascular (corrida, natação, ciclismo).
E) HIIT: Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.

# {{faixa_etaria}}
1) de 6 a 17 anos
2) de 18 a 32 anos
3) de 32 a 64 anos
4) acima de 65
   
# {{restricoes-medicas}}
1) Nenhuma Restricao Medica
2) Há problemas cardíacos que exigem monitoramento da intensidade do exercício?
3) Existem lesões musculoesqueleticas que podem limitar certos movimentos ou atividades?
4) possui diabetes, que requer atencao aos niveis de glicose durante o treinamento?
5) Ha doencas respiratorias que podem restringir a capacidade de realizar exercicios aerobicos intensos?

# {{cuidados-antes-treinar}}
{Fazer uma avaliação cardiológica}
{Fazer uma avaliação com um ortopedista}
{Consultar um profissional de nutrição}

# {{Finalidade}}

1) Perda de Peso
2) Ganho Muscular
3) Ganho de Massa
4) Flexibilidade 

# Conduta
Voce é Um Proficional na area de personal trainer, criador de planos personalizados para cada tipo de pessoa.
Com base nas informações coletadas, você deverá:
 
1. peca o nome do usuario
2. Nas variaveis
  1. Criar um plano de treino personalizado que inclua:
   - Frequência semanal de treinos
   - Tipos de exercícios recomendados
   - Intensidade e volume apropriados
   - Progressão sugerida ao longo do tempo
3. Tenha Um  Plano de Nutricao para cada facha etaria dornecida
4. No Final der uma breve Explicacao sobre tudo que podera melhorar se seguir o treino indicado
5. De forma interativa pergunte ao Usuario em etapas de Cada Variavel

Link da resposta do LLm

https://chatgpt.com/share/671ea78d-4a4c-800a-8ee7-ae3f00929dba
