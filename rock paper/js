let playerScore = 0;
let computerScore = 0;
let compChoice;
let playerChoice;

let playerScoreboard = document.querySelector('.anna-count');
let computerScoreboard = document.querySelector('.kd-count');
let WINNER = document.querySelector('.result');

function computerChoice(){
  const computerOptions = ["rock", "paper", "scissors"];
  const randomNum = Math.floor(Math.random()* 3);
  compChoice = computerOptions[randomNum];
};

function throwRock(){
  playerChoice = "rock";
  computerChoice();
  console.log(playerChoice);
  console.log(compChoice);
  playGame(playerChoice, compChoice);
}

function throwPaper(){
  playerChoice = "paper";
  computerChoice();
  console.log(playerChoice);
  console.log(compChoice);
  playGame(playerChoice, compChoice);
}

function throwScissors(){
  playerChoice = "scissors";
  computerChoice();
  console.log(playerChoice);
  console.log(compChoice);
  playGame(playerChoice, compChoice);
}

function playerWin(){
  playerScore++;
  playerScoreboard.innerHTML = playerScore;
  WINNER.innerHTML = "WINNER";
}

function playerLose(){
  computerScore++;
  computerScoreboard.innerHTML = computerScore;
  WINNER.innerHTML = "LOSER; Try Another Game ;)";
}

function playGame(player, computer){
  if (player === computer){
      WINNER.innerHTML = "Tie";
  } else if (player === "rock" && computer === "scissors"){
    playerWin();
  } else if (player === "paper" && computer === "rock"){
    playerWin();
  } else if (player === "scissors" && computer === "paper"){
    playerWin();
  } else if (player === "rock" && computer === "paper"){
    playerLose();
  } else if (player === "paper" && computer === "scissors"){
    playerLose();
  } else if (player === "scissors" && computer === "rock"){
    playerLose();
  }
}
function reset(){
  annaScoreboard.innerHTML = "0";
  Scoreboard.innerHTML = "0";
  WINNER.innerHTML = "";
}
