## Diagrama de Classes
1. Enums estão soltas no limbo, não estão associadas a nenhuma Classes
2. Classes possuem atributo id, isso não existe no modelo de análise.
3. Existe a classe usuario, mas não tem uma HU para cadastrá-lo.
4. Classe Paciente não tem nenhum atributo.
5. Está criando atributos de associação nas classes, isso não deve ser feito. É implícito pela associação.
6. Na classe Documento existem dois atributos relacionados a outro objeto (Autenticador), não deveriam estar aí.
7. Não existe a classe ou EnumPerfilUsuario.
8. Não existe a classe agendamento, citada no arquivo "h02_01.md".
9. Vários objetos faltantes para atendimento da HU descrita no arquivo "h09_02.md"
