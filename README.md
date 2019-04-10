# Installere på forhånd
- Last ned IntelliJ Community Edition her: https://www.jetbrains.com/idea/
- Klon dette repositoriet

# Bygg og test prosjektet i IntelliJ
- Etter du har klonet repoet og lastet ned IntelliJ begynner du med å starte opp IntelliJ.
- I velkomstvinduet trykker du på "Open" så finner og trykker du på mappen som ble laget når du klonet dette prosjektet.
- Prosjektet bør automatisk starte å bygge, og forhåpentligvis bygger dette uten noe problemer. (Det gjør ingenting om det er noe warnings)

# Start å gjøre oppgaver
- Oppgavene finner man i kotlin mappen (src -> main -> kotlin)
- De er strukturert i mapper, der hver mappe er et overordnet tema der man inni selve mappene har oppgaver i hver fil: "task0X.kt"
- Start ved å teste environmentet i mappen "task01.testEnvironment", gå inn i filen som ligger i mappen og trykk på "play" ikonet.

# Struktur på oppgaver
Oppgavene er strukturert slik at man har en funksjon man tester oppgavene i, og en funksjon der man skal skrive selve oppgaven.

```java
fun main() {
  tests(...
  )
}

// Beskrivelse av oppgaven

fun task1() {
  // Løs oppgaven her
}
```
Når man vil teste om løsningen er korrekt, trykker man "play" ikonet som dukker opp ved siden av main funksjonen, så ser man i loggen om testene kjørte uten feil.
