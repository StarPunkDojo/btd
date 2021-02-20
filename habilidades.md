# Habilidades de Armadura

## Armaduras Leves
```json
{
    "lv-1": [
        {
            "nome": "Rota de Fuga",
            "efeito": "+10 em Desvio",
            "duração": "1 turno",
            "custo": null
        }
    ]
}
```

## Armaduras Médias
```json
{
    "lv-1": [
        {
            "nome": "Resoluto",
            "efeito": "+10 em Perseverança",
            "duração": "2 turnos",
            "custo": null
        }
    ]
}
```
## Armaduras Pesadas
```json
{
    "lv-1": [
        {
            "nome": "Prevalecer",
            "efeito": "+10 em Resistência",
            "duração": "1 turno",
            "custo": null
        }
    ]
}
```

# Habilidades de Arma

## Armas Pesadas
### Porrete
```json
{
    "lv-1": [
        {
            "nome": "Golpe Pesado",
            "dano": "Aptidão * 1.2",
            "tipoDeDano": "Contundente",
            "custo": null
        },
        {
            "nome": "Onda de Choque",
            "efeito": "Atordoar X [X=Aptidão/10]",
            "custo": null
        }
    ]
}
```
### Espada
```json
{
    "lv-1": [
        {
            "nome": "Golpe Justo",
            "dano": "Aptidão * 1",
            "tipoDeDano": "Cortante",
            "efeito": "Avariado X [X=Aptidão/20]",
            "custo": null
        },
        {
            "nome": "Desafio",
            "efeito": "Provocado X [X=Aptidão/10]",
            "custo": null
        }
    ]
}
```
### Claymore
```json
{
    "lv-1": [
        {
            "nome": "Golpe Selvagem",
            "dano": "Aptidão * 1",
            "tipoDeDano": "Contundente",
            "custo": null,
            "multiplosAlvos": true
        },
        {
            "nome": "Aura Berserk",
            "efeito": "Aterrorizar X [X=Aptidão/20]",
            "custo": null
        }
    ]
}
```
## Armas Médias
### Katana
```json
{
    "lv-1": [
        {
            "nome": "Golpe Misericordioso",
            "dano": "Aptidão * 1",
            "tipoDeDano": "Cortante",
            "efeito": "Chance X% de OTK em inimigos mais fracos [X=Aptidão/2]",
            "custo": null
        },
        {
            "nome": "Alma Persistente",
            "efeito": "Status -X [X=Aptidão/20]",
            "custo": null
        }
    ]
}
```
### Pistolas Duplas
```json
{
    "lv-1": [
        {
            "nome": "Tiro Duplo",
            "dano": "Aptidão * 1",
            "tipoDeDano": "À Distância",
            "efeito": "Chance X% aplicar novamente o dano [X=Aptidão]",
            "custo": null
        },
        {
            "nome": "Aplicar Afinidade",
            "efeito": "Transforma o tipo de dano de acordo com a afiliação",
            "custo": null
        }
    ]
}
```
### Rifle de Precisão
```json
{
    "lv-1": [
        {
            "nome": "Tiro Preciso",
            "dano": "Aptidão * 1.1",
            "tipoDeDano": "À Distância",
            "efeito": "Chance X% de identificar fraqueza [X=Aptidão*1.5]",
            "custo": null
        },
        {
            "nome": "Carregar Afinidade",
            "efeito": "Próximo ataque de Rifle de Precisão causa o dobro de dano",
            "custo": null
        }
    ]
}
```
## Armas Leves
### Soqueiras
```json
{
    "lv-1": [
        {
            "nome": "Golpe Furioso",
            "dano": "Aptidão * Número de golpes desse turno",
            "tipoDeDano": "Contundente",
            "custo": null
        },
        {
            "nome": "Golpe Crescente",
            "dano": "Aptidão/2",
            "tipoDeDano": "Contundente",
            "efeito": "Chance X% de aplicar mais um golpe [X=Aptidão]",
            "custo": null
        },
        {
            "nome": "Disciplina",
            "passiva": "Máximo de X golpes por turno [X=Aptidão/5]",
        },
    ]
}
```
### Catalizador
```json
{
    "lv-1": [
        {
            "nome": "Golpe Sobrecarregado",
            "dano": "Aptidão",
            "tipoDeDano": "Elemental",
            "efeito": "Também danifica o Fluxo do alvo",
            "custo": null
        },
        {
            "nome": "Conhecimento Antigo",
            "efeito": "Próxima Habilidade tem custo de Fluxo reduzido pela metade",
            "custo": null
        },
        {
            "nome": "Curiosidade",
            "passiva": "Fluxo +X [X=Afinidade]",
        },
    ]
}
```
### Adaga
```json
{
    "lv-1": [
        {
            "nome": "Golpe Furtivo",
            "dano": "Aptidão",
            "tipoDeDano": "Cortante",
            "efeito": "Triplo de dano caso esteja camuflado",
            "custo": null
        },
        {
            "nome": "Desaparecer",
            "efeito": "Camuflado X [X=Aptidão/10]",
            "custo": null
        }
    ]
}
```
# Habilidades de Afiliações
## Afiliação em Akari
```json
{
    "lv-1": [
        {
            "nome": "Brilho de Akari",
            "dano": "Afinidade + Resistência",
            "tipoDeDano": "Fogo",
            "efeito": [
                "Causa Chamuscar", 
                "Dobro de dano caso o alvo esteja Chamuscado"
                ],
            "custo": 30
        },
        {
            "nome": "A Chama Interior",
            "passiva": "Causa mais X% de dano para cada X% de vida faltante",
        }
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "Eu sou meu próprio Sol!",
            "passiva": "Causa mais X% de dano para cada X% de vida faltante para cada aliado"
        },
        {
            "nome": "Desprezo ao Fogo",
            "passiva": "Imune a Fogo",
        }
    ]
}
```
## Afiliação em Leora
```json
{
    "lv-1": [
        {
            "nome": "Luz de Leora",
            "dano": "Afinidade + Percepção",
            "tipoDeDano": "Luz",
            "efeito": "Causa Ofuscar",
            "custo": 30
        },
        {
            "nome": "Punir",
            "efeito": "Causa Avariar X [X=(Afinidade + Percepção)/10]",
            "custo": 30
        },
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "A Luz me traiu!",
            "passiva": "Habilidades que causam Atordoar artodoam todos os inimigos"
        },
        {
            "nome": "Desprezo a Luz",
            "passiva": "Imune a Luz",
        }
    ]
}
```
## Afiliação em Dyllana
```json
{
    "lv-1": [
        {
            "nome": "Vontate de Dyllana",
            "dano": "Afinidade + Perseverança",
            "tipoDeDano": "Água",
            "efeito": "Causa 4x mais dano na lua cheia",
            "custo": 30
        },
        {
            "nome": "Revitalizar",
            "efeito": "Cura X% da vida máxima do aliado [X=(Afinidade + Percepção)/10]",
            "custo": 30
        },
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "Não há mais mistérios para mim!",
            "passiva": "Descubra um ponto forte ou fraco aleatório do inimigo"
        },
        {
            "nome": "Desprezo a Água",
            "passiva": "Imune a Água",
        }
    ]
}
```
## Afiliação em Darcell
```json
{
    "lv-1": [
        {
            "nome": "Amor de Darcell",
            "efeito": "Condece Camuflagem X [X=Afinidade + Desvio/10]",
            "custo": 30
        },
        {
            "nome": "Refúgio",
            "passiva": "Quanto não é o único combatente alidado, só será alvejado após o primeiro ataque"
        },
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "Ninguém escapa da própria Sombra!",
            "efeito": "Habilidades Regulares tem 50% de chance de causarem Camuflagem 1",
            "duração": "2 turnos",
            "custo": 2
        },
        {
            "nome": "Desprezo as Sombras",
            "passiva": "Imune a Sombra",
        }
    ]
}
```

## Afiliação em Viora
```json
{
    "lv-1": [
        {
            "nome": "Harmonia de Viora",
            "efeito": "Muda a ordem de ataque dos inimigos ou aliados",
            "custo": 30
        },
        {
            "nome": "Ressonância",
            "dano": "Afinidade * 1",
            "tipoDeDano": "Som",
            "efeito": "Escolha um aliado, aplique essa habilidade toda a vez que ele atacar",
            "duração": "3 turnos"
        },
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "Silencio!",
            "efeito": "Silencie o inimigo",
            "duração": "2 turnos",
            "custo": 3
        },
        {
            "nome": "Desprezo ao Som",
            "passiva": "Imune ao Som",
        }
    ]
}
```
## Afiliação em Fai Mei
```json
{
    "lv-1": [
        {
            "nome": "Cria de Fai Mei",
            "dano": "Afinidade * 1",
            "tipoDeDano": "Corte",
            "efeito": "Cria um Golem Metálico imune a ataques físicos (Limite de apenas 1)",
            "custo": 30
        },
        {
            "nome": "Projetar: Fronteira",
            "efeito": "Cria uma barreira entre seus aliados e o inimigos que deve ser destruida",
            "durabilidade": "Afinidade + Resistência"
        },
    ]
}
```
### Decair
```json
{
    "lv-1": [
        {
            "nome": "Eu sou imortal... Eu sou invecível!",
            "passiva": "Imune a ataques cortantes ou à distancia"
        },
        {
            "nome": "Desprezo ao Metal",
            "passiva": "Imune ao Metal",
        }
    ]
}
```