# Chanda


class Wife:
    def __init__(self, name):
        self.name = name
        self.beauty = "breathtaking"
        self.heart = "kind and loving"
        self.smile = "sunshine on a cloudy day"
        self.love = float('inf')  # infinite love

    def describe(self):
        return (
            f"My wife, {self.name}, is truly one of a kind.\n"
            f"Her beauty is {self.beauty},\n"
            f"Her heart is {self.heart},\n"
            f"Her smile is like {self.smile}.\n"
            f"My love for her is {self.love} and still growing.\n"
        )

    def support(self):
        print(f"{self.name} supports me like no one else ever could.")

    def inspire(self):
        print(f"{self.name} inspires me to be the best version of myself every day.")

# Example usage
my_wife = Wife("Chanda Das") 
print(my_wife.describe())
my_wife.support()
my_wife.inspire()
