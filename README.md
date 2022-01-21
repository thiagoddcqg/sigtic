# SIGTIC
Repositório oficial do Sistema Integrado de Gestão de Tecnologia da Informação e Comunicação (SIGTIC).

Usa-se de bibliotecas python (pdfminer, NLTK, spaCy) para analisar arquivos PDF de revistas científicas e extrair palavras-chave específicas como: taxonomia, nsc (identificador único), autores, nome composto. Usado para auxiliar na extração de informações pertinentes de artigos de periódicos e inserir em planilhas. Um voto de classe ensemble foi usado para classificar palavras-chave com base no conjunto de treinamento (`taxon_names.csv`)

## Informações
Existem três arquivos `.ipynb` separados. O arquivo com extensão `_ML` foi escrito pelo colega usando o método TFID (não implementado, mas mantido para referência). O arquivo com extensão `_short_version` foi usado para apresentação. O arquivo sem extensão é a versão original. Os modelos devem ser compilados no notebook jupyter, pois o tamanho do arquivo era muito grande para ser incluído no repositório. Existe uma função para selecionar o modelo e salvá-lo na máquina local para acelerar as execuções subsequentes.