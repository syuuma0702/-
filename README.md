# -import random
x = [random.randint(1, 37) for p in range(0, 7)]
print(x)
x = list(map(int, input(x).split(x)))
 
sorted(x)
予想方法
１～３７の番号の中から７つ数字をランダムに取り出してその７つの数字を小さい順番に並べた
