# React-project-notes-and-checklist
Notes, commands and checklist for React Projects


## Setting up React Environment with Vite
if name of project === name of current directory
```
npm create vite@latest . -- --template react
```

#### Sample code to Update a state value in format - ([{}])
function hold(id) {
        setDice(oldDice => oldDice.map(die =>
            die.id === id ?
                { ...die, isHeld: !die.isHeld } :
                die
        ))
    }
