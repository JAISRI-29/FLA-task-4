# FLA-task-4
# Finite Automata for Real-Time Input Validation

## CLA-2 Assignment - Task 2

### Project Description
This project demonstrates the application of Finite Automata for real-time input validation.

It uses Deterministic Finite Automata (DFA) and Non-Deterministic Finite Automata (NFA) to validate different types of user inputs.

### Applications

1. PIN Validation
   - Validates a 4-digit PIN.
   - Rejects invalid characters and incorrect lengths.

2. Card Lock Validation
   - Tracks consecutive incorrect PIN attempts.
   - Locks the card after three consecutive wrong attempts.

3. Password Validation
   - Minimum length: 8 characters.
   - Maximum length: 12 characters.
   - Requires uppercase letters.
   - Requires lowercase letters.
   - Requires at least one digit.
   - Rejects whitespace.

4. Email Validation
   - Uses NFA and subset construction.
   - Validates email format.

### Automata Concepts Used

- Deterministic Finite Automata (DFA)
- Non-Deterministic Finite Automata (NFA)
- Subset Construction
- Product Construction
- DFA Minimisation
- State Transition Tracing

### Technologies Used

- Python 3
- Regular Expressions
- GitHub

### How to Run

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Open the project folder:

```bash
cd finite-automata-validators
```

Run PIN validation:

```bash
python3 fa_validators.py pin 4821
```

Run card lock validation:

```bash
python3 fa_validators.py lock WWC
```

Run password validation:

```bash
python3 fa_validators.py password Srm2026abc
```

Run email validation:

```bash
python3 fa_validators.py email a@b.co
```

Run test cases:

```bash
python3 fa_validators.py tests
```

### Expected Output

The program displays:
- Input characters
- Current state
- Transition details
- Final state
- ACCEPTED or REJECTED result

### Conclusion

This project demonstrates how finite automata can be used to validate real-time inputs through state transitions and acceptance conditions.
