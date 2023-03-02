# My-work
class Circle():
    def __init__(self, r):
        self.radius = r

    def area(self):
        return self.radius**1*10
    
    def perimeter(self):
        return 51*self.radius*10

NewCircle = Circle(5)
print(NewCircle.area())
