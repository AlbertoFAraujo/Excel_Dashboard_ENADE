![fundo](https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/38711a77-0076-4d26-8a5e-bb9bb9a3fb34)

# 1. DASHBOARD ENADE 2021

#### GITHUB: ####
[https://github.com/AlbertoFAraujo/DashEnade2021](https://github.com/AlbertoFAraujo/DashEnade2021)

**Objetivo:** 

Analisar os Indicadores de Qualidade do Ensino Superior (ENADE 2021) entre as modalidade de ensino "EAD" e "Presencial" com base nos dados públicos oferecidos pelo portal gov.br.

[https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/indicadores-educacionais](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/indicadores-educacionais)

## Etapas do projeto: ##

1. Definição do objetivo da análise e coleta dos dados públicos;
2. Tratamento dos dados (Limpeza, transformações, formatações, criação de tabelas dinâmicas, auxiliares e filtros-chave);
3. Identificação das métricas-alvo e escolha das visualizações gráficas adequadas para cada cenário;
4. Criação do layout e composição de paleta de cores;
5. Teste de qualidade e eficácia do dashboard (garantir que todos os gráficos estejam funcionando corretamente e que os dados estejam sendo atualizados)

## Tempo de Execução: ##

O tempo estimado para a execução de todas as etapas é de 1 dia.

## Projeto Final a ser desenvolvido: ##

![Dash_ENADE_2021](https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/2f47800e-6968-461c-93e9-6472da0e0b99)

## Execução das Etapas ##

### 1. Definição do objetivo da análise e coleta dos dados públicos: ###

O objetivo da análise é garantir a comparação da qualidade de ensino entre as modalidades EAD (distância) e Presencial de forma nacional ou estadual. A ideia é apresentar o nível de comparação entre as modalidades,        sendo correlacionadas à outros parâmetros, tais como, grau acadêmico, categoria acadêmica, cursos classificados com a maior nota e classificação geral por faixa do ENADE.

### 2. Tratamento dos dados (Limpeza, transformações, formatações, criação de tabelas dinâmicas, auxiliares e filtros-chave): ###
- Foi realizado a limpeza dos dados que não constava indicação de nota do ENADE, visto que, o número de dados NULL não influenciará na comparação entre as duas modalidades;
- Houve necessidade de abreviar alguns dados da variável “Área” e “Categoria Administrativa”, devido o comprimento dos caracteres não sendo viável na exibição dos gráficos;
- Os campos foram formatados conforme a disposição do tipo de dados “Texto e numéricos”;
- Foi criado todas as tabelas dinâmicas na qual serão utilizadas como base para nosso dashboard. No entanto, não utilizarei os gráficos dinâmicos (basta criar um gráfico sem dados e selecionar manualmente as informações pertinentes, visto que em uma única tabela dinâmica vou extrair dois gráficos conforme as modalidades “EAD” e “Presencial”).
### 3. Identificação das métricas-alvo e escolha das visualizações gráficas adequadas para cada cenário: ###

Os gráficos foram escolhidos conforme a disposição dos dados das variáveis e que melhor atendem ao objetivo e visualização das informações;

### 4. Criação do layout e composição de paleta de cores: ###

O layout foi pensando na disposição das informações, como a ideia é apresentar a comparação entre as modalidades “EAD” e “Presencial”, criei uma divisão no layout principal de forma espelhada, assim o usuário final poderá observar em paralelo as duas informações e compará-las;

As paletas de cores foram baseadas na logomarca do ENADE:

| RGB (35, 79, 140) | RGB (251, 202, 0) |
|-------------------|-------------------|
| ![paletaAzul](https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/17ba115a-a274-44c5-bf67-2f04fada58c8) | ![paletaAmarela](https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/f9361980-577e-437d-a5a4-0325830d4b11) |

### 5. Teste de qualidade e eficácia do dashboard (garantir que todos os gráficos estejam funcionando corretamente e que os dados estejam sendo atualizados): ###

Foi realizado diversos testes de filtros e foram identificadas alguns inconsistências como rótulos acumulados ou em cima de legendas no gráfico de radar (”Qtd. Categ. Acadêmica”), sendo necessário criar caixas de texto para contornar o problema, visto que as legendas estão em posições fixas do gráfico.

## Resultado final

https://github.com/AlbertoFAraujo/DashEnade2021/assets/105552990/71fb9c4c-df9c-4eea-93b7-db38f6047d47
