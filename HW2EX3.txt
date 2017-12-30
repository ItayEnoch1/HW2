def fibonacci(n):
    num = n
    u0 = 0
    u1 = 1
    print(u0)
    print(u1)
    for i in range(2, n):
        u0 += u1
        print(u0)
        u1 += u0
        print(u1)