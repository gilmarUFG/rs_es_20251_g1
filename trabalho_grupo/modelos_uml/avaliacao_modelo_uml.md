## Diagrama de Classes
1. Enums estão soltas no limbo, não estão associadas a nenhuma Classes
2. Classes possuem atributo id, isso não existe no modelo de análise.
3. Existe a classe usuario, mas não tem uma HU para cadastrá-lo.
4. Classe Paciente não tem nenhum atributo.
5. Está criando atributos de associação nas classes, isso não deve ser feito. É implícito pela associação.
6. Na classe Documento existem dois atributos relacionados a outro objeto (Autenticador), não deveriam estar aí.
