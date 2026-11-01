# 🌸 Flor Pontilhada

Uma flor roxa feita de **milhares de pontinhos** que brota da terra sob uma nuvem de chuva, num céu estrelado. Ela desabrocha, brilha e, quando a chuva para, murcha e suas pétalas caem no chão.

Um arquivo só, sem instalar nada e **sem precisar de internet**. É só abrir no navegador.

> 🔗 **Demo ao vivo:** `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
---

## ✨ A história que a animação conta

A animação dura cerca de **40 segundos** e passa por estas etapas:

1. 🌌 **Céu estrelado:** estrelinhas piscam sobre um chão de terra pontilhada, com pedrinhas.
2. ☁️ **Nuvem e chuva:** uma nuvem se forma pontinho a pontinho e começa a chover, com respingos no chão.
3. 🌱 **Brotinho:** a terra se mexe e o caule sobe, abrindo folhas de tons verdes, azuis e roxos.
4. 🌸 **Desabrochar:** a flor, com 23 pétalas em 4 camadas, se abre devagar e mostra os estames no centro.
5. ✨ **Brilho:** um halo, um anel de luz e faíscas douradas aparecem ao redor da flor.
6. 🍂 **Fim da chuva:** a nuvem vai embora, a flor murcha, o caule fica marrom e as pétalas caem no chão.

Só a cabeça da flor tem **mais de 20 mil pontinhos**.

---

## 🎮 Como interagir

| Ação | O que acontece |
|---|---|
| Clicar / tocar na tela | Recomeça a animação |
| Tecla `R` | Também recomeça |
| Tecla `Espaço` | Pausa e continua |

Funciona no computador e no celular. Para quem prefere menos movimento, o navegador com a opção "reduzir movimento" ligada mostra a flor aberta, parada.

---

## ▶️ Como usar

**Opção 1: abrir direto**
1. Baixe o arquivo `index.html` (ou `Flor_Pontilhada.html`).
2. Dê dois cliques nele. Ele abre no seu navegador.
---

## 🧠 Como funciona

- **Pontilhismo em pixels:** em vez de desenhar formas, o código sorteia milhares de pontos e "carimba" cada um direto num buffer de pixels. A flor, o caule, as folhas, a nuvem, a chuva e a terra são todos feitos assim.
- **Pétalas em curvas:** cada ponto de uma pétala tem uma posição calculada por uma curva que vai se abrindo conforme a flor desabrocha e se fechando quando ela murcha.
- **Linha do tempo com curvas suaves:** uma tabela de "momentos-chave" (`KEYS`) diz quanto o caule cresceu, quanto a flor abriu, quanto brilha e quanto murchou em cada instante, e o código suaviza a passagem entre eles.
- **Sorteio com semente (`seed`):** o aleatório é "combinado" de antemão, então a mesma semente sempre gera a mesma flor.
- **Qualidade automática:** se o aparelho estiver lento, o programa diminui a resolução sozinho para não travar.

**Tecnologias:** HTML, CSS e JavaScript puro (Canvas 2D). Nenhuma biblioteca externa.

---

## 🛠️ Personalize

Tudo fica no próprio arquivo, no começo do `<script>`:

- **`STEM_PAL`, `LEAF_PAL`, `LAYERS`**: as cores do caule, das folhas e de cada camada de pétalas.
- **`LAYERS`**: quantidade, abertura e tamanho das pétalas (`n` é o número de pétalas de cada camada).
- **`KEYS`**: a linha do tempo, ou seja, quando brota, abre, brilha e murcha.
- **`TIME_SCALE`**: a velocidade geral (menor = mais rápido).
- **`RAIN_START` e `RAIN_END`**: quando a chuva começa e termina.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Sinta-se livre para usar e adaptar, mantendo o crédito.

Feito por **gordaoprojetos** · [Instagram](https://www.instagram.com/gordaoprojetos/)
