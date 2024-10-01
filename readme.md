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

1. Introdução:
Objetivo: Criar um prompt que gere um plano de treino personalizado, considerando as variáveis de biotipo, tempo disponível e preferências de exercício.
Contexto: O prompt será utilizado para criar um assistente virtual que atua como um personal trainer, oferecendo planos de treino sob medida.
2. Biotipos Corporais:
Classificação: Ectomorfo (magro), mesomorfo (atlético) e endomorfo (tendência à gordura).
Características: Cada biotipo possui características físicas e metabólicas distintas que influenciam a resposta ao treino.
Prompt: Para cada biotipo, definir qual a melhor abordagem de treino (hipertrofia, força, resistência, etc.).
3. Dias Disponíveis para Treino:
Frequência: Variar a frequência dos treinos de acordo com a disponibilidade do usuário.
Intensidade: Ajustar a intensidade dos treinos com base na frequência.
Prompt: Criar uma lógica que permita ajustar o volume e a intensidade do treino de acordo com os dias disponíveis.
4. Tipos de Exercícios:
Preferências: Permitir que o usuário escolha os tipos de exercícios preferidos (cardio, musculação, funcional, etc.).
Contraindicações: Considerar possíveis contraindicações ou limitações físicas do usuário.
Prompt: Criar uma lista de exercícios para cada tipo e permitir que o usuário escolha os seus preferidos.
5. Regras de negócio:
Objetivos: Definir os objetivos do treino (perda de peso, ganho de massa muscular, definição, etc.).
Restrições: Considerar restrições como lesões, gravidez, idade, etc.
Progressão: Implementar um sistema de progressão para evitar o efeito platô e garantir resultados contínuos.
6. Material de Apoio:
Base de dados: Criar uma base de dados com exercícios, suas características e benefícios.
Modelos de treino: Desenvolver modelos de treino pré-definidos para cada objetivo e biotipo.
Algoritmos: Utilizar algoritmos de recomendação para personalizar os planos de treino.

7. Prompt de Resposta Proposto:
Vamos começar a criar seu plano de treino personalizado. Qual é o seu nome? 
Você se identifica mais com qual biotipo?: 
A) Ectomorfo: Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular. 
B) Mesomorfo: Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento. 
C) Endomorfo: Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.
Onde você costuma treinar?
A)	Em casa: 
•	Funcional  
•	HIIT
•	Cardio
B)	Academia:
•	Maquinário
•	Peso Livre
•	Funcional
•	HIIT
C)	Ginásios 
•	Peso Livre
•	Funcional
•	Cardio
D)	Ao ar livre 
•	HIIT
•	Cardio
•	Funcional

Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais e múltiplos grupos musculares
Maquinário: Exercícios realizados em equipamentos, focados em isolar grupos musculares específicos.
Peso Livre: Exercícios com pesos livres (halteres, barras, kettlebells) para trabalhar múltiplos grupos musculares simultaneamente
HIIT: Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.
Cardio: Exercícios aeróbicos para melhorar a resistência cardiovascular (corrida, natação, ciclismo).

Disponibilidade de Treino: 
A) 1-2 dias por semana: Treino Full Body 
B) 3-4 dias por semana: Treino ABC 
C) 5-6 dias por semana: Treino ABCDE 
Nível de Condicionamento:
A) Iniciante: Pouca ou nenhuma experiência com exercícios regulares
B) Intermediário: Pratica exercícios há alguns meses, familiarizado com técnicas básicas 
C) Avançado: Treina consistentemente há anos, bom conhecimento de técnicas e princípios de treino
Faixa Etária: 
A) 16 a 29 anos 
B) 30 a 39 anos 
C) 40 a 49 anos 
D) 50 anos ou mais
Objetivo Principal: 
A) Perda de gordura 
B) Ganho de massa muscular 
C) Melhora do condicionamento físico
D) Aumento da força 
E) Melhora da flexibilidade e mobilidade
Restrições Médicas: 
A) Nenhuma restrição conhecida 
B) Problemas articulares 
•	Joelho
•	Ombro
•	Costas 
C) Condições cardiovasculares
•	Hipertensão
•	Insuficiência cardíaca
•	Miocárdio
D) Outras 

Respostas como um usuário:
1. Biotipo:
•	Opção: B) Mesomorfo
•	Justificativa: Sempre tive facilidade em ganhar massa muscular e definir o corpo. Meus músculos respondem bem ao treinamento e consigo ver resultados relativamente rápido.
2. Onde você costuma treinar?
•	Opção: B) Academia: Maquinário, Peso Livre, Funcional, HIIT
•	Justificativa: Gosto da variedade de equipamentos e da possibilidade de realizar diferentes tipos de treino. A academia me oferece um ambiente motivador e com acompanhamento profissional, quando necessário.
3. Disponibilidade de Treino:
•	Opção: C) 5-6 dias por semana
•	Justificativa: Tenho bastante tempo disponível e gosto de treinar com frequência. Acredito que quanto mais treinar, melhores serão os resultados.
4. Nível de Condicionamento:
•	Opção: B) Intermediário
•	Justificativa: Treino regularmente há alguns anos e já conheço as técnicas básicas. Busco sempre evoluir e me desafiar com novos exercícios.
5. Faixa Etária:
•	Opção: B) 30 a 39 anos
6. Objetivo Principal:
•	Opção: B) Ganho de massa muscular
•	Justificativa: Meu objetivo principal é aumentar a massa muscular e definir o corpo.
7. Restrições Médicas:
•	Opção: A) Nenhuma restrição conhecida
•	Preferência por exercícios: Gosto muito de treinar com peso livre, pois acho que os resultados são mais eficazes e completos. No entanto, também gosto de incluir exercícios funcionais e HIIT nos meus treinos para melhorar a minha condicion física e queimar gordura.
•	Divisão de treino: Prefiro a divisão ABCDE, pois permite trabalhar cada grupo muscular de forma mais específica e com maior frequência.
•	Flexibilidade: Sou bastante flexível em relação aos horários de treino e consigo me adaptar a diferentes situações.
