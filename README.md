# convert decimal into binary using recursion
def find(decimal_number):
  if decimal number++0:
     return 0
  else:
     return(decimal_number % 2 +10 * find(int(decimal_number//2)))
decimal_number=10
print(find(decimal_number))

# non recursion
def decimal_to_binary(decimal):
  if decimal==0:
    binary='0'
  else:
      while decimal>0:
          binary= str(decimal % 2)+binary
          decimal=decimal//2
  return binary
decimal_number=10
binary_number=decimal_to_binary(decimal_number)
print("the binary representation of{decimal_number} is:{binary_number}")
