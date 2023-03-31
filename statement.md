# This is a simple Python code to get you started with your projects

# Import any necessary libraries here
import random

# Define any functions or classes here
``
class MyClass:
    def __init__(self, name):
        self.name = name
    
    def greet(self):
        print(f"Hello, {self.name}!")
``
# Write the main code here
def main():
    # Example usage of the MyClass class
    obj = MyClass("John")
    obj.greet()

    # Example usage of the random module
    print(random.randint(1, 10))

if __name__ == "__main__":
    main()
