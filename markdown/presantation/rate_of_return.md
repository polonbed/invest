### Доходность

Доходность по методу Дитца:

Введем обозначения:
- $R$ - доходность портфеля в процентах 
- $S_e$ - это стоимость портфеля на конец периода 
- $S_b$ - это стоимость портфеля на начало периода
- $S_a$ - ополнение счета
- $S_w$ - снятие со счета
- $W_t$ - временной весовой коэффициент, который применяется к каждому денежному потоку в портфеле
- $T$ - длительность отчетного периода в днях, за который считается доходность
- $t$ - количество дней с начала инвестирования

$$
W_t = \dfrac{T-t}{T}
$$

$$
R = \dfrac{S_e-S_b-\sum S_a+\sum S_w}{S_b+\sum(S_aW_t)-\sum(S_wW_t)}
$$