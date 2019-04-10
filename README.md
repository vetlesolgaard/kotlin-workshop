# Installere på forhånd
- (De fleste har sannsynligvis dette installert allerede) Java 8(++) Development Kit https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
- Last ned IntelliJ Community Edition her: https://www.jetbrains.com/idea/
- Klon dette repositoriet

# Komme i gang
- Klon eller last ned dette repositoriet
- Åpne prosjektet i IntelliJ
- Prosjektet bør bygge automatisk uten problemer

# Start å gjøre oppgaver
- Oppgavene finner man i kotlin mappen (src -> main -> kotlin)
- De er strukturert i mapper, der hver mappe er et overordnet tema der man inni selve mappene har oppgaver i hver fil: "task0X.kt"
- Start ved å teste environmentet i mappen "task01.testEnvironment", gå inn i filen som ligger i mappen og trykk på "play" ikonet.

# Resources
- For å raskt få en oversikt av syntax og litt kode eksempler i kotlin se -> https://kotlinlang.org/docs/tutorials/getting-started.html

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
