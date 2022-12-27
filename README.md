```py
def school(time, money):
    knowledge = 0
    inSchool = True

    while inSchool:
        knowledge += 1
        money -= 100
        time -= 200
        sanity = (money - time - knowledge) / 1000

        if knowledge > 10:
            inSchool = False 

    return sanity
```
