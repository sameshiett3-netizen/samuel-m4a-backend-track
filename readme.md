# M4A Backend Assignment - Environment Setup & CLI

## 1. Environment Setup
- Configured custom green Bash prompt in `~/.bashrc`.
- Built structured dev-workspace in `~/m4ace/backend_track/`.

## 2. Command Line Mastery
- Created `setup_project_m4a.sh` to automate folder structures (src, config, controllers, models, routes).
- Used `grep` to search for patterns in text files.
- Managed file permissions with `chmod`.

## 3. Pseudocode Practice
### Finding the Largest Number
```text
BEGIN
    SET 'largest' to first number in list
    FOR each number:
        IF current > 'largest' THEN SET 'largest' to current
    DISPLAY 'largest'
END 
```
### Palindrome Checker
```text
BEGIN
    READ input word from user
    SET 'reversed_word' to the reverse of the input word
    IF input word matches 'reversed_word' (ignoring case):
        DISPLAY "The word is a palindrome"
    ELSE:
        DISPLAY "The word is not a palindrome"
END
```