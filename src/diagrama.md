classDiagram
class Animal {
+fazerSom() void
}

    class Cachorro {
        +fazerSom() void
    }

    class Gato {
        +fazerSom() void
    }

    class Main {
        +main(String[] args) void
    }

    Animal <|-- Cachorro
    Animal <|-- Gato
    Main --> Animal : usa
