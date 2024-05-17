import random

class Soldier:

def _init_(self, name, health, attack_power):

self.name name

self.health

health

self.attack_power attack power

def attack(self, enemy):

damage random.randint(1, self.attack_power)

enemy.health damage

print(f"(self.name} attacked (enemy.name} and dealt {damag

class Enemy:

def_init__(self, name, health, attack_power):

self.name name

self.health health

self.attack_power attack_power

def attack(self, soldier):

damage random.randint(1, self.attack_power)

soldier.health -= damage

print(f"(self.name} attacked (soldier.name} and dealt (dam

5 def main():

soldier - Soldier("Player", 100, 20)

enemy Enemy("Enemy", 100, 15)

while soldier.health > 0 and enemy.health > 0:

soldier.attack(enemy)

enemy.attack(soldier)

print(f"(soldier.name} health: (soldier.health)")

print(f"(enemy.name) health: (enemy.health}")

print()

if soldier.health <= 0:

print("Game over. You lost.")

else:

print("Congratulations! You won the game.")

if name="main":

main()
