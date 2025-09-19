// =============================
// 🎯 Part 1: Variables & Conditionals
// =============================

// Selecting elements
const ageInput = document.getElementById("ageInput");
const checkAgeBtn = document.getElementById("checkAgeBtn");
const ageResult = document.getElementById("ageResult");

// Event listener for age check
checkAgeBtn.addEventListener("click", () => {
  let age = Number(ageInput.value); // Variable declaration
  if (age >= 18) {
    ageResult.textContent = "✅ You are eligible to vote!";
  } else if (age > 0) {
    ageResult.textContent = "❌ You are too young to vote.";
  } else {
    ageResult.textContent = "⚠️ Please enter a valid age.";
  }
});


// =============================
// ❤️ Part 2: Functions
// =============================

// Function 1: Calculate total price
function calculateTotal(prices) {
  let total = 0;
  for (let price of prices) {
    total += price;
  }
  return total;
}

// Function 2: Format string (capitalize)
function capitalize(str) {
  return str.charAt(0).toUpperCase() + str.slice(1);
}

// Using functions with button
const calcTotalBtn = document.getElementById("calcTotalBtn");
const cartResult = document.getElementById("cartResult");

calcTotalBtn.addEventListener("click", () => {
  let cart = [10.99, 5.5, 20]; // sample cart prices
  let total = calculateTotal(cart);
  cartResult.textContent = "Your total is $" + total.toFixed(2);
});


// =============================
// 🔁 Part 3: Loops
// =============================

const countdownBtn = document.getElementById("countdownBtn");
const countdownList = document.getElementById("countdownList");

countdownBtn.addEventListener("click", () => {
  countdownList.innerHTML = ""; // clear previous
  for (let i = 5; i >= 1; i--) {
    let li = document.createElement("li");
    li.textContent = i;
    countdownList.appendChild(li);
  }
  let li = document.createElement("li");
  li.textContent = "🚀 Blast off!";
  countdownList.appendChild(li);
});

// Example while loop (console only)
let i = 0;
while (i < 3) {
  console.log("While loop count:", i);
  i++;
}


// =============================
// 🌐 Part 4: DOM Manipulation
// =============================

const toggleBtn = document.getElementById("toggleBtn");
const toggleText = document.getElementById("toggleText");

toggleBtn.addEventListener("click", () => {
  toggleText.classList.toggle("highlight");
});

// Adding list items dynamically
const addItemBtn = document.getElementById("addItemBtn");
const dynamicList = document.getElementById("dynamicList");

let itemCount = 0;

addItemBtn.addEventListener("click", () => {
  itemCount++;
  let li = document.createElement("li");
  li.textContent = "Item " + itemCount;
  dynamicList.appendChild(li);
});
