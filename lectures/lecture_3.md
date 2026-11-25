---
title: "Теория вероятностей и математическая статистика"
subtitle: "Условная вероятность. Независимость событий."
institute: "Прикладные нейросетевые технологии, ФКН ВШЭ."
author: "Глеб Карпов"
format: 
    beamer:
        pdf-engine: xelatex
        aspectratio: 169
        fontsize: 9pt
        theme: Singapore
        fonmttheme: serif
        section-titles: true
        incremental: false
        include-in-header: ../files/xeheader.tex  # Custom LaTeX commands and preamble
---

{{< include ../atoms/probability/conditional.md >}}

{{< include ../atoms/probability/independency.md >}}

## Задача

Бросаются два кубика. Какова условная вероятность того, что хотя бы на одном из них выпало $6$, при условии, что значения на кубиках различны?

## Задача

Бросаются два кубика.

\begin{itemize}
    \item Какова условная вероятность того, что на первом кубике выпало $4$, при условии, что сумма значений равна $6$?
    \item Какова условная вероятность того, что на первом кубике выпало $4$, при условии, что сумма значений равна $7$?
\end{itemize}
