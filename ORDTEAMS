for i in range(int(input())):
    j = [list(map(int,input().split())) for sc in range(3)]
    j.sort()
    for b in range(2):
        if j[b][0] <= j[b + 1][0] and j[b][1] <= j[b + 1][1] and j[b][2] <= j[b + 1][2] and sum(j[b]) < sum(j[b + 1]):
            continue
        print('no')
        break
    else:
        print('yes')
