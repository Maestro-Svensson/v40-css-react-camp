Peka på importen: var i App.jsx CSS-filen kopplas in.
svar: På rad 2 import "./App.css"

Peka på className: raden där done styr klassen completed.
svar: rad 49 className={t.done ? "todo completed" : "todo"}>

Peka på resultatet: vad ögat ser när done är true — och varför det inte är samma sak som state.

svar .completed {
  text-decoration: line-through;
  opacity: 0.6;
}

gör en line genom texten som är klar.
en State är ett värde i minnet