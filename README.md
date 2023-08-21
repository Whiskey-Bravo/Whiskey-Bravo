```pyclass Life:
    def __init__(self, name: str) -> None:
        self.name = name
        self.rizz = float("inf")
        self.bitches = float("inf")
        self.health = 100
        self.money = 0
        self.knowledge = 69

    def school(self) -> None:
        """School is shit

        Returns:
            None: none besides a bit of knowledge 
        """

        self.health -= 10
        self.money -= 10
        self.knowledge += 1

        return None
    
ziagl = Life("Ziagl")

while True:
    ziagl.school()
    
print("Finally eternal happiness") # unreachable
```
