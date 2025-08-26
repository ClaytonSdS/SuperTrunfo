# SuperTrunfo
## Funcionamento
O usuário deverá fornecer ao computador as informações para o preenchimento de **duas cartas**, representando dois países diferentes.

As informações que deverão ser fornecidas estão listadas na tabela abaixo:

| Parâmetro                        | Tipo                     |
|---------------------------------|---------------------------|
| Nome do País (sem espaços)      | char[50]                |
| População                       | unsigned int            |
| Área (em km²)                   | float                   |
| PIB (em bilhões de reais)       | float                   |
| Número de Pontos Turísticos     | unsigned short int      |

---

## Lógica do Jogo
O jogo funciona da seguinte forma:

1. O usuário informa os atributos para as duas cartas.
2. Em seguida, escolhe **dois atributos** para comparar entre as cartas.
3. O programa indica qual carta venceu em cada atributo escolhido.
4. Em caso de empate, o programa exibirá **"Empate"**.
5. No final, o programa soma os pontos dos dois atributos e determina a carta vencedora.

Atributos disponíveis para comparação:

| Opção | Atributo                          | Tipo                  |
|-------|------------------------------------|-----------------------|
| 1     | População                         | unsigned int          |
| 2     | Área (em km²)                     | float                 |
| 3     | PIB (em bilhões de reais)         | float                 |
| 4     | Número de Pontos Turísticos       | unsigned short int    |
| 5     | Densidade Demográfica (habitantes/km²) | float            |

---

## Como executar
Primeiro, faça o clone do repositório:

```bash
git clone https://github.com/ClaytonSdS/SuperTrunfo
cd SuperTrunfo
```

Depois, compile e execute o jogo com os seguintes comandos:

```bash
gcc supertrunfo.c -o supertrunfo
./supertrunfo
```
