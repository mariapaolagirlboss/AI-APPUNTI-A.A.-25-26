- **Entropia**
$$H(X) = - \sum_{i=1}^{n} P(X=i)\log_2 P(X=i)$$
- **Cross-entropy** 
	$$\sum_{x} P(x) \cdot \log(Q(x))$$
- **Esercizi relativi al dataset**
	$$
\begin{aligned}
\text{Positivi Totali (P)} &= TP + FN \\
\text{Negativi Totali (N)} &= TN + FP \\
\text{Totale Dati (All)} &= TP + TN + FP + FN \\
\\[10pt]
\text{Accuratezza} &= \frac{TP + TN}{\text{All}} \\
\\[10pt]
\text{Precisione} &= \frac{TP}{TP + FP} \\
\\[10pt]
\text{Richiamo (Recall)} &= \frac{TP}{TP + FN} \\
\\[10pt]
\text{Specificità} &= \frac{TN}{TN + FP} \\
\\[10pt]
\text{F1 Score} &= 2 \cdot \frac{\text{Precisione} \cdot \text{Recall}}{\text{Precisione} + \text{Recall}}
\end{aligned}
$$
- **Derivata della funzione logistica**
	$$\sigma(x) \cdot (1 - \sigma(x))$$
- **Output layer convolutivo**
	$$\text{Output} = \frac{W + P - K}{S} + 1$$
- **Parametri layer convolutivo**
	$$
[(\text{Kernel}_h \times \text{Kernel}_w \times C_{in}) + 1] \times C_{out}
$$

- **Parametri indipendenti**
	$$ (\text{Numero di Classi}) \times (\text{Numero di Features}) + \text{Priors} $$
	i Priors si calcono nel seguente modo: $P(C_1) + P(C_2) + P(C_3) + P(C_4) + P(C_5) = 1$


- **Campo ricettivo di un neurone**
	$$ RF_{\text{totale}} = RF_{\text{precedente}} + (\text{Kernel} - 1) $$
- **Numero di backpropagation**
	$$ \text{Numero di Backpropagation} = \frac{\text{Totale Dati}}{\text{Batch Size}}$$
	