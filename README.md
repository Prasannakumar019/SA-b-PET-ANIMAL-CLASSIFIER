# SA-b-PET-ANIMAL-CLASSIFIER

# Algorithm
1.Import necessary packages.

2.Read the dataset and normalize the data.

3.Form the CNN model using the necessary layers and filters.

4.Train the model using the training dataset.

5.Evalute the model using the test data.

6.Test the model upon various new images of dogs and cats.
## Program:
```
/*
Program to implement 
Developed by   :Prasannakumar M
RegisterNumber :212220230035  
```
```python
class Pet(object):

    def __init__(self, animal='', color='', food='', noise='', name=''):

        self.Animal = animal
        self.Color = color
        self.Food = food
        self.Noise = noise
        self.Name = name


Pet1 = Pet('Cat', 'Orange', 'Kibble Bits', 'Purr', 'Toby')
Pet2 = Pet('Dog', 'black', 'Steak', 'Bark', 'Elvis')
Pet3 = Pet('Cat', 'Black', 'Kibble Bits', 'Hiss', 'Salem')
Pet4 = Pet ('Salammander', 'White', 'Insects', 'Hiss', 'Gertrude')
Pet5 = Pet('Pig', 'Pink', 'Feed', 'Oink', 'WiLbur')

petList = [Pet1, Pet2, Pet3, Pet4, Pet5]

def print_attributes(objList):

    for obj in objList:

        for attr in obj.__dict__:

            print(attr, getattr(obj, attr))

print_attributes(petList)
```

## OUTPUT:


1. CODE :
![image](https://user-images.githubusercontent.com/75235090/172654411-d02d066d-ddc7-4e9e-9d52-cb53549572e1.png)




2. DEMO VIDEO YOUTUBE LINK:
https://www.youtube.com/watch?v=RQqlgkkX8ho

