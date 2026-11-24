#from statistics import median, mode

# Function 1: Calculate the sum
def calculate_sum(numbers):
    return sum(numbers)


# Function 2: Calculate the average
def calculate_average(numbers):
    return sum(numbers) / len(numbers)


# Function 3: Calculate median and mode
def calculate_median_mode(numbers):
    med = median(numbers)
    mod = mode(numbers)
    return med, mod


# List of numbers
numbers = [2, 4, 4, 6, 8, 10, 12]

# Display results
print("Sum:", calculate_sum(numbers))
print("Average:", calculate_average(numbers))

med, mod = calculate_median_mode(numbers)

print("Median:", med)
print("Mode:", mod)