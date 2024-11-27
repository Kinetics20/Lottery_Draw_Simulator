# Lottery Draw Simulator

## Description  
This project is a simple Python program that simulates a lottery game. You can choose between two types of lottery draws:  
- **Mini Lotto Draw** (5 numbers)  
- **Lotto Draw** (6 numbers)  

The program allows you to input your chosen numbers, validates them, and compares them with randomly drawn numbers. It also displays your hits, if any.

## How It Works  
1. **Game Selection**:  
   - The user selects the game type:  
     - `5` for Mini Lotto (5 numbers).  
     - `6` for Lotto (6 numbers).  
2. **Input Numbers**:  
   - Enter your chosen numbers, separated by commas.  
   - The program ensures the numbers are:  
     - Within the range of 1-49.  
     - Unique (no duplicates).  
3. **Draw Numbers**:  
   - The program randomly selects 5 or 6 numbers (depending on the game type) from the range 1-49.  
4. **Results**:  
   - The program checks and displays how many of your numbers match the drawn numbers.  

## Example Usage  
```bash
choose game type [5-Mini Lotto draw, 6-Lotto draw] 5
Enter 5 digits separated by comma:
1, 2, 3, 4, 5
Hits: 2. Your digits: 3, 5.
```

## Requirements
- **Python 3.8 or higher.**

## How to Run  
1. Clone the repository.  
2. Run the script using:  
   ```bash
   python lottery_simulator.py
   ```
3. Follow the prompts in the terminal to play the game.

## Notes  
- The numbers must be within the range of 1-49.  
- Duplicate numbers are not allowed.  
- If no hits occur, the program encourages you to try again! 😊