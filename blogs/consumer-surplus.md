---
layout: page
permalink: /blogs/consumer-surplus
title: web
---

# 关于消费者剩余的刻画
> 有时需要刻画一些新策略对消费者剩余(consumer-surplus, CS)的影响，如产品的绿色程度、相应企业的社会责任等。传统经济学中关于CS的刻画主要是产品价格。
<br>![Economic-surpluses.svg](consumer-surplus.assets/Economic-surpluses.svg)

## 关于消费者剩余的刻画
假设消费者数量为 $n$。消费者 $u_i=w_i-\alpha p+\beta e$，其中 $p$为价格， $e$为商品的绿色度，且 $w_i~U[0,w_H]$。对于消费者 $i$而言，当 $u_i>0$时，会购买。即 $w_i>\alpha p-\beta e$，那么需求函数为 $q=n\int_(\alpha p-\beta e)^(w_H) f(w) dw=n(w_H-\alpha p-\beta e)/w_H $。转换为 $p=w_H/\alpha -w_H/(n\αlpha) q+\beta/\alpha e$，
将上述系数{w_H/α,-w_H/nα,β/α}改写为{a,-1,b}，即w_H/α=a，-w_H/nα=-b， β/α=c
p=a-bq+c(e+μ)
消费者剩余为CS=∫_0^(w_H)▒〖max⁡{u_i,0} f(w)dw〗=∫_(αp-βe)^(w_H)▒(w-αp+βe)f(w)dw=(w_H-pα-eβ)(w_H-pα+3eβ)/(2w_H )=(w_H/α-p-eβ/α)(w_H/α-p+3eβ/α)/((2w_H)/α)=(a-p-ce)(a-p+3ce)/2a
