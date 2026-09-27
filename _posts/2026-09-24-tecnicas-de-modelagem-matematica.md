---
title: Técnicas de Modelagem Matemática
description: Composição de técnicas que eu uso para modelagem em geral.
author: jonatas
date: 2026-09-24 15:35:00 -0300
categories: [Design 3D, Matemática]
tags: [Utilidades]
render_with_liquid: false
math: true
pin: false
toc: true
---
Composição de técnicas que eu uso para modelagem em geral.

## 1 | Distribuição Circular

Divida um círculo de 360° em um número de partes iguais, e você encontrará o ângulo para replicar uma malha em sentido circular.

$$
360° \,÷\, n = x°\, ×\, n
$$

## 2 | Escalas

#### 2.1 Descobrir Fator de Escala Uniforme

Divida o valor da escala desejada de um modelo pela escala que ele tem, o resultado será o fator da escala necessário ao aplicar redimensionamento uniforme da malha.

$$
S = \frac{A}{B}\\[1.2em]\text{A = Valor desejado}\\\text{B = Valor real}
$$

#### 2.2 Desfazer Dimensionamento Uniforme Aplicado

Divida 1 pelo fator da escala aplicado para encontrar o fator usado para desfazer um redimencionamento uniforme.

$$
So = \frac{1}{S}\\[1.2em]\text{S = Fator de Escala Aplicado}\\\text{So = Inverso do Fator de Escala Aplicado}
$$
