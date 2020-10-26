# My First README

Repo explaining README.md

## Description
HTML-based Tic-Tac-Toe game using JS functions.

## Steps to install Tic-Tac-Toe on local computer
1. Go to [repo](https://github.com/tuanhrex/tic-tac-toe) on Github profile.
2. `fork` the repo.
3. `clone` the repo to local machine.
```text
 git clone https://github.com/tuanhrex/tic-tac-toe.git
 ```
 4. Locate and change to the directory
 ```text
 cd .\tic-tac-toe\
 ```
 5. Open the `index.html` file
 ```text
 open index.html
 ```



```javascript
document.querySelector('#restart').onclick = function() {
    clicks = 0;
    zero = null;
    one = null;
    two = null;
    three = null;
    four = null;
    five = null;
    six = null;
    seven = null;
    eight = null;
    document.querySelectorAll('p').forEach(p => p.innerHTML = '');
    document.querySelector('.message').innerHTML = "Player One's Turn";
    
}

```

```css
#grid {
  justify-content: center;
  display: grid;
  grid-template-columns: 150px 150px 150px;
  grid-template-rows: 150px 150px 150px;
  
}
```

```html
 <div id='grid'>
    <p id="0"></p>
    <p id="1"></p>
    <p id="2"></p>
    <p id="3"></p>
    <p id="4"></p>
    <p id="5"></p>
    <p id="6"></p>
    <p id="7"></p>
    <p id="8"></p>
</div>
```

| functions | Description |
| ----------- | ----------- |
| `turn()` | Determines which turn |
| `assignPlayerOne(id)`| Assign player one's class to the selected box |
| `assignPlayerTwo(id)`| Assign player two's class to the selected box |
| `winner()`| Determines the winner based on current selection |
