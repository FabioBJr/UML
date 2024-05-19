```mermaid
classDiagram
    class iPhone{ 
    }
    
    iPhone --> ReprodutorMusical 
    iPhone --> AparelelhoTelefonico
    iPhone --> NavegadorInternet

    class ReprodutorMusical {
    +tocar()
    +pausar()
    +selecionarMusica(String musica)
    }

    class AparelelhoTelefonico { 
    +ligar(String numero)
    +atender()
    +iniciarCorreioVoz()
    }

    class NavegadorInternet {
    +exibirPagina(String url)
    +adicionarNovaAba()
    +atualizarPagina()
    }
```

