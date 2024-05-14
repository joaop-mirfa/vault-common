
## 1- Intro

1.1- Relações entre variáveis envolvidas em um experimento
	 - Determinísticas
	 - Semideterminísticas
	 - Empíricas

1.2 Determinação de uma formula matemática

1.3 Pertubação na relação de variáveis
	- precisão
	- erros
	- variações de leituras

1.4 Objetivo Ajuste de Curvas

1.5 O que é a regressão



## 2 -Regressão Linear Simples

Relação simples entre 2 variáveis
![[Pasted image 20240514084927.png]]

1.2 Diagrama de dispersão

1.3 Retas de regressão 
![[Pasted image 20240514085149.png]]

Necessário estimar parâmetros B0 e B1

1.4 Qualidade do modelo

Mensurar o desvio:
![[Pasted image 20240514085354.png]]

u <- distancia vertical do ponto ate a reta


## 3- Método dos quadrados mínimos

Método que propõe encontrar o menor valor de desvio:

![[Pasted image 20240514085653.png]]

funçao D(β0 , β1 ) possui um mínimo -> onde as derivadas parciais se anulam.

![[Pasted image 20240514085954.png]]

Valores em que D(β0 , β1 ) apresenta um mínimo são obtidos pela solução do sistema linear (1), denominado equaçoes normais.

![[Pasted image 20240514090129.png]]

Para resolver, utilizar operações l elementares
![[Pasted image 20240514090236.png]]

Encontra-se então os parâmetros estimados

![[Pasted image 20240514090314.png]]


1.4 Observações
O ajustes por quadrado minimo apresenta o melhor dos resultados do desvio comparado a regressão linear simples


