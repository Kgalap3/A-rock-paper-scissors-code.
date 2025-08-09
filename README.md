# A code for Rock, Paper, Scissors

// Code for Rock, Paper, Scissors below 💖

const player = Math.floor(Math.random()*3);
const computer = Math.floor(Math.random()*3);
// 0 = "Rock";
// 1 = "Paper";
// 2 = "Scissors";

if(player === 0 && computer === 0){
  console.log("Player picked:   Rock");
  console.log("Computer picked: Rock");
  console.log(" ");
  console.log("It is a draw!");
} else if(player === 1 && computer === 1){
  console.log("Player picked:   Paper");
  console.log("Computer picked: Paper");
  console.log(" ");
  console.log("It is a draw!");
} else if(player === 2 && computer === 2){
  console.log("Player picked:   Scissors");
  console.log("Computer picked: Scissors");
  console.log(" ");
  console.log("It is a draw!");
} else if(player === 0 && computer === 1){
  console.log("Player picked:   Rock");
  console.log("Computer picked: Paper");
  console.log(" ");
  console.log("The computer wins!");
} else if(player === 1 && computer === 0){
  console.log("Player picked:   Paper");
  console.log("Computer picked: Rock");
  console.log(" ");
  console.log("The player wins!");
} else if(player === 0 && computer === 2){
  console.log("Player picked:   Rock");
  console.log("Computer picked: Scissors");
  console.log(" ");
  console.log("The player wins!");
} else if(player === 2 && computer === 0){
  console.log("Player picked:   Scissors");
  console.log("Computer picked: Rock");
  console.log(" ");
  console.log("The computer wins!");
} else if(player === 1 && computer === 2){
  console.log("Player picked:   Paper");
  console.log("Computer picked: Scissors");
  console.log(" ");
  console.log("The computer wins!");
} else {
  console.log("Player picked:   Scissors");
  console.log("Computer picked: Paper");
  console.log(" ");
  console.log("The player wins!");
}
