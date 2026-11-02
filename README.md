# Vale.-2026.1
Projeto Integrador UNIFEI + Vale S.A. — 2026.1

1. Contexto e objetivo do projeto
O projeto consistiu no desenvolvimento de um sistema eletrônico de alerta de proximidade para operadores de pontes rolantes, inspirado em situações de risco na movimentação de cargas e equipamentos industriais.

A proposta surgiu no contexto do Projeto Integrador do curso de Bacharelado em Ciência e Tecnologia da Universidade Federal de Itajubá (UNIFEI), com foco em uma aplicação para a realidade operacional da Vale S.A., em Itabira, Minas Gerais.

O principal objetivo era desenvolver um protótipo capaz de:
- Detectar a aproximação de obstáculos utilizando sensores ultrassônicos.
- Emitir alertas sonoros e visuais quando um objeto atingisse uma distância de risco.
- Aumentar a frequência dos alertas sonoros conforme a distância diminuísse.
- Transmitir sinais de alerta por radiofrequência para um receptor.
- Demonstrar uma possível solução de apoio à segurança de operadores em ambientes industriais.
Importante: tratava-se de um protótipo acadêmico demonstrativo, não de um sistema de segurança industrial homologado ou colocado em operação pela Vale.
2. Componentes e tecnologias utilizadas
Componente ou ferramenta	Função no projeto
Arduino Uno	Processamento das leituras e controle dos alertas
2 sensores HC-SR04	Medição ultrassônica da distância de obstáculos em lados opostos
Buzzer	Emissão dos alertas sonoros
LED	Sinalização visual da detecção
Módulos RF 433 MHz	Transmissão e recepção de sinais de alerta
Bateria	Alimentação elétrica do protótipo
Linguagem C (Arduino)	Programação do microcontrolador
Python	Desenvolvimento de scripts auxiliares
Autodesk Fusion 360	Modelagem tridimensional da caixa de proteção
Scrum	Organização das atividades da equipe

O projeto também envolveu conhecimentos de circuitos eletrônicos, integração entre hardware e software, modelagem 3D e preparação de modelos para impressão 3D.
<img width="818" height="466" alt="image" src="https://github.com/user-attachments/assets/3dab670f-dded-45f9-8852-2fde1fed992c" />
# Sistema de Alerta de Proximidade para Pontes Rolantes

**Projeto Integrador — UNIFEI | 2026.1**

**Instituição:** Universidade Federal de Itajubá (UNIFEI), Campus Itabira  
**Curso:** Bacharelado em Ciência e Tecnologia (BCTec)  
**Contexto:** Projeto acadêmico apresentado a profissionais da Vale S.A.

## Objetivo

Desenvolver um protótipo eletrônico de alerta de proximidade com aplicação proposta para operações de pontes rolantes, visando auxiliar na identificação de obstáculos próximos e contribuir para a prevenção de situações de risco durante a movimentação de cargas industriais.

## Desenvolvimento

O projeto foi desenvolvido por uma equipe de cinco integrantes, com organização das atividades utilizando a metodologia Scrum.

A solução utilizou um microcontrolador Arduino Uno, dois sensores ultrassônicos HC-SR04 posicionados em lados opostos, buzzer, LED e módulos de comunicação por radiofrequência de 433 MHz.

O sistema foi programado em C para monitorar a distância de objetos e acionar alertas sonoros e visuais quando a aproximação atingisse 20 centímetros. A frequência de repetição dos sinais sonoros aumentava conforme a distância diminuía.

Também foi implementada a comunicação por radiofrequência para transmitir sinais de alerta a um receptor separado do dispositivo de detecção.

O desenvolvimento incluiu a montagem dos circuitos eletrônicos, criação de scripts auxiliares em Python e modelagem tridimensional de uma caixa de proteção utilizando Autodesk Fusion 360.

Para demonstrar o funcionamento, foi utilizado um protótipo físico com carrinho de quatro rodas, permitindo reproduzir situações de aproximação de obstáculos.

## Testes e validação

Durante o desenvolvimento, foram realizados mais de 30 testes e ajustes para identificar e corrigir problemas relacionados às leituras ultrassônicas e à integração dos componentes.

A comunicação por rádio apresentou limitações de alcance e estabilidade nas condições testadas, sendo mais confiável em curtas distâncias.

Após os ajustes, foram realizadas cinco verificações adicionais com funcionamento satisfatório do protótipo.

## Participação individual

Minha contribuição envolveu a programação do Arduino em C, montagem dos circuitos, elaboração de scripts em Python, modelagem da caixa no Fusion 360 e participação nos testes e ajustes.

Também contribuí para a organização do trabalho, resolução de dificuldades técnicas e preparação da apresentação final.

## Apresentação e resultados

O projeto foi demonstrado presencialmente na UNIFEI, com apoio de vídeos e material em PowerPoint, para profissionais da Vale S.A.

O protótipo demonstrou a possibilidade de integrar sensores ultrassônicos, sinalização sonora e visual e comunicação sem fio em uma solução de alerta de proximidade.

O equipamento permaneceu na universidade para eventual avaliação posterior. Os testes foram realizados em ambiente acadêmico, sem implantação ou validação operacional nas instalações da Vale.

O projeto proporcionou experiência prática em programação embarcada, eletrônica, prototipagem, modelagem 3D, integração de sistemas e resolução de problemas em equipe.







