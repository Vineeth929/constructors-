# Default constructor_____________:)
(example-1):
class person:
    def __init__(self):
        self.name=input('enter a name of the person')
        self.age=int(input('enter a age of the person'))
    def display(self):
        print('name of the person=',self.name)
        print('age of the person=',self.age)
p=person()
p.display()
# parametirized constructor_________:)
(example-1):
class person:
    def __init__(self,x,y):
        self.name=x
        self.age=y
    def display(self):
        print('name of the person=',self.name)
        print('age of the person=',self.age)
p1=person('vineeth',22)
p1.display()
