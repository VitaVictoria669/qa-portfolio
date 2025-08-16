### Test Case 1: Calculate sum of two positive integers

**Priority:** P0  
**Created by:** Viktoriia Masanovets  
**Updated by:** Viktoriia Masanovets  
**Assignee:** Viktoriia Masanovets  
**Created on:** 07-29-2025  
**Updated on:** 07-30-2025  

**Precondition:**  
Open the link: [Calculator app](https://calculator.students.hillel.it/)

**Test Steps:**

| № | Step                                     | Expected Result                               |
|---|------------------------------------------|-----------------------------------------------|
| 1 | Enter integer 99 in the top input field  | Value is entered                              |
| 2 | Enter integer 99 in the bottom input field | Value is entered                             |
| 3 | Click the "Add" button                    | The correct sum of the entered numbers is displayed (198) |


### Test Case 2: The “Add” button adds valid integers

**Priority:** P0  
**Created by:** Viktoriia Masanovets  
**Updated by:** Viktoriia Masanovets  
**Assignee:** Viktoriia Masanovets  
**Created on:** 07-29-2025  
**Updated on:** 07-30-2025  

**Precondition:**  
Open the link: [Calculator app](https://calculator.students.hillel.it/)

**Test Steps:**

| № | Step                                     | Expected Result                               |
|---|------------------------------------------|-----------------------------------------------|
| 1 | Enter integer 99 in the top input field  | Value is entered                              |
| 2 | Enter integer -99 in the bottom input field | Value is entered                             |
| 3 | Click the "Add" button                    | The correct sum of the entered numbers is displayed (0) |


### Test Case 3: The “Clear” button clears the filled fields

**Priority:** P1  
**Created by:** Viktoriia Masanovets  
**Updated by:** Viktoriia Masanovets  
**Assignee:** Viktoriia Masanovets  
**Created on:** 07-29-2025  
**Updated on:** 07-30-2025  

**Precondition:**  
Open the link: [Calculator app](https://calculator.students.hillel.it/)

**Test Steps:**

| № | Step                                     | Expected Result                               |
|---|------------------------------------------|-----------------------------------------------|
| 1 | Enter a number in the range -99 to 99 in the top input field | Value is entered |
| 2 | Enter a number in the range -99 to 99 in the bottom input field | Value is entered |
| 3 | Click the "Add" button                    | The correct sum of the entered numbers is displayed |
| 4 | Click the "Clear" button                  | All fields (top, bottom, and sum) are cleared |
| 5 | Click the "Add" button                    | Error message appears: "Please input an Integer between -99 and 99 only." |


### Test Case 4: The “Random” button generates random numbers in the range from -99 to 99

**Priority:** P1  
**Created by:** Viktoriia Masanovets  
**Updated by:** Viktoriia Masanovets  
**Assignee:** Viktoriia Masanovets  
**Created on:** 07-29-2025  
**Updated on:** 07-30-2025  

**Precondition:**  
Open the link: [Calculator app](https://calculator.students.hillel.it/)

**Test Steps:**

| № | Step                                     | Expected Result                               |
|---|------------------------------------------|-----------------------------------------------|
| 1 | Click the "Random" button multiple times | Each time the "Random" button is clicked, new valid integers within the range -99 to 99 should appear in the top and bottom input fields |


### Test Case 5: The “Rows Up/Down” buttons increase or decrease the entered value by 1

**Priority:** P0  
**Created by:** Viktoriia Masanovets  
**Updated by:** Viktoriia Masanovets  
**Assignee:** Viktoriia Masanovets  
**Created on:** 07-29-2025  
**Updated on:** 07-30-2025  

**Precondition:**  
Open the link: [Calculator app](https://calculator.students.hillel.it/)

**Test Steps:**

| № | Step                                     | Expected Result                               |
|---|------------------------------------------|-----------------------------------------------|
| 1 | Enter integer 99 in the top input field  | Value is entered                              |
| 2 | Click the "Rows Up" button               | The value does not change and remains 99      |
| 3 | Enter integer -99 in the top input field | Value is entered                              |
| 4 | Click the "Rows Down" button             | The value does not change and remains -99     |
| 5 | Enter integer 99 in the bottom input field | Value is entered                             |
| 6 | Click the "Rows Up" button               | The value does not change and remains 99      |
| 7 | Enter integer -99 in the bottom input field | Value is entered                             |
| 8 | Click the "Rows Down" button             | The value does not change and remains -99     |
