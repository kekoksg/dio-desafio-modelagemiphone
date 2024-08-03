### Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        + tocar(): void
        + pausar(): void
        + selecionarMusica(musica: String): void
    }

    class AparelhoTelefonico {
        + ligar(numero: String): void
        + atender(): void
        + iniciarCorreioVoz(): void
    }

    class NavegadorInternet {
        + exibirPagina(url: String): void
        + adicionarNovaAba(): void
    }

    class iPhone {
        - reprodutorMusical: Reprodutor Musical
        - aparelhoTelefonico: Aparelho Telefônico
        - navegadorInternet: Navegador na Internet
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```
