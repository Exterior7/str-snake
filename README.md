# Snake Game to practicing TypeScript

## Leírás
Pótold a játék hiányzó részeit!

## Csapatmunka
Csapatban dolgozzatok, négy olyan fájl van a játékban, ahol ki kell egészíteni 
a kódot. A csapat minden tagja külön fájlban dolgozzon és __soha ne írjatok 
bele__ a másiknak kiosztott fájlba, így nem fog conflict létrejönni.

## Github
- A csapat egyik tagja forkolja az alap játékot a Github -on. 
- Ezután hívja meg a többi csapattagot a repo -ba.
- Beszéljétek meg, ki melyik feladaton szeretne dolgozni.
- Rendszeresen commit -oljatok és push -oljatok.

## Program futtatása
- Lépj be a mappába: `cd str-snake`
- Állítsd be a code gyökerének a mappát: `code . -r`
- Telepítsd a függőségeket: `npm i`
- Indítsd el a szervert: `npm run serve`
- Nyisd meg a böngészőben a következő oldalt: `http://localhost:4200`

## Feladatok
A feladatokat négy fájlban találjátok:
- `src/Utils.ts` - Két feladat, egyet megoldottunk a konzultáción. - Lipták Gyuri
- `src/Piece.ts` - Négy feladat. - Bonyai Péter
- `src/Level.ts` - Hat feladat. - Győrffy Péter.
- `src/Game.ts` - 2 feladat, plusz BaseGame fájl. - Szöllősi László.

> A feladatok kommentekkel vannak jelölve, amelyek így kezdődnek: FELADAT!

## Extra feladatok
- Oldjátok meg, hogy a piros alma felvétele csak 1 pontot érjen.
  // Game.ts 219 this.updateScore(type === 'food' ? 10 : 50); => this.updateScore(type === 'food' ? 1 : 50);
- A zöld alma felvételénél vonjon le a játék 2 pontot.
  // Game.ts 219 this.updateScore(type === 'food' ? 10 : 50); => this.updateScore(type === 'food' ? 1 : -2);
- A kígyó ne tudjon jobbra fordulni.
  // Tipp: Ha kivesszük a constants.ts -ben a 6-os sort?
- Ha 20 pontot elért a játékos nullázódjanak a pontjai.
  // Tipp: Ha beteszünk a Game.ts 284-es sorába egy if-et?
  // if (this.score == 20) {
  //  this.score = 0
  // }

## Csapatmunka Javaslatok
- Mutatkozzatok be röviden egymásnak, mielőtt kezditek a munkát.
- Mindenki válaszoljon három kérdésre:
1. Kedvenc film
1. Kedvenc étel
1. Kedvenc ország
