let player = Math.floor(Math.random() * 3)
if (player == 0) {
console.log("player picked: " + "Rock") 
} else if (player == 1) {
console.log("player picked: " + "Paper") 
} else if (player == 2) {
console.log("player picked: " + "Scissors") 
}
let computer = Math.floor(Math.random() * 3)
if (computer == 0) {
console.log("computer picked: " + "Rock") 
} else if (computer == 1) {
console.log("computer picked: " + "Paper") 
} else if (computer == 2) {
console.log("computer picked: " + "Scissors") 
}
if (computer == player) {
  console.log("nobody wins")
} else if (computer == 0 && player == 1) {
  console.log("player wins")
} else if (computer == 1 && player == 0) {
  console.log("computer wins")
} else if (computer == 0 && player == 2) {
  console.log("computer wins") 
} else if (computer == 2 && player == 0) {
  console.log("player wins") 
} else if (computer == 1 && player == 2) {
  console.log("player wins") 
} else if (computer == 2 && player == 1) {
  console.log("computer wins") 
}
