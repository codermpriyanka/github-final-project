# github-final-project

Where:

Principal = Amount of money
Rate = Interest rate per year (%)
Time = Time in years
Features
User can enter:
Principal
Rate
Time
Click on Calculate button
Instantly shows Simple Interest
Simple and beginner-friendly code
Files Used
index.html – Structure of the page
style.css – Styling of the page
script.js – Logic for calculation
How It Works
User enters values in input fields
Clicks on Calculate
JavaScript reads the values
Converts them to numbers
Applies formula
Displays result in the page
JavaScript Logic
let prinicipal = document.getElementById("prinicipal");
let rate = document.getElementById("rate");
let time = document.getElementById("time");
let ans = document.getElementById("ans");

function calculate() {
  let p = Number(prinicipal.value);
  let r = Number(rate.value);
  let t = Number(time.value);
  let ansss = (p * r * t) / 100;
  ans.innerHTML = ansss;
}
