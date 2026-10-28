1. PROBLEM STATEMENT
To write a Python program to reverse the digits of a given number using loop.
Example: If number is 123 -> Reverse is 321
2. ALGORITHMjavascript1. Start
2. Input num
3. Set rev = 0
4. While num > 0:
      a. digit = num % 10
      b. rev = rev * 10 + digit
      c. num = num // 10
5. Print rev
6. Stop3. FLOWCHART
START -> INPUT num -> rev=0 -> num>0? -> YES -> digit=num%10 -> rev=rev*10+digit -> num=num//10 -> LOOP -> NO -> PRINT rev -> END

print(f"Original number: {original}")
print(f"Reversed number: {rev}")Using for loop logic (string method):pythonnum = input("Enter a number: ")
rev = num[::-1]
print(f"Reversed number: {rev}")5. SAMPLE INPUT 1javascriptEnter a number: 1234SAMPLE OUTPUT 1javascriptOriginal number: 1234
Reversed number: 43216. SAMPLE INPUT 2javascriptEnter a number: 1205SAMPLE OUTPUT 2javascriptOriginal number: 1205
Reversed number: 50217. MERMAID FLOWCHART CODE
Paste this in https://mermaid.live/ for diagram:mermaidflowchart TD
    A([START]) --> B[/Input num/]
    B --> C[rev = 0]
    C --> D{num > 0?}
    D -->|Yes| E[digit = num % 10]
    E --> F[rev = rev * 10 + digit]
    F --> G[num = num // 10]
    G --> D
    D -->|No| H[/Print rev/]
    H --> I([END])

    style A fill:#b3e5fc,stroke:#0288d1
    style B fill:#bbdefb,stroke:#1976d2
    style D fill:#ffe0b2,stroke:#ef6c00
    style H fill:#c8e6c9,stroke:#388e3c
    style I fill:#b2dfdb,stroke:#00796b
