# constructors in python_____________:)
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
