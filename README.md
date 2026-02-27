# 🤖 Simulador Inteligente de Entrevistas de Carreira Tech

Este projeto foi desenvolvido como parte de um desafio prático na **DIO (Digital Innovation One)**. O objetivo é criar um assistente de IA especializado em recrutamento e orientação de carreira para novos talentos na área de tecnologia.

## 🎯 Objetivo do Projeto

O simulador utiliza técnicas avançadas de **Prompt Engineering** para conduzir uma entrevista estruturada em fases. Ele identifica o perfil do candidato, analisa suas motivações e sugere as três carreiras mais compatíveis com base em uma matriz de decisão interna.

## 📋 Estrutura do Prompt

O prompt foi desenhado seguindo as melhores práticas de design de instrução:

1.  **Definição de Persona:** Um entrevistador especializado com tom profissional e acolhedor.
2.  **Fase de Coleta (7 Perguntas):** Perguntas sequenciais para evitar sobrecarga cognitiva do usuário.
3.  **Lógica de Análise:** Uma matriz de pontuação (0 a 20) que avalia afinidade, demanda de mercado e tempo de ramp-up.
4.  **Handoff de Agente:** Preparação dos dados para a transferência para um segundo agente (Especialista em Plano de Estudos).

## 🚀 Como Utilizar

1.  Copie o conteúdo do arquivo `prompt.md` (ou o texto abaixo).
2.  Cole em uma ferramenta de IA generativa (como ChatGPT, Gemini ou Claude).
3.  Responda às 7 perguntas sequencialmente para receber o seu diagnóstico de carreira.

## ⚙️ Regras de Negócio Implementadas

- [x] **Single-turn interaction:** A IA faz apenas uma pergunta por vez.
- [x] **Matriz de Decisão:** Avaliação técnica interna para ranqueamento de carreiras.
- [x] **Formatação Estruturada:** Uso de emojis e divisores visuais para facilitar a leitura.
- [x] **Proteção de Dados:** O agente evita citar salários específicos, focando em tendências de mercado.

## 🛠️ Tecnologias Utilizadas

- **IA Generativa** (LLMs)
- **Markdown** para documentação
- **Prompt Engineering** (Few-shot, Chain of Thought)

---
Finalizado por [anatechon/GitHub] para a comunidade DIO.
