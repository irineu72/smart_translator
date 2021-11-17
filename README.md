# smart_translator

Foi criado um script em ruby que faz uma chamada recursiva onde é passado um json em português e o script chama um endpoint 
https://api.cognitive.microsofttranslator.com/translate  recurso da azure, o script percorre sobre o json todo e realiza a tradução apenas do valores
de cada chave. Foi criado uma imagem no docker e pode ser utilizada por qualquer pessoa. Basta apenas criar um cadastro basico na azure e  criar
a chamada da api e assim trocar a chave do script para a chave que a api da Azure vai gerar.
