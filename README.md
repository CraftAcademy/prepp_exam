## Preparatory course exam challenge

### Format
Online. Please share the screen you will be working on. Keep sharing your screen at all time throughout the exam. 

### Time
60 minutes from start. There will be a timer visible on the screen schared by your coach. If you want to keep track of the time yoursef, visit https://marinaratimer.com/coding_timer

### Delivery
At the end of the exam, you need to submit a link to your GitHub repository with the solution. Please note that you can not push any commits to your repository after the exam has ended. 

### Challenge
**BMI Calculator Formula**
For nearly 200 years now, medical professionals the world over have used the universally accepted Body Mass Index (BMI) to help assess the overall state of a person’s health.

Experts have identified a flaw in the basic BMI formula and have recently come up with a new calculation which presents a more realistic result as it scales more accurately in relation to a person’s height.

**Old forula**

The way we have calculated the BMI value before was:

  _weight(kg)/(height(m) * height(m))_

it can also be written like this:

  _weight(kg)/height(m)<sup>2</sup>_

"Weight in kilograms divided by height in meters to the power of two" (Swedish: "upphöjt till 2")

**New formula**

The new way of calculating BMI is:

  _1.3 x weight(kg)/height(m)2.5<sup>2.5</sup>_

"one point three times weight in kilograms divided by height in meters to the power of two and a half" (Swedish: "upphöjt till 2.5")

**Your challenge will be to return to your BMI Challenge that you worked on in the preparatory course, and modify the way your application calculates the bmi value. Remember to update your tests.**

**Hints**

In JavaScript, you can make use of `Math.pow()` to calculate power of. This method returns the value of x to the power of y (x<sup>y</sup>).

```
1.86 * 1.86 = 3.4596000000000005
Math.pow(1.86, 2) = = 3.4596000000000005
```

## Good luck!
