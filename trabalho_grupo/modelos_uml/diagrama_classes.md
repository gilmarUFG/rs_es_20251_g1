@startuml
abstract class Usuario {
  - id: Integer
  - nome: String
  - email: String
  - senha: String
  - perfil: String
}

class Medico {
  - crm: String
  - especialidade: String
}

class Paciente {
  -- 
}

class Consulta {
  - id: Integer
  - dataHora: DateTime
  - status: String
}

class DocumentoMedico {
  - id: Integer
  - tipo: String
  - arquivo: String
}

class Ambiente3D {
  - id: Integer
  - descricao: String
}

class AnotacaoMedica {
  - id: Integer
  - texto: String
  - dataHora: DateTime
}

class Mensagem {
  - id: Integer
  - texto: String
  - dataHora: DateTime
}

Usuario <|-- Medico
Usuario <|-- Paciente

Medico "1" -- "0..*" Consulta : realiza >
Paciente "1" -- "0..*" Consulta : participa >
Consulta "1" -- "1" Ambiente3D : possui >
Paciente "1" -- "0..*" DocumentoMedico : envia >
Consulta "1" -- "0..*" AnotacaoMedica : possui >
Consulta "1" -- "0..*" Mensagem : possui >
@enduml