# 🍓 Pomar da Memória

Jogo físico de memória sensorial desenvolvido com Arduino destinado para crianças portadoras de deficiências visuais. O jogador ouve o nome de 3 frutas, identifica cada uma pelo formato tátil (feita com biscuit) e aproxima do leitor RFID na ordem correta.

Projeto desenvolvido para a cadeira de **Projetos 1** do primeiro período de **Ciência da Computação e Design** da [CESAR School](https://www.cesar.school/).

---

## 🎮 Como funciona

1. Pressione o botão — o jogo reproduz o tutorial
2. Pressione novamente — o jogo sorteia e fala 3 frutas em ordem
3. O jogador identifica as frutas pelo tato e aproxima cada uma do leitor RFID
4. Ao aproximar, o jogo fala o nome da fruta em voz alta
5. Após a 3ª fruta, o jogo informa se a ordem estava correta

---

## 🛠️ Tecnologias

- Arduino Uno
- Módulo RFID MFRC522
- Módulo MP3 YX5300
- Tags RFID MIFARE 13.56MHz
- Frutas feitas com biscuit

---

## Esquemático
```
Tag RFID
    ↓
Leitor RFID MFRC522
    ↓
Arduino Uno
    ↓
Módulo MP3 YX5300
    ↓
Alto-falante
```

---

## 👥 Equipe

**Orientador:** Leo Macedo

| Nome | LinkedIn |
|---|---|
| Caio Mendonça de Oliveira | [linkedin.com/in/caio-oliveira](https://www.linkedin.com/in/caio-oliveira912/) |
| Helena Gabrielli Bezerra Santos | [linkedin.com/in/helena-santos](https://www.linkedin.com/in/helena-santos-a89288418/) |
| João Eduardo Mascarenhas Leite Lemos | [linkedin.com/in/joão-eduardo](https://www.linkedin.com/in/joão-eduardo-121052418) |
| Jose Henrique Carneiro Lapa | [linkedin.com/in/henrique-carneiro-dev](https://www.linkedin.com/in/henrique-carneiro-dev/) |
| Júlia Teixeira Catão Ribeiro | [linkedin.com/in/júlia-catão](https://www.linkedin.com/in/júlia-catão-019b07417?utm_source=share_via&utm_content=profile&utm_medium=member_ios) |
| Lunna de Aguiar Mendonça Morelato Moreno | [linkedin.com/in/lunnaaguiar](https://www.linkedin.com/in/lunnaaguiar/) |
| Ricardo Amorim Bayma | [linkedin.com/in/ricardo-bayma](https://www.linkedin.com/in/ricardo-bayma-aa5a83411/) |
| Sofia Marinho de Hollanda Cavalcanti | [linkedin.com/in/sofia-marinho](https://www.linkedin.com/in/sofia-marinho-de-hollanda-cavalcanti-136a14400/) |
| Thony Guilherme de Aquino Barreto | [linkedin.com/in/thonybarreto](https://www.linkedin.com/in/thonybarreto/) |
