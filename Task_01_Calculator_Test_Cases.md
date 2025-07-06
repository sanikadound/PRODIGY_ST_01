# Task 01 - Test Cases for Simple Calculator Application

## Test Case ID: TC_CALC_01
**Test Description**: Verify addition of two positive integers  
**Preconditions**: Calculator app is open  
**Test Steps**:
1. Enter 5  
2. Press +  
3. Enter 3  
4. Press =  
**Expected Result**: Output should be 8  

---

## Test Case ID: TC_CALC_02
**Test Description**: Verify subtraction of a negative and positive number  
**Preconditions**: Calculator app is open  
**Test Steps**:
1. Enter -7  
2. Press -  
3. Enter 2  
4. Press =  
**Expected Result**: Output should be -9  

---

## Test Case ID: TC_CALC_03
**Test Description**: Verify division by zero  
**Preconditions**: Calculator app is open  
**Test Steps**:
1. Enter 10  
2. Press ÷  
3. Enter 0  
4. Press =  
**Expected Result**: Show error or 'Cannot divide by zero' message  

---

## Test Case ID: TC_CALC_04
**Test Description**: Verify multiplication with decimal numbers  
**Preconditions**: Calculator app is open  
**Test Steps**:
1. Enter 2.5  
2. Press ×  
3. Enter 4.2  
4. Press =  
**Expected Result**: Output should be 10.5  

---

## Test Case ID: TC_CALC_05
**Test Description**: Verify invalid input (e.g. alphabets)  
**Preconditions**: Calculator app is open  
**Test Steps**:
1. Enter 'abc'  
2. Press +  
3. Enter 2  
4. Press =  
**Expected Result**: Show input error message  
