# unique-number-array-builder

This LabVIEW program lets you type unique numbers into a list. Here's how it stands out:
- It only adds a number if it's not already there.
- It stops when you have added ten different numbers or you hit the STOP button.
- It shows the sorted array, the smallest and biggest numbers.

How does it work?
- It uses the shift register to keep track of the list and update it.
- It uses Search 1D Array to check if a number is already in the list.
- The loop stops when the list is full or you can press the STOP button.


<img width="754" height="422" alt="Front panel (unique-number-array-builder)" src="https://github.com/user-attachments/assets/0249dd37-3cd5-43df-8a8d-eaf16781a8f1" />
<img width="824" height="302" alt="Block diagram (unique-number-array-builder)" src="https://github.com/user-attachments/assets/0262f87c-b091-47e9-961d-8b15d57400b8" />

Requirements:
- LabVIEW (2020-present)

