# Estrutura de nós da Godot

- Na Godot tudo é um nó
- Basta estender as classes preexistentes
- Herança + composição
- Ordenação é relevante
- Callbacks / Event Handlers
  - _ready: quando o nó entra na Scene
  - _process: todo frame (gráficos)
  - _physics_process: com intervalos de tempo constante -> consistente (física)
  - _on_something
