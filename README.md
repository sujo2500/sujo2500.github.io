Personlig hemsida för susan johansson
använt HTML teknik
https://sujo2500.github.io/
https://sujo2500miun.netlify.app/
git add = Väljer vilka ändringar som ska vara med i nästa commit
git commit = sparar de valda ändringarna
Du ändrar filer -> git add -> staging area -> git commit -> git-historiken
Man jobbar i branches för att hålla koll på ändringar som gjorts, när de gjorts, och inte blanda grundstrukturen ihop med något som kanske längre fram visar sig behöva göras en förändring. det är bra för spårbarhet och speciellt bra om man jobbar flera stycken i ett projekt där det är uppdelade arbeten. 
om man tänker en gren som fördelas i två grenar som sedan återförenas till en gren kan man kalla det en merge. två branches som slås ihop och interageras. alltså hamnar grenarna i en gemensam main
När man pushar till Github så gör man det från datorn eller vs code. netlify behöver koden för att bygga projektet som sen blir en färdg hemsida. git hub lagrar källkod och samarbetar med andra. Netlify hostar hemsidan.
man använder .gitignore. exempel: node_modules (ignorera hela mappen). *.log: ignorera alla .log filer
