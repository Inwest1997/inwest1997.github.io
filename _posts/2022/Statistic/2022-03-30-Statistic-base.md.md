---
title:  "[Statistics] 통계학 기본 베이스"
excerpt: "사회과학자들은 어떤 실 세계의 과정이 특정 조건에서 어떻게 작동하는지 예측하기 위해 그런 과정의 모형을 구축합니다. 그리고 연구자는 그런 과정에 직접 접근할 수 없으므로, 그 과정을 대표하는 자료를 수집하고 그 자료를 이용해서 통계적 모형을 구축하고 그 통계적 모형을 이용해서 실세계의 현상을 예측합니다."

categories:
  - Statistics
# tags:
#   - [Statistics]

toc: true
toc_sticky: true
use_math: true

# date: 2022-03-20
# last_modified_at: 2022-03-20
---



# 1 통계적 모형의 구축

사회과학자들은 어떤 실 세계의 과정이 특정 조건에서 어떻게 작동하는지 예측하기 위해 그런 과정의 모형을 구축합니다. 그리고 연구자는 그런 과정에 직접 접근할 수 없으므로, 그 과정을 대표하는 자료를 수집하고 그 자료를 이용해서 통계적 모형을 구축하고 그 통계적 모형을 이용해서 실세계의 현상을 예측합니다.

$$
\begin{matrix}
수집   \ \ \ \ \implies\ \ \ \ \ 구축  \ \ \ \ \ \ \implies예측\\
대표하는\ 데이터\implies 통계적모형\implies실세계의 \ 현상 
\end{matrix}
$$

하지만 실 세계 상황에 직접 접근하지 못 하니, 할 수 있는 것은 우리가 만든 모형에 기초해서 심리학이나 사회학, 생물학, 경제학적 과정에 관한 무언가를 추론하는 것 뿐입니다.

정확한 추론을 하기 위해서는 통계 모형이 우리가 수집한 자료(관측 자료)를 제대로 대표해야하고, 이때 우리의 통계적 모형이 자료를 얼마나 잘 대표하는지 알기위해 적합(*fit*)이라는 개념을 사용합니다.

통계적 모형을 자료 집합에 적합시킬 때는 자료에 잘 적합하는 모형을 만드는 것이 중요합니다. 왜냐하면 만약 관측 자료에 대한 모형이 데이터에 적합하지 않다면, 그 모형에 기초한 결론(예측)또한 그만큼 나빠지기 때문이죠.

# 2 모집단과 표본

연구자가 사람이나 사물의 모집단(*population*)전체에 적용되는 결과를 얻고자 합니다. 예를 들어 심리학자는 모든 사람에게 나타나는 과정(*process*)을 발견하려 하고, 생물학자는 모든 세포에서 발생하는 과정에 관심이 있으며, 경제학자는 모든 임금에 적용되는 모형을 구축하길 원합니다.

그리고 이 모집단은 아주 일반적일 수도(모든 인류), 또는 아주 협소할 수도 있습니다(이름이 철수인 한국인). 보통 과학자는 협소한 모집단보다는 일반적인 모집단에 관한 무엇가를 추론하기를 원합니다. 

협소한 모집단일수록 편향이 되기 쉬우며, 보다 의미있는 결과를 얻어내기 힘들기 때문입니다.

예를 들어, 한국에 살고 있는 ‘철수’ 라는 이름을 가진 20대 남성이 카페가서 공부하는 성향이 강하다는 결론을 얻는 것은 별로 흥미롭지 않습니다. 반면 모든 사람이 카페가서 공부하는 성향이 강하다는 것을 알아내는 것은 나름 흥미로운 연구주제가 될 수 있습니다.

하지만 과학자가 어떤 모집단의 구성원 전부에 접근할 수 있는 경우는 있다고 해도 아주 드물고, 사실상 매우 힘들기 때문에 우리는 **모집단의 작은 부분집합(표본(*sample*))에서 자료를 수집하고, 그 자료로부터 모집단 전체에 관한 어떤 것을 추론합니다.**

모집단 전체(축소 모형)를 수집하고 그 표본으로부터 모집단의 행동에 관한 것을 추론합니다. 그리고 표본이 클수록 그것이 모집단 전체를 반영할 가능성 또한 커집니다.

만일 모집단에서 무작위로 여러 개의 표본을 추출한다면, 각 표본이 약간씩 다른 결과를 낼 것이지만, 평균적으로 큰 표본들은 상당히 비슷한 결과를 낼 수 있습니다.

# 3 단순한 통계적 모형 및 몇 가지

## 3. 1 평균 : 아주 단순한 통계적 모형

평균이 반드시 자료에 있는 실제 관측값인 것은 아닙니다.

평균은 가설상의 값이므로, 하나의 통계적 모형으로 간주할 수 있습니다.

예를 들어 다섯 명의 통계학 강사를 선택해서 친구 수를 조사했더니 1, 2, 3, 3, 4라는 자료가 나왔다고 가정해봅니다. 이들의 평균 친구 수는 그 값들을 모두 더한 것에 값들의 개수를 나는 것, 즉 (1 + 2 + 3 + 3 + 4)/5 = 2.6입니다.

위의 예제처럼 어떤 사람의 친구가 2.6명일 수는 없습니다. 따라서 평균값은 **가설상의(*hypothetical*)값**입니다. 그런 만큼, **평균은 자료를 요약하기 위해 만들어 낸 하나의 통계적 모형**이라고 할 수 있습니다.

## 3. 2 평균의 적합 평가: 제곱합, 분산, 표준편차

그 어떠한 통계적 모형이더라도 ,자료에 대한 그 모형의 적합(*fit*)을 평가해 봐야됩니다.

### 이탈도(deviance)

대부분의 통계적 모형에서는 그 모형이 얼마나 정확한지를 실제 자료와 모형의 차이를 통해서 알아낼 수 있습니다.

차이를 보는 가장 간단한 방법은 실제 자료의 값에서 모형의 값을 뺀 차들을 살펴보는 것입니다.

아래 그림은 통계학 강사들의 친구 수와 그 평균, 그리고 둘의 차이들을 나타냈습니다.

![Untitled.png](/assets/images/posts/Statistics/2022-03-30-Statistics-Base/Untitled.png)


이 그래프에서 둥근 점은 관측자료이고, 평균을 나타내는 직선은 하나의 모형에 해당됩니다.그리고 점선으로 된 수직 선분들은 해당 관측값과 평군값의 차이를 나타냅니다.

위 그림에서 수직 선분들이 나타내는 관측자료와 모형의 차이를 **이탈도(deviance)**라고 합니다.

- 이탈도는 간단히 말해 모형의 오차(*error*)에 해당됩니다.
- 이탈도 계산은 관측값($x_i$)에서 모형(지금 예에서는 평균, $\bar{x}$)을 빼면 됩니다.
    
    예를 들어 강사1의 친구는 한명 뿐이므로 그 차이는 $x_1- \bar{x}=1-2.6=-1.6$입니다. 이 경우 이탈도는 음수인데, 이는 모형이 이 강사의 인기를 **과대추정(*overestimate*)**했다고 할 수 있습니다. 이유는 이 모형은 그 강사의 친구가 2.6명이라고 예측하지만, 실제로는 한 명 뿐이기 때문입니다.
    

이러한 **편차**(*deviation*, 평균이 통계적 모형일 때의 이탈도)들로 모형의 정확도를 추정하는 방법 증 하나는 이탈도들을 모두 더하는 것이지만, 실제로 계산해 보면 의외의 답이 나올 때도 있습니다. 다음 수식은 통계학 강사 친구 수의 전체 오차입니다.

$$
\begin{matrix}
전체\ 오차 =편차들의\ 합&=&\sum(x_i-\bar{x})\\&=&(-1.6)+(-0.6)+(0.4)+(0.4)+(1.4)\\
&=&0
\end{matrix}
$$

### 오차제곱합(SS)

위에서 보인 예제처럼, 편차들은 음의 오차들과 양의 오차들이 상쇄되어 전체 오차가 0이 되었습니다. 의미있는 결과를 얻기 위해서는 오차의 부호를 무시해야 하는데, 한 가지 수학적 해법은 오차를 제곱하는 것입니다.

예제의 편차들을 제곱한 뒤에 더해보겠습니다.

$$
오차제곱합(SS)\\
\begin{matrix}
&=&\sum(x_i-\bar{x})(x_i-\bar{x})\\
&=&(-1.6)^2+(-0.6)^2+(0.4)^2+(1.4)^2+(1.4)^2\\
&=& 2.56+0.36+0.16+0.16+1.96\\
&=& 5.20
\end{matrix}
$$

오차제곱합(*sum of squared errors*), 줄여서 제곱합($SS$)은 모형의 정확도를 잘 측정합니다.

### 분산(variance)

오차제곱합이 수집한 자료의 양에 의존한다는 점도 상당히 명확합니다. 자료점(*data point*)이 많을수록 $SS$도 커짐. 이 문제를 극복하는 방법은 $SS$를 관측값들의 개수$N$으로 나누어 평균오차를 구하는 것입니다.

그런데 만일 표본의 평균오차 자체에만 관심이 있다면 그냥 $N$으로만 나누면 되지만, 우리는 보통 모집단의 오차를 추정하기 위해 표본의 오차에 관심을 가집니다.

그런 경우에는 $SS$를 관측 수에서 1을 뺀 값으로 나눔.

$$
분산(S^2)= \frac{SS}{N-1}=\frac{\sum(x_i-\bar{x})^2}{N-1}=\frac{5.20}{4}=1.3
$$

따라서 분산은 평균과 관측값 사이의 평균오차이며, 모형이 실제 자료에 얼마나 적합한지 나타내는 하나의 측도이기도 합니다.

<aside>
💡 **자유도**(*degree of freedom*)
통계학에서 자유도는 임의로 변할 수 있는 관측들의 개수와 관련있습니다.

어떤 모집단에서 $N$ 가지 값을 관찰해서 하나의 표본을 얻었다고 하면, 그 $N$ 개의 점수는 어떤 방식으로든 자유로이 변할 수 있습니다(어떤 값이다로 가질 수 있음) . 그러나 이 관측값 $N$ 개의 표본으로 모집단의 표준편차를 계산한다면, 표본의 평균을 모집단의 평균에 대한 추정값으로 사용해야므로 하나의 매개변수(모수)를 고정하게 되는 셈이 되는 것이죠. 

예를 들어 표본의 평균이 10이고 모집단의 평균도 10이라고 가정했을 때, 그 값은 하나의 상수가 됩니다. 이 매개 변수가 고정이 되었을 때 $N$ 개의 점수 모두 자유로이 변할 수 있을까요?

평규이 일정하게 유지되려면 오직 $N - 1$ 개의 값만 자유로이 변할 수 있습니다. 

표본이 4 개 있다고 가정하고, 표본값을 8, 9, 11, 12라고 가정한다면 평균값은 10이됩니다.  만일 그 중 세 값을 7, 15, 8로 바꾼다면 나머지 한 값은 반드시 10이어야합니다. 그래야 평균이 변하지 않기 때문이죠.
따라서, 어떤 매개변수 하나를 상수로 유지하려면 자유도는 표본 크기에서 1을 뺀 값이어야합니다. 표본을 이용해서 모집단의 표준 편차를 추정할 때 제곱합을 $N$이 아니라 $N-1$로 나누어야하는 이유가 바로 이 때문입니다.
통계학에서는 "변인의 수 빼기 제약"이 됩니다. 쉽게 생각해서, 만약 숫자 5개의 평균값이 3이면, 숫자 4개는 자유롭게 정할 수 있으나 마지막 하나의 숫자는 나머지 네 개의 숫자에 의해 결정된다는 뜻이죠. 즉, 자유롭게 결정할 수 있는 숫자는 4개이기 때문에 자유도는 4라고 할 수 있는 것입니다.

</aside>

### 표준편차(standard deviation, SD)( 평균이 자료를 얼마나 잘 대표하는지를 평가하는 측도)

분산의 측도(measure)은 그 단위가 제곱이라는 문제점이 있습니다.

예를 들어 분산은 평균 친구 수의 제곱이 1.3임을 말해주고, 친구가 1.3명인 것도 사실 말이 잘 안 되는데, 친구 수의 제곱은 더욱 말이 되지 않습니다. 

그래서 분산 대신 분산의 제곱근을 사용하는 경우가 많습니다.

$$
\begin{matrix}
s &=& \sqrt{\frac{\sum{(x_i-\bar{x})^2}}{N-1}}\\
&=& \sqrt{1.3}
\\&=&1.14
\end{matrix}
$$

이러한 제곱합과 분산, 표준편차는 모두 평균이라는 통계적 모형의 '적합'을( 즉, 평균이 자료를 얼마나 잘 대표하는지를) 나타냅니다.

- 표준편차가 작다는(평균값 자체의 크기에 상대적으로)것은 자료 점들이 평균에 가깝다는 뜻입니다.
- 표준편차가 크다는 것은 자료점들이 평균에서 멀다는 뜻(그리고 이는 평균이 자료를 그리 잘 대표하지 않는다는 뜻임)입니다.
- 표준편차가 0이면 모든 점수가 같은 값일 가능성이 있습니다.

### 표준편차와 분포의 형태

분산과 표준편차는 자료집합의 모형으로서의 평균의 정확도를 말해줄 뿐만 아니라 점수들이 어떤 형태로 분포되는지 알려줍니다.

평균이 자료를 잘 대표한다면 점수들 대부분이 평균 근처에 몰려 있을 것이며, 띠리사 표준편차가 평균을 기준으로 비교적 작을 것이고, 반대로 만약 자료를 잘 대표하지 않을 때는 점수들이 평균에서 좀 더 멀리 퍼지게 되고, 표준편차는 커집니다.

즉, 표준편차가 클수록 분포가 더 평평해질 것입니다.

## 3. 3 통계적 모형으로서의 평균

$$
결과_i=모형+오차_i
$$

위의 방적식은 우리가 관측하는 자료에 적합시키고자 하는 모형에 일정한 양의 오차를 더함으로써 예측할 수 있다는 것입니다.

분산과 표준편차도 어떤 근본적인 개념을 묘사하는데, 이는 바로 모형이 자료에 얼마나 적합한지를 측정한다는 개념입니다. 모형이 자료에 얼마나 적합한지를 파악할 때 우리는 주로 자료가 모형과 얼마나 다른지 , 다시 말해 자료가 모형으로부터 얼마나 벗어났는지를 살펴봅니다, 그리고 흔히 오차제곱합을 이용해서 자료가 모형으로 부터 벗어난 정도를 측정합니다.

$$
자료가 \ 벗어난\ 정도=\sum(관측값-모형)^2
$$

즉, 우리는 관측한 자료와 그 자료에 적합시키려는 모형을 비교해서 그 차이들을 제곱함으로써 모형을 평가합니다.

# 4 자료 이상의 것을 얻으려면

표본 자료에서 그러한 일반적인 예측을 이끌어내는 방법을 이해하려면 먼저 모형이 표본(그 모형을 도출한)에 잘 적합하는지를 살펴보는 것이 아니라, 그 표본을 추출한 모집단에 잘 적합하는지를 살펴보아야합니다.

## 4. 1 표준오차(standard error)

한 모집단에서 여러 개의 표본을 취한다면, 그 표본들은 서로 조금씩은 다를 것이기 때문에, 특정한 하나의 표본이 모집단을 얼마나 잘 대표하는지를 아는 것도 중요하고 이때 사용하는 것이 **표준오차** 입니다.

사회과학자들은 모집단의 습성을 추정하는 한 방법으로 표본을 사용하고, 그러한 모집단에서 표본 하나를 취한다는 것은 수많은 가능한 표본 중 하나를 뽑는 것을 뜻합니다. 그리고 같은 모집단에서 여러 개의 표본을 취한다면, 표본마다 따로 평균을 계산할 수 있는데, 그러한 평균들이 모두 같지는 않을 것입니다.

- 모집단 평균(population mean,$\boldsymbol{\mu}$) :  모집단 모든 표본의 평균
- 표본평균(sample mean) : 모집단에서 여러 개의 표본을 취하고, 표본마다 구한 평균

### 표집변동(sampling variation)

표본들 사이에 차이가 있는 것을 뜻하며, 이러한 차이는 각 표본이 이 모집단의 서로 다른 구성원들로 이루어지기 때문에 발생합니다.

예를 들어 우연히 어떤 표본에는 값이 큰 표본들만 포함되어 있고, 다른 표본에는 값이 작은 표본들만 포함되어 있다면, 전자의 평균은 후자보다 높을 것입니다.

### 표집분포(sampling distribution)

같은 모집단에서 얻은 표본들의 표본 평균을 도수분포로 나타낸 것입니다. 

표집분포는 모집단에서 취한 표본들의 습성을 말해줍니다. 그리고 표집분포의 중심이 모집단 자체의 평균과 같습니다. 즉 모든 표본평균의 평균을 계산한다면 모집단 평균과 같은 값이 나올 것입니다. 

이처럼 표본평균들의 평균이 모집단의 평균과 같은 경우, 만일 모집단 평균의 정확도를 안다면 주어진 한 표본이 모집단을 얼마나 잘 대표하는지도 알 수 있습니다.

### 평균의 표준오차(standard error of the mean)

표본평균들의 표준편차를 가리키며, 줄여서 표준오차($SE$)라고 합니다.

표본평균들로 구한 표준편차는 여러 표본의 평균들이 서로 얼마나 다른지, 즉 표본평균들의 변이성이 어느 정도인지 말해줍니다.

각 표본평균과 전체 평균의 차이를 제곱한 값들을 모두 더하고, 그 합의 제곱근을 취하면 표본평균들의 표준편차가 나오는데, 이것이 바로 표준오차입니다.

### 중심극한정리(central limit theorem)

현실에서는 수백 개의 표본을 구하기가 쉽지 않으므로, 우리는 표준오차의 근사치에 의존합니다.

표본이 클수록 표집분포는 그 평균이 모집단 평균과 같고 표준편차가 다음과 같은 정규분포를 따름.

$$
\boldsymbol{\sigma}_{\bar{x}}=\frac{s}{ \sqrt{N}}
$$

만일 표본이 크면(흔히 표본이 30개 이상이면 크다고 간주) 앞의 공식을 이용해서 표준오차를 근사할 수 있습니다.

이러한 근사가 가능한 것은 애초에 표준오차가 바로 표집분포의 표준편차이기 때문입니다.

표본이 비교적 작다면(30개 미만) 표집분포는 정규분포와는 다른 형태의 분포인 t분포를 따릅니다.

<aside>
💡 표준오차 
표준오차는 표본평균들의 표준편차이고 표준오차는 주어진 표본이 모집단을 얼마나 잘 대표하는지를 나타내는 측도입니다. 표준오차가 크다는 것은 서로 다른 평균들의 변이성이 크다는 뜻이죠. 따라서 그 표본이 모집단을 그리 잘 대표하지 않을 가능성이 큽니다. 표준오차가 작다는 것은 대부분의 표본평균이 모집단 평균과 비슷하다는 뜻이고, 따라서 그 표본이 모집단을 정확하게 반영할 가능성이 크다고 할 수 있습니다.

</aside>

## 4. 2 신뢰구간

### 4. 2. 1 신뢰구간의 계산

모집단 평균의 근삿값으로서의 표본평균의 정확도를 평가하는 또 다른 접근 방식으로 우리가 평균의 참값이 속한다고 믿는 구간을 계산해보는 것입니다.

계산한 구간을 신뢰구간(confidence interval)이라고 합니다. 신뢰구간에 깔린 개념은, 모집단의 값이 속하리라고 간주되는 값들의 범위를 만드는 것입니다.

신뢰구간을 사용할 때 관건은, 그러한 구간으로부터 뭔가 유용한 사실을 알아낼 수 있도록 한계들을 정하는 것입니다.

신뢰구간이 특정한 속성들을 가지게 됨. 즉 우리가 추정하려는 대상의 참값이 그 구간에 속할 확률을 계산할 수 있습니다.

95% 신뢰구간은 모집단의 참값이 그 신뢰구간에 속할 가능성(확률)이 95%임을 뜻하고, 99%신뢰구간은 그럴 가능성이 99%임을 뜻합니다.

쉽게 생각해서 만약 어떤 평균에 대한 95%신뢰구간을 보았다면, 다음과 같이 생각하면 됩니다:

만일 표본을 100개 수집해서 평균을 계산하고 그 평균에 대한 95% 신뢰구간을 결정했다면, 100개 중 95개의 표본에서는 모집단의 평균 참값이 신뢰구간에 속하는 것입니다.

### $z$점수

95% 신뢰구간을 결정하려면 95%의 평균들이 속하는 한계들을 알아내야합니다.

만약 표본평균들이 평균 0, 표준편차 1의 정규분포를 따른다면, 95% 신뢰구간의 한계들은 $z$점수가 신뢰구간이 95%일 때의 값인 -1.96과 +1.96가 됩니다.

표본들의 평균과 표준편차가 0 과 1 이 아니라면 아래 공식을 통해 평균이 0 표준편차가 1인 $z$점수들로  변환할 수 있습니다.

$$
z=\frac{X-\bar{X}}{s}
$$

예를 들어 $z$점수 기준으로 신뢰구간의 한계가 -1.96과 +1.96임을 알았다면, 다음으로 할 일은 실제로 원본 자료의 점수들을 $z$점수로 변환하는 것입니다.

$$1.96=\frac{X-\bar{X}}{s}$$

$$-1.96=\frac{X-\bar{X}}{s}$$

그리고 최종적으로 $X$의 값을 구하는 것인데,  표준편차(공식의 s)와 평균(공식의 $\bar{X}$)을 알면 신뢰구간을 쉽게 계산할 수 있습니다.

그러나 실제로 쓰이는 것은 표준편차가 아닌 표준오차인데, 이는 우리의 관심 대상이 표본 안의 관측값들의 변이성이 아니라 표본평균들의 변이성이기 때문에 다음과 같은 수식으로 상계와 하계를 구합니다.

$$
\begin{matrix}
신뢰구간의\ 하계=\bar{X}-(1.96\times SE)\\
신뢰구간의\ 상계=\bar{X}+(1.96\times SE)
\end{matrix}
$$

한계들을 이렇게 계산하기 때문에 평균은 항상 신뢰구간의 중심에 놓입니다. 만일 평균이 실제 평균을 잘 대표한다면, 그평균의 신뢰구간은 범위가 작아야 마땅합니다.

만일 신뢰구간의 95%에 실제 평균이 속함이 확실하다면, 그 신뢰구간이 실제 평균을 포함한다고 가정할 수 있습니다.

따라서 만일 구간이 작다면 표본평균이 반드시 실제 평균과 아주 가까워야 하고, 반대로 만일 신뢰구간이 아주 넓다면 표본평균과 실제 평균의 차이가 아주 클 수 있으며, 이는 그 표본평균이 모집단을 그리 잘 대표하지 않았다는 뜻입니다.

즉, 신뢰구간을 구하려면 일단 z점수로 해당 데이터를 평균은 0, 표준편차는 1인 정규분포로 변환한 후에 구할 수 있습니다.

### 4. 2. 2 기타 신뢰구간의 계산

만약 신뢰구간이 99% 구간이나 95%구간처럼 다른 종류의 신뢰구간을 계산해야 된다면 아래 공식을 따릅니다.

$$
\begin{matrix}
신뢰구간의\ 하계=\bar{X}-(z_{\frac{1-p}{2}}\times SE)\\
신뢰구간의\ 상계=\bar{X}+(z_{\frac{1-p}{2}}\times SE)
\end{matrix}
$$

여기서 $p$는 해당 신뢰구간의 확률값입니다.

예를 들어 95%신뢰구간을 계산할 때는 (1-0.95)/2=0.025에 대한 $z$값을 사용하면 되고 90% 신뢰구간을 위해서는 (1-0.90)/2=0.05에 대한 $z$값을 사용하면 됩니다.

이런식으로 $z$값을 구한 뒤 표준오차를 곱하면 신뢰구간의 상하계가 나옵니다.

### 4. 2. 3 작은 표본을 위한 신뢰구간 계산

$z$점수는 표본이 클 때(표본이 30개 이상일 때) 잘 통하지만, 표본이 작을 때는 그렇지 않습니다.

작은 표본은 표집분포가 정규분포가 아닌 t 분포입니다.

t 분포는 표본 크기가 커짐에 따라 그 형태가 변하는 부류의 확률분포에 속합니다(표본이 아주 크면 정규분포의 형태가 됨).

작은 표본의 신뢰구간을 계산할 때는 이전과 같은 원리를 따르되 $z$값이 아닌 t 값을 이용해서 상, 하계를 계산합니다.

$$
\begin{matrix}
신뢰구간의\ 하계=\bar{X}-(t_{n-1}\times SE)\\
신뢰구간의\ 상계=\bar{X}+(t_{n-1}\times SE)
\end{matrix}
$$

공식의 n - 1은 자유도이며, 이 자유도를 이용해서 t 분포표의 t값을 조회합니다.

95% 신뢰구간의 경우에는 그 자유도에 해당하는 행에서 양쪽꼬리 검정의 확률 0.5열에 있는 t 값을 사용하면 됩니다.

### 4. 2. 4 신뢰구간의 가시화

### 같은 모집단? 다른 모집단?

신뢰구간은 모집단 평균이 속할 가능성이 큰 구간의 상, 하계를 말해줍니다(신뢰구간의 크기는 표준오차의 크기에 의존합니다). 서로 다른 평균들의 신뢰구간들을 비교해 보면 그 평균들이 같은 모집단에서 비롯된 것인지 아니면 서로 다른 모집단들에서 비롯된 것인지 어느 정도 짐작할 수 있습니다.

![Untitled1.png](/assets/images/posts/Statistics/2022-03-30-Statistics-Base/Untitled1.png)

신뢰구간이 2번과 3번처럼 겹친다는 것은 이 평균들이 같은 모집단에서 나왔을 가능성이 크다는 뜻입니다. 왜나면 두 경우 모두 평균의 참값이 해당 구간에 속할 가능성이 크며(95%의 연구들에서 그런 결과가 나오도록 계산된 구간들이므로), 두 구간이 상당히 많이 겹치므로 두 구간에 비슷한 값들이 많이 있을 것이기 때문입니다.

반대로 만약에 1번과 2번처럼 신뢰구간이 전혀 겹치지 않는다면, 두 신뢰구간의 표본들이 서로 다른 모집단에서 추출한 것이거나, 아니면 같은 모집단에서 추출한 표본들이긴 하지만 두 신뢰구간 중 하나에는 모집단 평균이 속하지 않는 것입니다. 만일 95% 신뢰구간을 사용했다면 두 번째 설명이 참일 가능성은 작습니다(그런 일은 100번 중 다섯 번, 즉 5%의 경우에만 발생). 따라서 첫 번째 설명이 좀 더 그럴듯 합니다.

### 표본들을 서로 다른 모집단에서 추출하는 것에 대해

보통 실험을 수행할 때는 둘 이상의 조건들을 어떤 방식으로든 조작하게됩니다.

만약 무작위로 사람들을 뽑아서 두 개의 표본을 만든 후 뭔가 측정을 했을 때:

보통은 그 사람들이 같은 모집단에 속한다고 기대합니다. 그런데 두 표본의 평균이 아주 다르다면, 두 표본이 사실은 서로 다른 모집단에서 온 것이라 할 수 있습니다. 이유는 우리의 실험적 조작 때문에 실제로 표본들에 차이가 생깁니다

다시 말해, 어떤 실험적 조작이 성공적이라면, 표본들이 서로 다른 모집단에서 왔다고 판명될 가능성이 크다고 할 수 있습니다. 반면, 조작이 성공적이지 않다면, 표본들이 같은 모집단에서 왔다고 판명될 가능성이 크다고 할 수 있습니다.

쉽게 말해서, 실험설계가 제대로 이뤄졌을 때 두 표본 평균이 아주 다르다면 표본이 사실은 서로 다른 집단에서 왔을 가능성이 더 높고, 설계가 제대로 이뤄지지 않았을 때는 표본들이 같은 모집단에서 왔을 가능성이 크다는 것입니다.

95% 신뢰구간이라는 것은 모집단 평균의 참값이 얼마일지에 관한 정보를 제공합니다. 만약 우리가 서로 다른 두 집단에서 표본들을 수집한다면, 해당 신뢰구간들이 서로 다를 것이라고 기대할 수 있습니다(사실, 표본들이 서로 다른 모집단에서 온 것임이 확실하다고 생각한다면, 신뢰구간들이 서로 겹칠 것이라고는 기대하지 않습니다). 

같은 모집단에서 두 표본을 수집했다면, 그리고 측정에 신뢰성이 있다면, 그 신뢰구간들은 아주 비슷할 것이라고( 즉, 거의 완전히 겹칠 것이라고) 기대할 수 있습니다

<aside>
💡 신뢰구간
평균의 신뢰구간은 전체 표본 중 95%의 표본들에서 모집단 평균이 구간의 상계와 하계 사이에 속하도록 만들어진 구간입니다. 모집단 평균이 속할 가능성이 95%로 확실한(confident)구간이 아님을 주의해야됩니다

</aside>

# 5 통계적 모형을 이용한 연구 질문 검증

 

<aside>
🔬 연구 과정의 다섯 단계 요약
1. 초기 관찰을 통해서 연구 질문을 만든다( 어떤 자료가 그것을 지지하길 기대하면서)
2. 그러한 초기 관찰을 설명하는 이론을 만든다
3. 가설을 세운다 : 이론을 일단의 검증 가능한 예측들로 분할한다
4. 가설을 검증할 자료를 수집 : 예측들을 검증하기 위해 측정해야 할 변수들을 결정하고, 그 변수들을 측정 또는 조작하는 최선의 방법을 파악함
5. 자료 분석 : 통계적 모형을 자료에 적합시킴. 이 모형은 원래의 예측들을 검증하는 역할을 함. 이 모형이 초기 예측들을 지지하는지 평가함

</aside>

### 추론 통계(inferential statistics)

많은 연구는 대립가설이 참일 가능성이 큰 추론 통계를 다룹니다. 그런 통계는 예측들을 확인 또는 기각하는데 도움이 됩니다. 이 경우 우리는 대립가설을 대표하는 자료에 통계적 모형을 적합시켜 봐서 그것이 얼마나 잘 맞는지 평가합니다. 만일 통계적 모형이 자료에 적합하다면, 우리는 초기 예측이 참이라고 가정할 수 있음. 즉, 대립가설이 참이라는 확신(신뢰)이 강해집니다. 

물론 가설이 참이라고 완전하게 확신할 수는 없습니다. 대신 우리는 모집단이 아무런 효과도 발생하지 않았을 때( 즉, 귀무가설이 참일 때) 모형이 자료에 적합할 확률을 계산합니다. 그 확률이 낮을수록 대립가설이 실제로 참이며 귀무가설을 기각해도 된다는 확신도 커집니다. 이러한 방식은 자료를 수집하기 전에 예측을 했을 때 유효합니다.

가설이 참일 가능성이 있는지에 관한 이러한 개념을 설명하는 수단으로 피셔는 다음과 같은 실험을 고안했습니다

<aside>
🔬 피셔의 밀크티 실험
실험은 밀크티 한 컵을 맛보면 그 잔에 차를 먼저 넣었느지 아니면 우유를 먼저 넣었는지 알 수 있다는 어떤 여성의 주장을 검증하기 위한 것입니다. 차를 먼저 넣은 컵들과 우유를 먼저 넣은 컵들을 그 여성에게 주어서 맞춰 보게 했습니다. 차를 먼저 넣은 컵들과 우유를 먼저 넣은 컵의 수가 같다는 점은 그녀도 알고 있습니다. 그러나 그 컵들이 어떤 순서로 제공되는 지는 알지 못함. 컵이 둘 뿐인 가장 간단한 상황에서는 그녀가 컵들을 정확히 분류할 기회가 50%입니다. 그녀가 실제로 정답을 말했다고 해서 실제로 그녀가 컵에 우유를 먼저 넣었는지 차를 먼저 넣었는지 아는 능력이 있다고 확신할 수는 없습니다. 그냥 추측만으로도 절반의 확률로 정답이 나올 수 있기 때문. 컵을 여섯 잔으로 늘려서 상황을 좀 더 복잡하게 하면 컵들을 배열하는 순서는 총 20가지($C_6^3=20$)이며, 따라서 그 여성이 정답을 맞힐 확률은 1/20(즉, 5%)이 됩니다. 만일 실제로 그 여성이 컵들을 정확히 분류한다면, 실제로 그녀에게 그런 식별 능력이 있다면 확신이 두 컵의 경우보다 휠씬 강해집니다.

</aside>

피셔의 실험에서 밀크티 여섯 컵을 예로 든 것은 우연이 아닙니다. 피셔는 결과를 확신하기에 유용한 기준으로 95%를 제시했는데, 밀크티가 여섯 컵일 때는 음미자가 정답을 맞힐 기회가 5%이므로 그 기준과 맞아떨어집니다. 이 기준은 결과가 운이 아니라 진짜라는 확신이 95%이상일 때만 그 결과가 참이라고 받아들여야 한다는 뜻입니다. 반대로 말하면, 만일 어떤 일이 전적으로 우연히 일어날 기회가 5%(.05의 확률)밖에 되지 않는다면, 그 일은 정말로 일어난 것이라고 받아들일 수 있다는 것입니다. 이를 두고 **통계적으로 유의한(statistically significant)**발견이라고 합니다.

## 5. 1 검정통계량

통계적 모형이(따라서 가설이) 수집된 자료에 의미있게(유의하게) 적합하는지도 검증할 수 있습니다

비체계적 변동은 자료에 적합시킨 모형으로는 설명할 수 없는 변동입니다. 다른 말로 해서, 비체계적 변동은 우리가 조사하는 효과 때문에 생긴 것이 아닌 어떤 오차 또는 변동입니다(또는 Unsystematic variance is variability within individuals and/or groups of individuals, and this variability is essentially random이라고 이해해도 좋습니다.). 따라서, 모형이 자료에 적합하는지(다른 말로 하면 가설이 관측자료를 잘 설명하는지) 검증하는 가장 간단한 방법은 체계적 변동을 비체계적 변동과 비교하는 것입니다.

그러한 비교는 모형/가설이 자료를 얼마나 잘 설명하는지와 모형/가설이 얼마나 잘 설명하지 못하는지(오차)를 비교하는 것에 해당됩니다.

$$
검증\ 통계량=\frac{모형이 \ 설명하는\ 변동}{모형이\ 설명하지 \ 못하는\ 변동}=\frac{효과}{오차}
$$

검정통계량은 종류가 많고, 세 가지만 들자면 $t$와 $F,\mathcal{X}^2$이 그러한 검정통계량입니다.

검정통계량은 결국 자료에 적합시킨 모형이 설명하지 못하는 변동의 양과 모형이 설명하는 변동의 양의 비(ratio)를 뜻합니다.

이 비(ratio)가 유용한 이유는 좋은 모형으로 설명할 수 있는 변동은 그것으로 설명할 수 없는 변동보다 많을 것이라는 것(그런 모형의 경우 검정통계량은 1보다 큼)입니다.

검정통계량은 그 속성이 알려진 어떤 통계량입니다. 구체적으로 말하면 검정통계량의 여러 값이 발생하는 빈도(도수)는 이미 알려져 있고, 그 도수들을 아는 덕분에 특정 값이 나올 확률도 계산할 수 있습니다.

필드와 홀은 이를 사람들이 죽는 나이에 비유해서 설명합니다.

과거의 자료에서 사망 연령의 분포를 알아낼 수 있습니다. 예를 들어 남성의 평균 사망 연령이 75세라고 하면, 사망 연령의 분포가 나이가 많은 쪽(오른 쪽)으로 쏠려 있습니다. 즉, 대부분의 사람은 50세 이상에서 죽으며, 20대에 죽는 사람은 비교적으로 드물다고 합니다. 이 경우 노년(老年) 사망의 도수는 아주 크지만 어린 나이에 사망하는 도수는 작습니다. 이러한 자료로부터 누군가가 특정 나이에 죽을 확률을 계산하는 것이 가능합니다. 

만일 어떤 사람을 무작위로 뽑아서 나이를 물었더니 53세라고 답했다고 했을 때, 우리는 그 사람이 다음 생일이 오기전에 죽을 확률을 계산할 수 있습니다.

또한, 110세 노인을 만났다면, 임의의 사람이 그렇게 오래 살 확률도 계산할 수 있습니다.

검정통계량들의 분포를 알고 있으면, 특정 검정통계량 값을 얻었을 때 그 값이 나올 확률을 계산할 수 있습니다.

예를 들어 어떤 검정통계량을 계산했는데 그 값이 110이라고 하면, 그렇게 큰 값이 나올 확률을 계산할 수 있습니다. 모형이 설명하는 변동이(설명하지 못하는 변동들에 비해) 많을수록 해당 검정 통계량이 더 커지며, 따라서 그 값들이 우연히 발생했을 가능성이 작아집니다. 간단히 말해서, 검정통계량이 클수록 그것이 발생할 확률은 작아집니다. 그 확률이 .05(피셔기준)보다 작으면, 그 검정통계량이 그런 값이 된 이유는 우리의 모형이 실세계(모집단)에서 정말로 발생하는 일들을 반영하는 변동들을 충분히 설명하기 때문이라고 확신할 수 있습니다. 그러한 검정통계량을 가리켜 **유의한(significant) 검정통계량**이라고 합니다. 

자료에 적합시킨 통계적 모형이 우리가 검증하고자 하는 가설을 반영한다고 할 때, 어떤 검정통계량이 유의하다는 것은 :  만일 모집단에 아무런 효과가 없었다면, 모형이 자료에 그렇게 잘 적합하지는 않았을(다시 말해 귀무가설이 참이 아니었을) 것이라는 뜻합니다. 그런 경우에는 귀무가설을 기각할 수 있으며, 결과적으로 대립가설이 참임을 좀 더 확신할 수 있습니다.

## 5. 2 한쪽꼬리 검정과 양쪽꼬리 검정

가설에는 방향이 있는 가설(이를테면 '이 책을 더 읽어 나갈수록 통계학을 싫어하는 마음이 더 커짐')과 방향이 없는 가설(이를테면'이 책을 더 읽어 나갈수록 통계학을 싫어하는 마음이 커지거나 작아짐')이 있습니다. 

방향이 있는 가설을 검증하는 통계적 모형을 가리켜 **한쪽꼬리 검정(one-tailed test)**이라고 하고, 방향이 없는 가설을 검증하는 모형을 가리켜 **양쪽꼬리 검정(two-tailed test)**라고 합니다.

독자가 이 책을 더 읽을수록 통계학을 싫어하는 마음이 커지는지 아니면 줄어드는지 알아본다면, 실험 연구에서는 이 책을 읽은 사람들의 그룹과 읽지 않은 사람들의 그룹을 비교해서 결론을 내릴 것이고, 상관 연구라면 이 책을 읽는 양과 통계학을 싫어하는 마음을 측정할 것입니다.

만약 방향 가설이 없다면 세 가지 가능성이 존재합니다:

1. 이 책을 읽은 사람은 일지 않은 사람보다 통계학을 더 싫어합니다. 즉, 그 차이(이 책을 읽은 사람의 그런 마음을 측정한 값의 평균에서 읽지 않은 사람의 그런 측정값의 평균을 뺀 것)가 양(positive)입니다. 상관관계로 볼 때, 독자가 이 책을 더 많이 읽을수록 독자는 통계학을 더 싫어합니다. 다른 말로 하면 독서량과 통계학을 싫어하는 마음은 양의 관계입니다.
2. 이 책을 읽는 사람은 이 책을 읽지 않은 사람보다 통계학을 싫어하는 마음이 덜합니다. 즉, 그 차이(독자의 평균 빼기 비독자의 평균)는 음입니다. 상관관계로 볼 때, 책을 더 많이 읽을수록 통계학을 더욱 좋아합니다. 이는 음의 관계입니다.
3. 독자와 비독자의 통계학에 대한 생각에는 차이가 없습니다. 즉, 독자의 평균 빼기 비독자의 평균이 정확히 0입니다. 상관관계로 볼때, 이 책을 읽는 것과 저자를 죽이고 싶어 하는 것은 무관합니다.
    
    이것이 바로 **귀무가설입니다**. 
    

검정통계량의 방향(양인지 음인지)은 차이가 양인지 음인지에 따라 결정됩니다. 양의 차이나 관계(이 책을 읽으면 통계학이 싫어진다)가 존재한다고 가정할 때, 그러한 차이를 검출하려면 독자들의 평균이 비독자들의 평균보다 크다는 사실을 고려해야됩니다(그래야 양의 검정통계량이 나옵니다). 그러나 이러한 가정이 잘못된 예측이어서 사실은 이 책을 읽을수록 통계학이 좋아진다면, 검정통계량은 음이 됩니다.

![Untitled2.png](/assets/images/posts/Statistics/2022-03-30-Statistics-Base/Untitled2.png)

이러한 논의가 뜻하는 바는 .05의 유의수준을 만족하려면 검정통계량이 10보다 큰 값이어야 하지만 실제로는 -12가 나왔다고 상상해보면, 차이가 존재하긴 하지만 그래도 가설을 기각해야됩니다. 이를 피하려면 가능한 검정통계량들의 분포에서 양 끝(즉, 두 꼬리)을 모두 봐야합니다. 이는 양의 검정통계량과 음의 검정통계량을 모두 포착한다는 뜻입니다.

하지만 여기에는 대가가 따릅니다.   .05라는 기준을 지키려면, 그 확률을 두 꼬리로 분할해야됩니다. 즉, 분포의 양의 쪽에서 .025의 확률을 적용하고 음의 쪽에서 .025의 확률을 적용해야 하는 것입니다.

위의 그림에도 그러한 상황이 나와있습니다. 분포의 양 끝에 짙게 음영진 영역은 유의수준 .025에 필요한 검정통계량들이 속한 범위입니다. 양 끝의 확률들을 결합하면(즉, 짙은 두 영역을 합치면) 애초의 기준인 0.05가 나옵니다.

이제 뭔가를 예측한 후 한 바구니에서 달걀을 꺼내서 분포의 한 쪽 끝(예측에 따라 음의 끝 또는 양의 끝)과 비교하면 됩니다.

위 그림을 보면 분포의 양 끝에 짙은 영역이 있을 뿐만 아니라, 유의한 값들의 한계를 나타내는 좀 더 큰 역역(빗금 친)이 있는데, 그 부분이 바로 두 확률을 합한 .05에 해당합니다. 이 덕분에 우연히 발생했을 확률이 .05인 검정통계량의 값을 표에서 조회할 수 있습니다. 위 그림에서 빗친 영역은 유의수준 .05를 만족하려면 양의 검정통계량보다 커야 하는 값들의 범위에 해당됩니다.

유의수준 .05 영역(빗금)의 첫 값이 유의수준 .025영역(음영)의 첫 값보다 작다는 점을 주목해야됩니다. 이는 우리가 어떤 구체적인 예측을 했을 때 유의한 결과를 얻으려면 더 작은 검정통계량이 필요하지만, 만약 그 예측의 방향이 틀렸다면 효과가 실제로 존재함을 검출하지 못하게 될 것이라는 뜻입니다.

이러한 문맥에서 기억해야 할 요점은, 토너먼트가 끝나면 내기를 걸거나 내기를 변경할 수 없다는 것입니다. 자료를 수집하기 전에 방향을 예측하지 않았다면, 방향을 예측해서 한쪽꼬리 검정의 이점을 취하기에는 이미 늦었다는 것입니다.

## 5. 3 제 1종 오류와 제2종 오류

![Untitled3.png](/assets/images/posts/Statistics/2022-03-30-Statistics-Base/Untitled3.png)

![Untitled4.png](/assets/images/posts/Statistics/2022-03-30-Statistics-Base/Untitled4.png)

(이미지 출처 : https://marginalrevolution.com/marginalrevolution/2014/05/type-i-and-type-ii-errors-simplified.html)

### 제 1 종 오류(type $\mathbf{I}$ error)

- 모집단에 효과가 진짜로 존재한다고 믿지만 사실은 모집단에 아무런 효과도 없는 입니다.
    
    플라시보 효과
    
- 피셔의 기준을 사용하면, 모집단에 효과가 존재하지 않을 때 이 오류가 생길 확률은 .05입니다.
- 이 값을 $\alpha$-수준이라고 부릅니다
- 모집단에 아무런 효과도 존재하지 않는 상황에서 자료 수집을 100회 반복한다면, 그 중 다섯 개의 표본에서는 모집단에 진짜로 효과가 존재한다고 믿게 될 정도로(실제로는 존재하지 않지만) 충분히 큰 검정통계량을 얻게 됩니다.
- $H_0$ = '메일은 스팸이 아니다', 만약 스팸 아닌 메일을 스팸으로 분류했을 경우에는 false positive가 되고, $\alpha$ error를 범하게 됩니다.

### 제 2 종 오류(type $\mathbf{II}$ error)

- 제 1 종 오류와는 반대로 모집단에 실제로 효과가 존재하지만 우리는 모집단에 아무 효과도 존재하지 않는다고 믿는 것입니다.
- 검정통계량이 작게 나오면(아마도 표본들 사이에서 자연적인 변동들이 아주 많기 때문에) 이런 오류를 겪게 됩니다.
- 코언은 제2종 오류의 허용 가능한 최대 확률로 .2(20%)를 제안합니다. 이를 $\beta$-수준이라고 합니다.
- 만일 실제로 효과가 존재하는 한 모집단에서 100개의 표본을 취했을 때 그 중 20개에서는(즉, 다섯 개 중 하나에서는) 효과가 존재하지 않는다는 잘못된 결과를 얻게 된다는 뜻입니다.
- $H_0$ = '메일은 스팸이 아니다', 만약 스팸 메일을 스팸으로 분류하지 못한 경우에는 false Negative가 되고, $\beta$ error를 범하게 됩니다.

 이 두 오류는 서로 절충 관계임이 분명합니다. 만일 효과가 진짜라고 받아들일 확률을 낮추면(즉, 알파값을 작게 하면) 실제로  존재하는 효과를 기각할 확률이 늘어납니다(효과가 진짜라고 받아들이는 기준을 엄격하게 만들었으므로). 

제1종오류와 제2종오류의 정확한 관계는 이해하기가 그렇게 쉽지 않습니다. 이는 두 오류가 서로 다른 가정에서 기초하기 때문입니다. 제 1종 오류를 범할 확률이 감소하면 제 2종 오류를 범할 확률이 높아지는 점은 확실하지만, 그 둘의 구체적인 관계는 그냥 여러 정보에 기초해서 최대한 잘 추측하는 수밖에 없습니다.

## 5. 4 효과크기

효과가 진짜인지 검증하는 틀에는 몇 가지 주의해야 할 사항이 있습니다.

1. 효과의 중요도를 고려해야됩니다. 검정통계량이 유의하다고 해서 그것이 측정하는 효과가 중요하거나 의미있다는 뜻은 아닙니다.
    
    이 문제의 해결책은 검증하고자 하는 효과의 크기를 표준화된 방식으로 측정해 보는 것입니다
    
    효과(실험적 조작이든, 변수들 사이의 관계의 강도이든)의 크기를 측정한 결과를 가리켜 효과크기(effect size)라고 합니다. 간단히 말하자면 효과의 크기는 관측된 효과가 어느정도나 큰지를 객관적이고(보통의 경우) 표준화된 방식으로 측정한 것입니다. 표준화된 측정 방법을 사용하는 덕분에, 측정하는 변수나 그 척도가 다른 여러 연구의 효과크기를 비교할 수 있습니다.(예를 들어 밀리초 단위의 속력에 기초한 효과크기를 심장 박동수에 기초한 효과크기와 비교할 수 있습니다)
    
    효과크기 측도로 흔히 쓰이는 것은 **코언의 $d$**와 **피어슨의 상관계수 $r$**, 그리고 **승산비(odds ratio)**입니다
    
    저자는 피어슨의 상관계수 r을 효과크기의 측도로 사용하길 선호함
    
    그 이유는 상관계수가 0(효과 없음)과 1(완전한 효과)사이로 제한되기 때문입니다.
    
    하지만 $d$가 더 나을 때도 있습니다
    
    예를 들어 그룹 크기들의 변동이 아주 클 때는 $d$에 비해 $r$이 상당히 편향될 수 있습니다.
    
2. 효과크기는 어떤 효과의 중요도를 객관적으로 측정한 것이라는 점에서 유용합니다.
    
    구체적으로 어떤 효과인지, 어떤 변수들을 측정했는지, 그 변수들을 어떻게 측정했는지와는 무관하게, 상관계수(효과크기의 측도로서의)가 0이라는 것은 그 효과가 존재하지 않는다는 것이고 1이라는 것은 완전한 효과가 존재한다는 뜻입니다.
    
    코언의 효과크기 분류 기준
    
    - r = .10 (작은 효과) : 이 경우 효과는 전체 변동의 1%를 설명합니다
    - r = .30 (중간 효과) : 이 경우 효과는 전체 변동의 9%를 설명합니다
    - r = .50 ( 큰 효과) : 이 경우 효과는 전체 변동의 25%를 설명합니다
    
    여기서 주의해야 될 점은, r이 선형(정비례) 척도로 측정되지는 않음을 염두에 두어야합니다.
    
    예를 들어, r = .6 인 효과의 크기가 반드시 r = .3 인 효과의 세 배인 것은 아닙니다.
    
    위의 지침들이 효과의 중요도를 평가하는 (검정통계량의 유의성과는 무관하게) 대략적인 법칙으로 유용할 수는 있지만, 이러한 '전형적인' 효과크기 분류에 의존하기보다는 해당 연구 분야의 문맥에서 효과크기를 구체적으로 평가하는 것이 바람직합니다
    
3. 효과크기를 계산할 때는 주어진 하나의 표본으로 효과크기를 계산합니다. 
    
    이는 모집단 전체의 평균(우리가 정말로 알고 싶어하는 대상)을 추론하기 위해 표본의 평균을 구하는 것과 같습니다. 우리가 정말로 알고 싶어 하는 것은 모집단에서의 효과의 크기이지만, 그 값에 직접 접근할 수는 없으므로 표본의 효과크기를 이용해서 모집단의 효과크기를 추측합니다. 
    
    또한, 모집단 효과크기를 좀 더 잘 추정하기 위해 같은 질문을 연구하는 서로 다른 여러 연구 결과의 효과크기들을 결합하기도 합니다. 이를 메타 분석(meta-analysis)라고 합니다.
    

## 5. 5 통계적 검정력

효과크기는 연구 결과의 중요도를 표현하는 데 아주 유용합니다

모집단의 효과크기는 다음 네 가지 통계적 속성들과 본질적으로 연결되어 있습니다:

1. 효과크기가 기초하는 표본의 크기
2. 효과의 통계적 유의성을 승인하는 확률 수준( 알파 수준)
3. 해당 크기의 효과를 검출하는 검정 능력
4. 효과크기는 검정이 한쪽꼬리인지 양쪽꼬리인지에도 의존

이 1-3 속성 중 둘을 알아내면 나머지 하나도 계산할 수 있습니다

통계적 검정력은 모집단에 효과가 존재한다는 가정하에서 주어진 검정이 그 효과를 검출할 확률을 뜻합니다

실제로 존재하는 효과를 검출하지 못하는 오류를 범할 확률이 제2종 오류인데,그 반대의 확률, 즉 실제로 존재하는 효과를 검출할 확률은 1-$\beta$입니다. 또한, $\beta$의 기준, 즉 실제로 존재하는 효과를 검출하지 못하는 오류를 범할 확률의 기준으로 코언이 .2를 제시합니다. 코언의 제안을 따른다면, 주어진 검정이 실제로 존재하느 효과를 검출할 확률의 기준은 1- .2 = .8 이며, 따라서 우리는 만일 효과가 정말로 존재한다면 그것을 적어도  .8 또는 80%의 확률로 검출할 수 있는 검정력을 목표로 삼아야 됩니다. 모집단의 효과크기는 표본의 효과크기로 추정할 수 있으며, 표본의 크기는 실험자가 결정합니다. 

위의 네 가지 변수의 관계를 알고 있을 때 할 수 있는 유용한 일 두 가지:

1. 검정능력을 계산함 : 실험을 마쳤다면 이미 알파 수준의 값이 정해져 있을 것입니다. 효과크기는 표본에서 구하면 되고, 실험 참가자들의 수도 이미 알고 있습니다. 따라서 그 세 가지 값으로 $\beta$, 즉 검정의 능령(검정력)을 계산할 수 있습니다. 만일 $\beta$값이 .8 이상이면, 실제로 존재하는 임의의 효과를 검출할 수 있는 능력을 갖추었다고 확신할 수 있습니다. 
    
    그러나 .8 미만이면 참가자를 좀 더 늘려서 실험을 반복함으로써 검정력을 키울 필요가 있습니다
    
2. 원하는 수준의 검정력에 필요한 표본 크기를 계산합니다: $\alpha$값과 $\beta$값을 미리 알고 있다고 하면, 우리가 실험에서 검출하고자 하는 효과의 크기는 기존 연구 결과에서 추정할 수 있습니다. 그리고 같은 실험에 관한 기존 연구가 전혀 없다고 해도, 비슷한 실험으로부터 효과크기를 어느 정도는 추정할 수 있습니다. $\alpha$값과 $\beta$값, 그리고 추정된 효과 크기로부터 그 효과를 검출하는 데 필요한 실험 참가자 수를 계산할 수 있습니다

두 용도 중 후자, 즉 원하는 검정력 수준에 필요한 참가자 수를 구하는 것이 좀 더 흔히 쓰입니다.