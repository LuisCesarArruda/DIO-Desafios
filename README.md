```mermaid
classDiagram
    Iphone <|-- ReprodutorMusical
    Iphone <|-- AparelhoTelefonico
    Iphone <|-- NavegadorInternet
    
    Iphone
    class ReprodutorMusical{
        -String musica
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }
    class AparelhoTelefonico{
        +int Numero
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }
    class NavegadorInternet{
        +String URL
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }
