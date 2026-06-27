const quotes = [
    "Believe in yourself!",
    "Every day is a new beginning.",
    "You are capable of amazing things.",
    "Small steps lead to big results."
];

const btn = document.getElementById("btn");
const text = document.getElementById("quote");

btn.addEventListener("click", () => {
    const random = Math.floor(Math.random() * quotes.length);
    text.innerText = quotes[random];
});
