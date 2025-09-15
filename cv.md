[rsschool-cv](https://github.com/rolling-scopes-school/tasks/blob/master/tasks/cv/en/cv.md#cv-contents)
---
## **Finsky Pavel**
## **Contact info**
- **Phone:** +375291041395

- **Email:** finsky201222@gmail.com

- **Telegram:** @mariiuyo

- **GitHub:** [finyso](https://github.com/finyso)

## **About me**
#### Motivated and detail-oriented Computer Science student at seeking an internship as a Junior Frontend developer. Eager to apply my programming skills and knowledge in a real-world environmant while contributing to innovative projects. 

## **Skills**
- C/C++(basic), C#(basic), Python(basic)

- QT Framework(basic)

- Assembler(basic)

- OC Windows, Linux(Ubuntu)

- Tools:  VS Code, Git

## **Education**
### **2024-present**
#### B.Sc in Informatics and Technology of Programming, BSUIR, Minsk, Belarus
- GPA:8.5/10

- Course project: Sort and search visualizer on QT

## **Code**
```#include <cmath>

bool narcissistic( int value ){
  int original = value;
  int num_digits = 0;
  int temp = value;
  
  while(temp > 0){
    num_digits++;
    temp /= 10;
  }
  
  int sum = 0;
  temp = value;
  
  while(temp > 0){
    int digit = temp % 10;
    sum += std::pow(digit, num_digits);
    temp /= 10;
  }
  
  return sum == original;
}
```

## **Experience**
- Completed an *Basic of Algorithmization and Programming in C++* on Stepik

- Completed an *Introductory course in Pythton* on Stepik 

- Member of ICPC 2024

## **Languages**
- Russian(native)
- Belorussian(native)
- English(A2)