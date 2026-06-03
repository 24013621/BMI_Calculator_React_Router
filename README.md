# Ex06 BMI Calculator
## Date: 29-05-26
# NAME: AHAMED JASEER SHA E
# REGISTER NUMBER: 212224040015
## AIM
To create a BMI calculator using React Router 

## ALGORITHM
### STEP 1 State Initialization
Manage the current page (Home or Calculator) using React Router.

### STEP 2 User Input
Accept weight and height inputs from the user.

### STEP 3 BMI Calculation
Calculate the BMI based on user input.

### STEP 4 Categorization
Classify the BMI result into categories (Underweight, Normal weight, Overweight, Obesity).

### STEP 5 Navigation
Navigate between pages using React Router.

## PROGRAM

### App.jsx
```
import React from "react";
import { Routes, Route, Link } from "react-router-dom";
import Home from "./components/Home.jsx";

        <div className="buttons">
          <button className="btn calculate" onClick={calculateBMI}>
            Calculate
          </button>
          <button className="btn reset" onClick={reset}>
            Reset
          </button>
        </div>

        {bmi && (
          <div className="result fade-in">
            <h2>Your BMI: {bmi}</h2>
            <p className={`category ${category.toLowerCase().replace(" ", "-")}`}>
              {category}
            </p>
          </div>
        )}
      </div>
      <p className="footer">Designed by Austin 🤍</p>
    </div>
  );
}

export default BMICalculator;
```

### Home.jsx:
```
import React from "react";
import { Link } from "react-router-dom";

function Home() {
  return (
    <div className="landing">
      <div className="hero">
        <h1 className="hero-title">Track Your Health Easily</h1>
        <p className="hero-subtitle">
          Calculate your BMI instantly and understand your health category.
        </p>
        <Link to="/calculator">
          <button className="btn primary">Start Calculating</button>
        </Link>
      </div>
      <p className="footer">Designed by Austin 🤍</p>
    </div>
  );
}

export default Home;
```


## OUTPUT
<img width="1264" height="595" alt="image" src="https://github.com/user-attachments/assets/cc92a442-e974-41d2-8044-4afbb66ccb55" />

<img width="1265" height="597" alt="image" src="https://github.com/user-attachments/assets/aa96a487-a76f-40ae-bb4d-3933ffd4ef0f" />

<img width="1267" height="600" alt="image" src="https://github.com/user-attachments/assets/21ed26a1-3135-4781-8e64-b22a86a4e1e5" />

<img width="1264" height="471" alt="image" src="https://github.com/user-attachments/assets/d4f3ccc9-ec7f-4155-9697-9929e91ef7a2" />

## RESULT
The program for creating BMI Calculator using React Router is executed successfully.

