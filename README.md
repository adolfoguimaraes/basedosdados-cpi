# Processamento de Dados da CPI 

Este notebook possui o código de processamento dos dados da CPI utilizados para construção de visualizações relacionadas ao tema. A fonte dos dados é a base de textos da CPI da Covid disponibiliza pela Base dos Dados no link: : https://basedosdados.org/dataset/br-senado-cpipandemia.

A visualização construída a partir dos dados processados pode ser acessada no link: https://observablehq.com/@adolfoguimaraes/swd-challenge-mar-22

Foram utilizadas técnicas de Processamento de Linguagem Natural para extração das informações de termos mais relevantes e entidades nomeadas. Para a extração de entidades nomeadas foi utilizado o modelo pré-treinado disponível no link: https://github.com/neuralmind-ai/portuguese-bert.

## Arquivos Gerados 

Foram gerados os seguintes arquivos: 


`output/ner_files/`: pasta dos arquivos com as entidades extraídas de cada fala dos depoentes e convidados. Cada arquivo corresponde a um depoente/convidado de um dia da CPI. 
`output/corpus_tfid.json`: arquivo com TF-IDF de cada termo/documento.
`outupt/todas_entidades_nomeadas_por_data.json`: arquivo com as entidades nomeadas para cada dia de CPI.
`output/todas_entidades_nomeadas.json`: arquivo com as entidades nomeadas de todos os dias. 
`output/vocabulary_full.json`: vocabulário de toda a base com informações da frequência do termo, quantidade e lista de documentos que o termo aparece.




