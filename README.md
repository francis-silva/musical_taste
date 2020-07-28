
# Observações importantes:
i)   O arquivo original "lyrics-data.csv" que contém as letras musicais não está presente neste repositório pelo fato de muito grande (>200MB), em substituição está o arquivo já tratado "lyrics_archive_filtered.csv" que justamente contém os dados de interesse;<br />
<br />
ii)  A tabela no banco de dados somente é criada após a execução do script objetivando permitir ao examinador o teste da correta execução, contudo uma vez criada e novamente o script executado esta não será recriada;<br />
<br />
iii) Foram idenficados registros duplicados no arquivo "lyrics-data.csv" para a banda "AC/DC", portanto, para garantia de que não serão ofertadas ao cliente letras musicais em duplicidade, somente são inseridos registros exclusivos;<br />
<br />
iv)  O Jupyter Notebook para teste do script faz a função de ETL através das funções: filter_csv(), create_table(), insert_data() e analítica através das funções: top3_genres_brasil() e mais_do_mesmo();<br />
<br />
v)   O banco de dados está presente no repositório.
