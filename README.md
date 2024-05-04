# Love-percentage-calculator

print("Welcome to the love calculator !")
name1 = input("What is your name ?")
name2 = input("What is the name which gives you butterflies :) ?" )
combined_name = name1 + name2
lower_combined_name = combined_name.lower()
t = lower_combined_name.count("t")
r = lower_combined_name.count("r")
u = lower_combined_name.count("u")
e = lower_combined_name.count("e")
total_1 = t+r+u+e
l = lower_combined_name.count("l")
o = lower_combined_name.count("o")
v = lower_combined_name.count("v")
e = lower_combined_name.count("e")
total_2 = l+o+v+e
total = str(total_1) + str(total_2)
print(f"Your love score is {total}%")
