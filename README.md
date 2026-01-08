# Waywall Config — 1366x768

[![GitHub last commit](https://img.shields.io/github/last-commit/gustavogordoni/waywall-config?color=purple)](https://github.com/gustavogordoni/waywall-config/commits/)
[![License](https://img.shields.io/github/license/gustavogordoni/waywall-config)](https://github.com/gustavogordoni/waywall-config/blob/main/LICENSE)

## Introdução

Este repositório é uma versão modificada do **[Waywall Generic Config](https://github.com/arjuncgore/waywall_generic_config)**, adaptada para funcionar o mais próximo do correto na resolução **1366x768**.

[English Version](README.en.md)

## Descrição

O foco desta versão é ajustar **mirrors, overlays e resoluções** para telas 1366x768, mantendo o comportamento e as funcionalidades do config original, mas com melhor alinhamento e usabilidade nessa resolução.

As modificações envolvem principalmente ajustes de tamanho, posição e escala dos elementos visuais.

## Instalação

Clone este repositório diretamente na pasta de configuração do Waywall:

```bash
git clone https://github.com/gustavogordoni/waywall-config ~/.config/waywall
````

Caso já possua um config anterior e queira fazer backup:

```bash
mv ~/.config/waywall ~/.config/waywall.bkp
git clone https://github.com/gustavogordoni/waywall-config ~/.config/waywall
```

## Imagens (Screenshots)

<img src="preview/tall_1.png" width="1366" />
<img src="preview/tall_2.png" width="1366" />
<img src="preview/thin_1.png" width="1366" />
<img src="preview/thin_2.png" width="1366" />
<!-- <img src="preview/wide_1.png" width="1366" /> -->
<img src="preview/wide_2.png" width="1366" />

<details>
<summary><strong>Explicação detalhada das imagens</strong></summary>

### Tall (Mirror de medição / Eye Throws)

As imagens abaixo mostram o **modo Tall**, ativado pela tecla **F2**.

Esse modo exibe um *mirror* vertical que permite ao jogador **medir lançamentos do Olho do Fim** com precisão, utilizando o **Ninjabrain Bot**.
Ele também é totalmente compatível com **Boat Eye**, sendo possível utilizar medições tanto com barco quanto sem, dependendo da configuração de sensibilidade.

Esse setup é ideal para:

* Medir eye throws com Ninjabrain Bot
* Utilizar Boat Eye no Wayland
* Trabalhar com sensibilidade ajustada automaticamente via Waywall

<img src="preview/tall_1.png" width="1366" />
<img src="preview/tall_2.png" width="1366" />

---

### Thin (Contagem de entidades / Pie Chart)

O modo **Thin** é ativado pela tecla **Alt esquerdo**.

Esse modo reduz a largura da tela e facilita a **visualização da contagem de entidades em uma direção específica**, sendo extremamente útil para:

* Encontrar **bastiões** no Nether
* Utilizar o **Pie Chart** de forma mais eficiente
* Procurar **baús de tesouro**
* Escanear **strongholds** e localizar a sala do portal com mais facilidade

<img src="preview/thin_1.png" width="1366" />
<img src="preview/thin_2.png" width="1366" />

---

### Wide (Redução de fog / Exploração no Nether)

O modo **Wide** é ativado pela tecla **B**.

Esse modo comprime a imagem na vertical e a estica na horizontal, o que permite **reduzir significativamente o efeito do fog do jogo**, especialmente no Nether.

Ele é extremamente útil para:

* Localizar **Nether Fortresses**
* Encontrar **Bastions**
* Explorar grandes áreas do Nether com melhor visibilidade

Abaixo, a comparação:

* **Imagem 1**: visão normal (Wide desativado)
* **Imagem 2**: visão com Wide ativado — o bastião se torna visível

<img src="preview/wide_1.png" width="1366" />
<img src="preview/wide_2.png" width="1366" />

</details>

## Créditos

Config original e base do projeto:
[https://github.com/arjuncgore/waywall_generic_config](https://github.com/arjuncgore/waywall_generic_config)