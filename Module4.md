# Fuzzy Inference Systems (FIS)
Fuzzy Inference Systems (FIS), also known as fuzzy rule-based systems, fuzzy models, and fuzzy expert systems, are crucial in decision-making within fuzzy logic systems. They utilize "IF ... THEN" rules, often connected by "OR" or "AND".

- **Input**: Can be fuzzy or crisp
- **Output**: Always a fuzzy set

Fuzzy Inference Systems are essential for decision-making within fuzzy logic systems. Both Mamdani and Sugeno FIS have unique methods and applications:

- **Mamdani FIS**: Focuses on fuzzy outputs and defuzzification to obtain crisp results.
- **Sugeno FIS**: Uses crisp functions in the consequents and is suitable for modeling nonlinear systems and interpolating between multiple linear models.

By fuzzifying inputs, applying rules, and defuzzifying outputs, FIS ensures effective decision-making in complex systems.

### Components of FIS
1. **Rule Base**: Contains numerous fuzzy IF-THEN rules.
2. **Database**: Defines the membership functions of fuzzy sets used in the rules.
3. **Decision-making Unit**: Operates on the rules to make decisions.
4. **Fuzzification Interface Unit**: Converts crisp quantities into fuzzy quantities.
5. **Defuzzification Interface Unit**: Converts fuzzy quantities back into crisp quantities.

### Construction and Working Principle
1. **Fuzzification**: Converts crisp input to fuzzy input using various methods.
2. **Rule Base Formation**: Using the database, fuzzy rules are established.
3. **Decision-making**: Operations on rules to make decisions.
4. **Defuzzification**: Produces a crisp output from fuzzy quantities.

### Methods of FIS
1. **Mamdani FIS (1975)**
2. **Sugeno FIS (1985)**

---

## Mamdani FIS
Proposed by Ebrahim Mamdani in 1975, Mamdani FIS was initially used for controlling a steam engine and boiler combination.

### Key Characteristics
- Output membership functions are fuzzy sets.
- Defuzzification is crucial to obtain a crisp output.

### Steps in Mamdani FIS
1. **Determine a set of fuzzy rules**.
2. **Fuzzify inputs** using input membership functions.
3. **Combine inputs** according to fuzzy rules to establish rule strength.
4. **Determine the consequent** by combining rule strength and output membership function.
5. **Combine all consequents** to get an output distribution.
6. **Defuzzify the output distribution** to obtain a crisp output.

### Rule Formation
- Uses "IF-THEN" statements and "AND/OR" connectives.
- Consequent of the rule:
  - Compute rule strength using fuzzified inputs.
  - Clip the output membership function at the rule strength.

### Defuzzification Techniques
- Center of Mass
- Mean of Maximum

---

## Sugeno FIS
Proposed by Takagi, Sugeno, and Kang in 1985, the Sugeno FIS uses fuzzy rules in the format: IF x is A and y is B THEN z = f(x,y).

### Key Characteristics
- **Antecedents**: Fuzzy sets (A, B).
- **Consequent**: Crisp function (z = f(x, y)).

### Steps in Sugeno FIS
1. **Fuzzify the inputs**.
2. **Apply the fuzzy operator**.

### Applications
- **Interpolating Supervisor**: Suitable for smooth interpolation of linear gains across the input space.
- **Modeling Nonlinear Systems**: Interpolates between multiple linear models.

### Adaptive Techniques
- Used for constructing fuzzy models.
- Customize membership functions.

---

