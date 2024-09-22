def lcm(a, b):
  """
  Calculates the Least Common Multiple (LCM) of two numbers.

  Args:
    a: The first number.
    b: The second number.

  Returns:
    The LCM of the two numbers.
  """
  # Find the greater number
  greater = max(a, b)

  while True:
    if greater % a == 0 and greater % b == 0:
      lcm = greater
      break
    greater += 1

  return lcm

# Get the numbers from the user
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

# Calculate the LCM
lcm_result = lcm(num1, num2)

# Print the result
print(f"The LCM of {num1} and {num2} is {lcm_result}")