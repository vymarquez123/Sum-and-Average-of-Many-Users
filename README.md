# Sum-and-Average-of-Many-Users
sum = 0.0
nocount = 0

while True:
  number = float(input("Enter the number : "))
  sum += number
  nocount += 1

  choice = input("Add another number ? (y/n) : ")
  if choice.casefold() == 'n':
    break

average = sum / nocount
print()
print()

print(f"sum : {sum}")
print(f"average : {average}")
