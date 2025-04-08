Exemplo de Implementações para o primeiro Iphone em UML (DIO ATIVIDADE)

```mermaid
classDiagram
    class iPhone {
    }

 class ReprodutorMusical {
	    Tocar()
	    Pausar()
	    SelecionarMusica(String musica)
    }

class AparelhoTelefonico {
	    Ligar(String numero)
	    atender()
	    iniciarCorreioDeVoz()
    }

class NavegadorInternet {
	    exibirPagina(String url)
	    adicionarNovaAba()
	    atualizarPagina()
    }

iPhone --> ReprodutorMusical
iPhone --> AparelhoTelefonico
iPhone --> NavegadorInternet
```
