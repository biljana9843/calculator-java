file Calculator:
loc: 134
ciklomatska slozenost: 57
kognitivna slozenost: 24
metode evaluateExpression i Calculate su predugacke
citljivost je losa
izračunate indekse indexMultiply i indexDivide treba cuvati u promenljivim izvan if-a
line 4: public class Calculator - ovo je podrazumevani javni konstruktor
line 18: ispraviti String ToString() sa: String Calculator.Operations.ToString()
line 24: ispraviti String Run(String expression) sa: String Calculator.Run(String expression)
line 74: ispraviti void Calculate(List<Float> numbers, List<String> operations) 
        sa: void Calculator.Calculate(List<Float> numbers, List<String> operations)

file Start:
loc: 19
ciklomatska slozenost: 4
kognitivna slozenost: 4
line 6:  String Expression; promenljiva treba da pocinje malim slovom
Scanner treba zatvoriti izvan petlje
line 19: nije importovana klasa Calculator
