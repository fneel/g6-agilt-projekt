This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Vi pushar allt till dev - inte main
Vi accepterar inte våra PR
Vi mergar inte våra egna PR - det gör någon annan i teamet

📄 Kontrakt för versionshantering
Projekt: gruppuppgift agilt arbetssätt
Grupp: 6
Datum: 18/2-26
⸻

1. Syfte
   Syftet med detta kontrakt är att säkerställa:
   • En gemensam och konsekvent struktur för versionshantering
   • Minskad risk för merge-konflikter
   • Tydlig spårbarhet av förändringar
   • Professionell arbetsprocess motsvarande branschstandard
   Alla gruppmedlemmar förbinder sig att följa detta dokument.
   ⸻
2. Verktyg
   • Versionshanteringssystem: ********\_\_******** (ex. Git)
   • Repository-plattform: ********\_\_******** (ex. GitHub/GitLab/Azure DevOps)
   • Kommunikationskanal vid konflikter: ********\_\_********
   ⸻
3. Branch-struktur
   Vi använder följande branch-struktur:
   • main – Produktionsklar kod
   • develop – Integrationsbranch
   • feature/_ – Nya funktioner
   • bugfix/_ – Buggfixar
   • hotfix/\* – Akuta fixar mot produktion
   Regler:
   • Direkt push till main är inte tillåten
   • All kod ska gå via Pull Request
   • main ska alltid vara stabil och körbar
   • develop ska alltid vara byggbar
   ⸻
4. Namngivningsstandard
   Branch-namn
   Format:
   feature/kort-beskrivning
   bugfix/kort-beskrivning
   Exempel:
   feature/login-system
   bugfix/nullpointer-check
   Commit-meddelanden
   Format:
   Typ: Kort beskrivning i imperativ form
   Exempel:
   Add: Implement login validation
   Fix: Handle null pointer in UserService
   Refactor: Simplify authentication logic
   Docs: Update README
   Commits ska:
   • Vara små och fokuserade
   • Ha tydliga och beskrivande meddelanden
   • Inte innehålla irrelevant kod
   ⸻
5. Pull Requests
   Alla ändringar ska:
   • Skapas via Pull Request
   • Ha en beskrivning av:
   • Vad som har gjorts
   • Varför det gjordes
   • Eventuella kända begränsningar
   • Granskas av minst en annan gruppmedlem
   • Vara godkända innan merge
   Ingen får godkänna sin egen Pull Request.
   ⸻
6. Kodgranskning (Code Review)
   Vid granskning ska följande kontrolleras:
   • Kodens läsbarhet
   • Struktur och arkitektur
   • Namngivning
   • Testbarhet
   • Att inga känsliga uppgifter checkas in
   • Att koden följer projektets kodstandard
   Feedback ska vara:
   • Saklig
   • Respektfull
   • Lösningsorienterad
   ⸻
7. Hantering av konflikter
   Vid merge-konflikt:
8. Den som mergar ansvarar för att lösa konflikten.
9. Osäkerhet diskuteras i gruppen innan lösning.
10. Ingen “force push” utan gruppens godkännande.
    ⸻
11. Tests och byggbar kod
    • Kod får inte mergas om projektet inte bygger.
    • Tester ska köras innan push.
    • Nya funktioner ska, om möjligt, inkludera tester.
    ⸻
12. Ansvar
    Varje medlem ansvarar för att:
    • Hålla sin branch uppdaterad
    • Pusha regelbundet
    • Kommunicera om större förändringar
    • Inte arbeta direkt i main
    ⸻
13. Brott mot överenskommelsen
    Om kontraktet inte följs:
14. Gruppen diskuterar situationen.
15. Åtgärder beslutas gemensamt.
16. Upprepade överträdelser dokumenteras.
    ⸻
17. Signaturer
    Genom att skriva under godkänner vi att följa detta kontrakt.
    Namn Signatur Datum
