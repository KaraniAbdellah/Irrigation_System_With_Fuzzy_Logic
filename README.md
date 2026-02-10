# Smart Irrigation System with Fuzzy Logic

## Introduction:
During my AI studies I discovered that to build intelligent programs we have the "old way" using Propositional Logic, Predicate Logic, and Fuzzy Logic, as well as Machine Learning where we let the machine learn from data.

I really like Fuzzy Logic because it is smarter than Propositional or Predicate Logic; it represents linguistic variables (such as Hard, Easy, Good, or Bad). It also represents uncertainty, because the human brain does not work in a purely numerical way but rather through language.

The problem with Propositional and Predicate Logic is that they cannot represent uncertainty. For example if we say a person has a fever if their temperature is higher than 38°C, these logics would say that a person with a temperature of 37.99°C is not sick. **This is where Fuzzy Logic makes a difference:** it uses intervals.
We can say a person is **"80% sick"** and **"20% not sick."** In the real world there is always uncertainty.

## What I Do in THis Project:
In this project, I developed a Smart Irrigation System that predicts the exact amount of water a plant needs based on environmental factors. The system processes three key input features: Air Humidity, Temperature, and Soil Moisture.

**Methodology: Fuzzy Logic Implementation**
To build this system, I utilized Fuzzy Logic principles (defined in doc.py). The core of the system relies on the following concepts:
Universe of Discourse: This defines the full range of possible values for a variable. For example, the Universe of Discourse for temperature might be set from -100°C to 100°C.

**Linguistic Variables & Values**: While "Temperature" is the variable, it is expressed through linguistic values such as Cold, Cool, Warm, or Hot.
**Membership Functions (Dealing with Uncertainty)**: Unlike Predicate Logic, which uses strict "True/False" boundaries, this system uses overlapping intervals.
**Example**: We don't just say "Cool" is exactly between 20°C and 30°C. Instead, we define a range (e.g., 15°C to 25°C) where the temperature is "partially cool." This allows the system to handle the uncertainty of the real world, ensuring a smooth transition between states rather than a sudden jump.

**NOTE: you can find all technical documentation in doc.py**






