# GS2 - Pensamento Computacional e Automação com Python

## 👥 Desenvolvedores
- Caio Castelão Carminato - RM563630  
- Guilherme Vasques Tamai - RM563276  
- Vitor Komura de Freitas - RM563694

## 📌 Descrição do Projeto e Propósito 

O projeto é um Sistema Inteligente de Orientação de Carreira desenvolvido em Python usando Programação Orientada a Objetos.
Ele avalia competências técnicas e comportamentais do usuário (como Python, lógica, colaboração, redes etc.) e compara com as exigências de diferentes carreiras.

Com base nisso, o sistema:

calcula nota de compatibilidade com cada carreira, identifica lacunas de habilidades (gaps), sugere trilhas de aprendizado, gera automaticamente um relatório .txt com as recomendações.

O objetivo é conectar programação e automação ao desenvolvimento humano, ajudando pessoas a se prepararem para o trabalho do futuro.

A proposta consiste em uma simulação de automação IoT voltada para o monitoramento de consumo energético, utilizando um ESP32 virtual e display LCD.

A solução demonstra como tecnologias embarcadas podem ser aplicadas para tornar ambientes de trabalho mais eficientes e sustentáveis. Ao acompanhar em tempo real os dados de tensão, corrente e potência, é possível identificar padrões de consumo, propor ajustes e contribuir para práticas mais conscientes no uso da energia elétrica.

## ▶️ Instruções de Execução

Use o menu:

1 → cadastrar perfil e notas das competências

2 → gerar recomendações e relatório

3 → sair

O relatório será salvo automaticamente em um arquivo .txt.

## 🧩 Estrutura de Arquivos e Classes

Principais classes:

Competency — representa uma competência individual.

Profile — guarda nome do usuário e suas competências.

Career — define cada carreira, seus pesos e níveis esperados.

Recommender — faz os cálculos: nota, gaps e sugestões.

Funções importantes:

example_data() — cria as carreiras disponíveis.

cadastrar_perfil() — coleta dados do usuário.

exibir_recomendacoes() — mostra resultados e cria relatório.

salvar_relatorio() — grava as recomendações em um arquivo .txt.

main() — controla o fluxo geral do sistema.


<img width="767" height="337" alt="image" src="https://github.com/user-attachments/assets/25328433-a9d3-4d58-be3f-c4a715652c38" />



