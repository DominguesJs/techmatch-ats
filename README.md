# TechMatch ATS 🚀

> Uma aplicação web inteligente que analisa currículos frente à descrição de vagas de tecnologia, calcula a compatibilidade com sistemas ATS (Application Tracking System) e gera uma versão otimizada com foco em ética profissional.

---

## 💡 1. Qual problema a aplicação resolve?
Muitos profissionais qualificados são eliminados de processos seletivos antes mesmo de um recrutador humano ler seus currículos, devido a filtros automatizados (ATS). O **TechMatch ATS** resolve essa barreira ao comparar os termos exigidos pela vaga com o currículo do candidato, identificando lacunas de palavras-chave e reestruturando o conteúdo para uma leitura limpa pelos robôs de RH, **sem inventar experiências que o candidato não possui**.

---

## 📝 2. O Mega Prompt Utilizado e Evolução

### O Mega Prompt inicial colado no Lovable:

Crie uma aplicação web moderna chamada "TechMatch ATS" voltada para otimizar currículos para vagas de tecnologia. A aplicação deve ser construída com React, Tailwind CSS e ícones do Lucide React, seguindo um design system limpo (estilo Shadcn/ui) com fundo cinza claro, botões em azul índigo e indicadores visuais de status (verde, amarelo, vermelho).

A aplicação deve conter as seguintes telas e funcionalidades em uma única página (Single Page Application):

1. **Cabeçalho (Header):**
   - Título: "TechMatch ATS 🚀"
   - Subtítulo: "Otimize seu currículo para passar pelos filtros automáticos de RH (ATS) sem inventar experiências."
   - Banner de Aviso Ético (destacado): "Aviso Importante: Este app melhora a apresentação e o ranqueamento das suas competências reais, mas nunca inventa experiências que você não possui."

2. **Área de Entrada (Split Screen):**
   - **Coluna Esquerda:** Um campo de texto (`textarea`) para colar a "Descrição da Vaga" (com um botão opcional "Carregar Exemplo de Vaga Tech").
   - **Coluna Direita:** Um campo de texto (`textarea`) para colar o "Seu Currículo Atual" (com um botão opcional "Carregar Exemplo de Currículo").
   - **Botão Central de Ação:** Um botão grande e destacado "Analisar Compatibilidade ATS" com ícone de inteligência artificial.

3. **Dashboard de Resultados (Aparece após a análise):**
   - **Indicador de Match:** Um círculo ou barra mostrando a porcentagem de compatibilidade (ex: 78%).
   - **Painel de Palavras-Chave:**
     - Seção de "Keywords Encontradas" (Badges verdes com tecnologias como React, TypeScript, Git).
     - Seção de "Keywords Ausentes" (Badges vermelhas ou âmbar com termos exigidos que faltam no currículo).
   - **Dicas de Estrutura ATS:** Lista rápida de recomendações de formatação (ex: evitar colunas duplas, usar fontes padrão).

4. **Gerador de Currículo Otimizado:**
   - Exibe em uma caixa de código/texto o currículo reestruturado com foco em termos ATS.
   - Botões de Ação: "Copiar Currículo em Markdown" e "Simular Exportação PDF".
   - Botão para "Salvar no Histórico" (salvando na sessão do navegador).

### O que mudou da primeira versão para a final:
* **Aviso de Ética Destacado:** Adicionado um banner fixo no topo reforçando que o sistema otimiza a linguagem, mas preserva a veracidade profissional.
* **Feedback Visual de Cópia:** Inclusão de alerta visual (*toast*) ao copiar o currículo otimizado para a área de transferência.
* **Responsividade:** Ajustes finos no layout em grid para empilhamento fluido em dispositivos móveis.

---

## 🔄 3. Como a Análise Funciona (Da vaga até o currículo ajustado)
1. **Ingestão:** O usuário cola os textos crus da vaga e do seu currículo atual nas respectivas áreas da tela.
2. **Processamento e Matching:** O script tokeniza os textos e cruza as palavras-chave técnicas (ex: React, Docker, SQL, AWS).
3. **Cálculo da Métrica:** 
   $$\text{Match (\%)} = \left( \frac{\text{Keywords Encontradas}}{\text{Keywords Exigidas na Vaga}} \right) \times 100$$
4. **Transformação Estrutural:** O currículo é reorganizado em formato linear puro, ideal para leitores ATS, acompanhado de recomendações e do alerta ético obrigatório.

---

## 🌐 4. Endereço da Aplicação Publicada
Acesse a aplicação em funcionamento: [🔗 Clique aqui para abrir o TechMatch ATS no ar](https://jobmatch-ats.lovable.app/)


<img width="1333" height="639" alt="image" src="https://github.com/user-attachments/assets/ce0e1d22-f703-4055-adca-2c27dd6dca1b" />




---
*Projeto prático desenvolvido como parte do desafio da DIO.*
