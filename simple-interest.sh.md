```bash
#!/bin/bash

# Simple Interest Calculator

echo "Simple Interest Calculator"
echo "--------------------------"

read -p "Enter the principal amount: " principal
read -p "Enter the interest rate (%): " rate
read -p "Enter the time period (years): " time

# Calculate simple interest
interest=$(echo "scale=2; $principal * $rate * $time / 100" | bc)

# Calculate total amount
total=$(echo "scale=2; $principal + $interest" | bc)

echo ""
echo "Simple Interest: $interest"
echo "Total Amount: $total"
```