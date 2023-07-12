# zadatak_metrika

---
-LOC:
 license = 21 loc
 Start.java = 26 loc
 Calculator.java = 188 loc
 All together = 235...
-Cyclomatic Complexity:
 Calculate = 12 moderate risk
 evaluateExpression = 12 moderate risk
-Observation:
 U kodu nedostaje komentara koji bi objasnili namjenu i logiku određenih delova.
 Dodavanje komentara može poboljšati čitljivost i razumijevanje koda, posebno za druge programere
 koji će ga čitati u budućnosti. Varijabla finalResult ima javni modifikator (static float finalResult;).
 Ako nema posebnog razloga, preporučuje se smanjiti vidljivost varijable koristeći privatni modifikator
 (private).Metoda evaluateExpression hvata Exception i vraća "ERROR".Čitljivost i stil koda
 Neke linije koda su duže i složenije, što može otežati čitanje i razumevanje. 
 Razmatrati razbijanje dužih linija koda na više linija kako biste poboljšali čitljivost. 
 Takođe, sliedite konvencije stila koda kako bi vaš kod bio dosljedan i lakše čitljiv.
