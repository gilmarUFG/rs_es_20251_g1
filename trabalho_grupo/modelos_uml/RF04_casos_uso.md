@startuml
left to right direction
skinparam packageStyle rectangle
skinparam usecase {
  BackgroundColor LightSkyBlue
  BorderColor DarkSlateGray
}

actor Médico as medico
actor Paciente as paciente

rectangle "Consulta Virtual 3D" {
  usecase "Iniciar sessão de consulta 3D" as UC1
  usecase "Navegar no ambiente virtual" as UC2
  usecase "Realizar comunicação por voz" as UC3
  usecase "Visualizar avatar do outro participante" as UC5
  usecase "Utilizar ferramentas de diagnóstico 3D" as UC6
  usecase "Finalizar consulta" as UC7

  medico --> UC1
  medico --> UC2
  medico --> UC3
  medico --> UC5
  medico --> UC6
  medico --> UC7

  paciente --> UC1
  paciente --> UC2
  paciente --> UC3
  paciente --> UC4
  paciente --> UC5
  paciente --> UC7
}
@enduml