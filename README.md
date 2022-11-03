# -
Распределение процентных ставок по вкладам в различных банках таким образом, что ключ — название банка, значение — процент
Программа, в результате которой будет сформирован список deposit значений.

money = int(input('Введите сумму депозита'))
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
dep_tkb = (per_cent['ТКБ'] * money / 100)
dep_ckb = (per_cent['СКБ'] * money / 100)
dep_vtb = (per_cent['ВТБ'] * money / 100)
dep_sber = (per_cent['СБЕР'] * money / 100)
deposit = [int(dep_tkb), int(dep_ckb), int(dep_vtb), int(dep_sber)]
print(deposit[ : ])
print("deposit", "=", deposit[ : ])
max(deposit)
print("Максимальная сумма, которую вы можете заработать", "—", max(deposit))
