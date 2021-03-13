# Atributos

## Viabilizadores
Atributos viabilizadores sãoo utilizados para performar ações ou aplicar efeitos de maneira proativa.
### Aptidão
### Afinidade
### Carisma
### Precisão 
## Defensivos
### Evasão
### Perseverança
### Resistência
<br />

# Ações
## Nível de Desafio
```
caso (atributo do atacante / atributo do defensor):
    >=2: Acerto
    >1: Desafio Favorável
    <=1: Desafio Desfavorável
```
```
desafio = 0.5 * (atributo do atacante / atributo do defensor)
se d100 <= desafio então:
    Acerto
senão:
    Falha
```

| Ação        | Atributo Atacante           | Atributo Defensor  |
| ------------- |:-------------:| -----:|
| Acerto      | Precisão | Evasão |
| Inflingir Efeito      | Atributo Viabilizador      |   Perseverança |
<br />

# Recebendo Dano
- O ataque é conectado com sucesso
- São calculados os efeitos
- Caso tenha fraqueza ao tipo do dano, o dano total é dobrado
- O dano é reduzido em X% onde X é a Resistência

# Tipos de Dano
## Dano Físico
- Perfurante
- Cortante
- Contundente
## Elemental
- Fogo
- Água
- Gelo
- Luz
- Sombra

# Efeitos
Efeitos tão condições impostas em personagens ou terrenos que, geralmente, alteram seus atributos. Eles podem ser causados pelas mais diversas fontes narrativas, quanto mais complexa a ação for, **mais efeitos podem tentar ser aplicados**. 

- Efeitos do mesmo tipo **não são acumulativos**, a não ser que dito **explicitamente** 
- Efeitos tem duração de **três turnos** por padrão.
- Efeitos podem ser do tipo **Afligir** quando afetam negativamente o alvo, **Conceder** quando afetam positivamente ou **Tático** quando afetam o campo de batalha.

- Mesmo não tendo um nome explicito de efeito, **jogadores podem usar atributos Viabilizadores para aplicar efeitos genéricos** através de suas ações (Ao fazer um discurso antes da batalha, por exemplo) para aplicar um modificador de 10% em um atributo de sua escolha.

## Maximizando o uso de Efeitos
Quando um alvo é afligido por mais de um efeito, o próximo atuante que aplicar um efeito com sucesso poderá optar por consumir todos os efeitos do alvo para realizar um tipo de ação especial com base no número de efeitos removidos desta forma. São eles:

- **Trinca (3):** O efeito aplicado é triplicado
- **Quadra (4):** Pode executar uma ação extra
- **Ace (5):** O alvo passa o próximo turno

Quando um **jogador** é infligido por um determinado número de efeitos, o próximo efeito a ser aplicado com sucesso cria uma **janela de oportunidade para ações de aliados**:
- **Trinca(3):** Um aliado pode aplicar um efeito no jogador
- **Quadra(4):** Um aliado pode receber o efeito no lugar do jogador
- **Ace(5):** Um aliado pode retaliar o ataque feito no jogador   

## Efeitos Comuns
### Quebrado
- -10% Resistência 
- -10% Perseverança
- **Usado naturalmente por**: Armas contundentes
### Dilacerado
- -10% Evasão 
- -10% Precisão 
- **Usado naturalmente por**: Armas cortantes
### Exposto
- recebe +10% de todas as fontes de dano
- **Usado naturalmente por**: Armas perfurantes


# Afiliações
## Afiliação em **Akari**
### Passiva: **Fervor**
- 50% de dano caso esteja com vida abaixo de 50%
### Efeito: Afligir **Chamuscado**
- O alvo recebe fraqueza contra Fogo
### Efeito: Conceder **Inspirado**
- O alvo recebe +20% Perseverança

## Afiliação em **Leora**
### Passiva: **Governado pelo Sol**
- +20% em todos os atributos quando de dia 
### Efeito: Conceder **Clareza**
- O alvo recebe +20% Precisão
### Efeito: Afligir **Iluminado**
- O alvo recebe -20% de Evasão

## Afiliação em **Dyllana**
### Passiva: **Mentor Cósmico**
- Quando noite de **Lua Cheia**: +100% de dano
- Quando noite de **Lua Crescente**: Revela a Fraqueza dos inimigos
- Quando noite de **Lua Minguante**: Revela os Tipos de Dano dos inimigos
- Quando noite de **Lua Nova**: -20% em todos os atributos
### Efeito: Conceder **Destinado**
- o alvo recebe +20% Afinidade
### Efeito: Afligir **Encharcado** 
- o alvo recebe -10% Evasão & +10% de dano Elemental

## Afiliação em **Viora**
### Passiva: **Viajante**
- Pode gastar o turno para reposicionar a ordem de ação do campo de batalha
### Efeito: Conceder **Sincronizado** 
- O alvo recebe +5% em todos os atributos **repetitivel**
### Efeito: Afligir **Ressonante** 
- o alvo recebe +20% de dano para o último Tipo de Dano que recebeu 

## Afiliação em **Fai Mei**
### Passiva: **Força da Fronteira**
- Uma vez por combate: Ao receber dano letal, resista com 1 de HP
### Efeito: Afligir **Provocado** 
- O alvo prioriza o ataque ao usuário
### Efeito: Conceder **Persistir** 
- O alvo recebe +20% de Resistência 

## Afiliação em **Eiar**
### Passiva: **Certeza das Estações**
- A cada quarta **estação**, ganhe uma extra para ser feita no turno
### Efeito: Tático **Rotacionar** 
- Aplica uma das quatro **estações** no campo de batalha
### Efeito: Conceder **Refrescado** 
- Efeitos que Afligirem o alvo duram somente 1 turno 

## Afiliação em **Nillaya**
### Passiva: **Vislumbre da Passagem**
- Pode gastar o turno para consumir Aflições de aliados para si mesmo
### Efeito: Afligir **Ruína**
- O alvo pode ser afligido por mais de um Efeito, desconsiderando este
### Efeito: Conceder **Pacto** 
- Sempre que o alvo é afligido por um efeito, absorva-o
- Sempre que o fizer, absorva junto 10% do Fluxo total do alvo

## Afiliação em **Sophia**
### Passiva: **Checkpoint**
- Pode gastar o turno para criar um **checkpoint**, registrando exatamente o estado de cada participante da batalha
### Efeito: Conceder **Acelerar** 
- o alvo recebe +20% de evasão
### Efeito: Tático **Flashback**
- É necessário ter um **checkpoint** definido 
- O alvo retorna ao estado do **checkpoint**, consome o **checkpoint**

## Afiliação em **Elphis**
### Passiva: **Blink**
- Pode gastar o turno para se reposicionar fisicamente no campo de batalha
### Efeito: Conceder **Elevado** 
- o alvo recebe +20% de Aptidão
### Efeito: Tático **Troca**
- Pode aplicar trocar dois alvos de posição

## Afiliação em **Darcell**
### Passiva: **Refúgio**
- Pode gastar o turno para fugir do campo de batalha
### Efeito: Conceder **Coberto** 
- Torna o alvo inalvejavel
### Efeito: Afligir **Aterrorizado**
- O alvo recebe -20% de Carisma

## Afiliação em **Boreas**
### Passiva: **Quebrar**
- Causa o dobro de dano em inimigos **congelados**
### Efeito: Tático **Névoa** 
- Inimigos no campo de batalha tem 50% de chance de acertar o alvo errado
### Efeito: Afligir **Congelado**
- O alvo recebe -10% de Aptidão
- O alvo recebe -10% de Resistência
- O alvo recebe -10% de Evasão

# Vantagens
## Posicionamento
- +10% Evasão
- +10% Precisão
## Camuflagem
- +20% Precisão

# Armas
## Modelo Base
### Composição
```
{
    "nome": "Exemplo de Nome",
    "atributosEscalaveis": [ ("nome", "valor da taxa"), ... ],
    "tipoDeDano": "Tipo de Dano"
}
```
### Dano Adicional
 ```
 Soma de (Valor do Atributo * Taxa de Escalabilidade) para cada Atributo em atributosEscalaveis
 ```

# Decair
Sanidade pode ser usada para gerar diferentes recursos ao jogador, essa ação é conhecida como Decair. 

| Recurso        | Conversão           |
| ------------- |:-------------:|
| Atributo      | Cada ponto equivale a 10% de aumento |
<br />