# Agente de ranking - Processos seletivos

Projeto de demonstração. Todos os candidatos e dados são fictícios.
Tempos em cenário simulado. A IA apoia e a decisão final é sempre humana.

## Objetivo
Comparar candidatos por critérios claros e gerar uma justificativa curta
para a posição de cada um, pronta para enviar ao gestor.

## O que foi feito
1. Planilha com notas de 0 a 10 (etapas, experiência, cultura) e pesos ajustáveis.
2. Nota final e ranking calculados por fórmula.
3. Fluxo no Make com dois agentes (Gemini): um redige a justificativa e
   outro revisa, removendo frases vagas e afirmações sem base nos dados.
4. A justificativa volta para a planilha, que pode ser enviada em PDF.

## Ferramentas
Make · Google Planilhas · Gemini (Google AI Studio)

## Resultado (cenário simulado)
- À mão (estimativa): 15 minutos por candidato
- Com o fluxo: 1 minuto para rodar, para todos os candidatos
- Em uma rodada de 8 candidatos: cerca de 2 horas contra 1 minuto

## Limites
Dados fictícios. A leitura e a revisão humana dos textos continuam necessárias.
