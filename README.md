# Projeto 02 - Curso de Data Analytics - Ironhack

#### Objetivos do projeto

Fazer uma análise, criar visualizações e apresentação utilizando dados extraídos através de API e/ou Webscraping.

#### Tema escolhido:

Análise de demanda de Energia Elétrica para o Estado de São Paulo

#### Link da apresentação no Tableu public:

https://public.tableau.com/app/profile/nat.lia.mendes.ceoldo/viz/DAPT-Project02/AnlisedeDemandaEnergiaparaoestadodeSP

# Análise de Demanda de Energia Elétrica para o Estado de São Paulo

<img src="images\power.jpg" alt="power" style="zoom: 50%;" />

## Introdução

### 1. Objetivo

Analisar o Perfil de demanda horária de energia elétrica para o estado de São Paulo e responder às perguntas:

- Qual o horário de pico de demanda de energia elétrica?
- Qual a influência do horário de verão na demanda de energia?

### 2. Motivação

- Contexto de crise hidríca
- Revogação do horário de verão
- Discussão sobre tarifa dinâmica de energia

### 3. Período Analisado

Ano de 2016 a outubro (parcial) de 2021.

### 4. Fonte de Dados

Operadora Nacional do Sistema (ONS)

Dados obtidos através da API disponível no portal SINTEGRE:

https://sintegre.ons.org.br



## Análises

### 1. Demanda Horária por dia da semana



<div class='tableauPlaceholder' id='viz1634693205171' style='position: relative'><noscript><a href='#'><img alt='Análise de Demanda Energia para o estado de SP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;KF&#47;KFWW9WT98&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;KFWW9WT98' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;KF&#47;KFWW9WT98&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='pt-BR' /></object></div>





### 2. Demanda Horária - meses quentes VS meses frios

<div class='tableauPlaceholder' id='viz1634693318348' style='position: relative'><noscript><a href='#'><img alt='Análise de Demanda Energia para o estado de SP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FG&#47;FGZSJZYHY&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;FGZSJZYHY' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FG&#47;FGZSJZYHY&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='pt-BR' /></object></div>



### 3. Comparação com e sem horário de verão

<div class='tableauPlaceholder' id='viz1634693361740' style='position: relative'><noscript><a href='#'><img alt='Análise de Demanda Energia para o estado de SP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;7B&#47;7BKSSKKBN&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;7BKSSKKBN' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;7B&#47;7BKSSKKBN&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='pt-BR' /></object></div>



## Conclusões

### 1. Horário de Ponta

A demanda de energia elétrica tem perfil de carga mais elevado em dias úteis, o que justifica a adoção de tarifa diferenciada para o horário de ponta nesses dias.

<img src="images\Kamel.png" alt="Kamel"  /> 

Observa-se que durante os meses mais quentes  do ano existem dois momentos de pico de demanda:

- Das 14h às 16h
- Das 19h às 21h

<img src="images\Fuji.png" alt="Fuji" style="zoom: 10%" align="left" />

Enquanto que para os meses mais frios, o pico de demanda ocorre entre 19h e 21h, coincidindo com o horário de ponta já adotado pelas concessionárias

### 2. Horário de Verão

<img src="images\sun.png" alt="sun" style="zoom:100%;" /> 

As temporadas em que houve horário de verão não apresentaram apresentaram melhor distribuição ou deslocamento de carga nos períodos de pico.

O impacto observado é que houve uma antecipação da elevação de demanda no início do dia, que na referência UTC-3 seria a partir da 6h sem o horário de verão, enquanto que com a elevação de demanda iniciava a partir das 4h.



## Próximos passos

Replicar a análise para demais estados e regiões e verificar se existem diferenças no perfil de demanda, horário de ponta, influência do horário de verão, sazonalidades, etc., bem como entender o comportamento no quadro nacional.

Analisar qual seria a diferença de custo de geração de energia de acordo com a demanda/horário de geração, períodos úmidos e secos.

 <font size="1" style="text-decoration: line-through">Espremer os dados até que eles digam que o horário de verão é bom!</font>
<font size="1" style="color: orange;">#TeamHorarioDeVerao #VoltaHorarioDeVerao </font>





