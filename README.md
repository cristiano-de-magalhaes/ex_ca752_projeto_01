# ex_ca752_projeto_01

O dataset inclui revisões de livros (0 a 10) feitas por vários usuários. Há catorze atributos e 131.179 linhas de dados. Os atributos são os seguintes:

--:|:---
'user_id' 				    | Identificador do usuário (numérico)
'age',					      | Idade do usuário
'isbn' 					      | Identificador do livro
'rating'				      | Classificação do livro dado pelo usuário (0 a 10)
'book_title'			    | Título do livro em inglês,
'book_author'	    		| Nome do autor do livro
'year_of_publication'	| Ano de publicação do livro
'publisher'				    | Editora
'img_l'				      	| Link para imagem de capa do livro
'Language'				    | Idioma no qual foi escrito o livro
'Category'				    | Tipo de livro, observe que um livro pode pertencer a mais de um tipo (string)
'city'					      | Cidade do usuário (identificado por user_id)
'state'					      | Estado do usuário
'country'				      | País do usuário

Observe que há dois arquivos de dados (dados_treinamento.csv, dados_teste.csv), com mesmo formato, que devem ser usados no treinamento e teste dos modelos, respectivamente. Não utilize os dados de teste para ajuste de hiperparâmetros, faça isto usando apenas os dados de treinamento. Você pode dividi-los em treinamento e validação, ou fazer validação cruzada (cross validation).
