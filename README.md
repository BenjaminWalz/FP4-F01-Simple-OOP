# FP4-F01-Simple-OOP
Intro to OOP



#main class, what sub classes pull from
class roll:
    
    def __init__(self, name, ability, health):
        self.name = name
        self.ability = ability
        self.health = health
        
        
     #each sub class here takes roll atributes and adds each own to make each class unique
     #meant to be based on game chareters 
class mage(roll):
    def __init__(self, name, ability, mana, health):
        super().__init__(name, ability, health)
        self.mana = mana

class heavy(roll):
    def __init__(self, name, ability, armour, health):
        super().__init__(name, ability, health)
        self.armour = armour

class sniper(roll):
    def __init__(self, name, ability, ammo, health):
        super().__init__(name, ability, health)
        self.ammo = ammo





