var ranTreasure = Math.floor(Math.random() * 8)
var ranBomb = Math.floor(Math.random() * 8)
var clickCount = 0

while(ranTreasure === ranBomb) {
    ranTreasure = Math.floor(Math.random() * 8)
}

const treasure = (id) => {
// clickCount = clickCount+1

console.log("clickCount", clickCount)
console.log("ranTreasure", ranTreasure)
console.log("ranBomb", ranBomb)

 if (id == ranTreasure) {
    document.getElementById(id).innerHTML = "💎"
    return alert("Congrats! You win!!")
 } 
else if (id == ranBomb ) {
    document.getElementById(id).innerHTML = "💣"
    return alert("Game Over!")
}

else  {
clickCount++
    document.getElementById(id).innerHTML = "🌴"
    // return alert("Game Over!")
    if (clickCount > 2) {
        alert ("You Lose!")
    }
}



}