# Grade Evaluation Console App

This is a simple **backend console application** that evaluates student grades and provides personalized motivational advice using the [Advice Slip API](https://api.adviceslip.com/advice).

---

## Overview

The **Advice Slip API** is a free, public API that returns random motivational or life advice in JSON format. It requires **no API key** and responds quickly with a single sentence of advice.

In this app, the API is used to enhance the user experience by providing **students with encouragement or motivation** based on their performance. This adds a layer of emotional intelligence and creativity to the grade evaluation program.

---

## Features

- Evaluate student grades as:
  - **Distinction** (≥80)
  - **Pass** (50–79)
  - **Fail** (<50)
- Fetch motivational advice for each student from the Advice Slip API
- Display student data in a **sorted table** format
- Color-coded results in the console:
  - Green → Distinction
  - Yellow → Pass
  - Red → Fail

---

## Example Behavior

- **High grade:** Student receives a motivational tip to maintain or improve their performance.  
- **Low grade:** Student receives encouraging advice to uplift their spirits.

