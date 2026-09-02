# What’s nine plus ten? Twenty one!

Skapa en ny mapp på din dator som du döper till _prg1_uppg1_. Publicera denna till GitHub. Skapa en ny fil i mappen som du döper till _dice_game.py_. Här ska du nu börja koda ett litet spel! För godkänt på uppgiften måste du uppfylla kraven, men det finns väldigt mycket frihet i denna uppgift. Du får själva modifiera uppgiften för att passa det du tycker är kul.

## Spelets regler: 
- Spelaren har en tärning (vanlig D6)
- Resultatet ska efter varje kast läggas på en totalsumma
- Efter varje kast får spelaren välja om hen vill kasta igen eller sluta kasta
- Målet är att komma så nära 21 som möjligt
- Om spelaren kommer över 21 så förlorar hen
- Får spelaren exakt 21 så vinner hen
- Stannar spelaren innan 21 får du bestämma vad som händer!

## Krav: 
- Implementera minst en loop i spelet. Rimligtvis körs allt i en while loop eftersom vi ska fråga användaren efter varje kast om denne vill kasta igen eller inte.
- Innehåller några if-satser.
- Innehåller minst två variabler. Kanske totalsumman + ett tillstånd för att hålla koll på om vi ska fortsätta eller inte? Antal kast? Du bestämmer!
- Spelet ska tydligt förmedla vad som händer i varje steg.
- Tydligt fråga: Vill du kasta igen?
- Tydligt förmedla: Nuvarande totalsumma
- Tydligt förmedla: Om man vann eller förlorade

## Extra:
- **Lägg till en prissumma**. Spelaren spelar för att vinna pengar. Här kan du modifiera reglerna efter eget intresse, men ett förslag är: 
  - Spelaren har en viss summa pengar. Det kostar en bestämd summa att spela, men man får sätta in mer om man vill. Får man exakt 21 så dubblas pengarna man satte in. Får man mellan 19-20 så vinner man en viss procent av det man satte in. Får man mer än 21 så halveras pengarna man satte in. 
- **Lägg till en extra spelare** så man kör mot varandra
- **Lägg till en bot** som du kör spelet mot! 
  - Boten kan t.ex slumpmässigt välja om den vill avstå sitt kast eller köra på varje runda. 
  - Du kan ge boten lite logik, så den inte vill avstå sitt kast om den inte har en chans att förlora nästa kast.
  - Du kan göra en stadig robot som tar det säkra före det osäkra, eller en galen gambling robot som alltid tar en risk för att försöka vinna mer pengar! Vilken går det bäst för? Testa att möta båda!
- Utöka spelet så du får **välja game mode** i början av spelet
  - T.ex bot mot bot?
  - Eller lägga till aternativa spel, t.ex: Betta på tärningskast, bara slumpa tärning, högst kast vinner etc.
