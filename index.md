---
icon: home
label: Home
authors:
  - name: Christian Rose
    email: support@danbyte.net
    link: https://danbyte.net
category: null    
---

# Velkommen til DanBytes Videndatabase

Her er nogen af de mest nyttiige artikler, som vi har skrevet. Hvis du ikke kan finde det du leder efter, så prøv at bruge søgefunktionen i toppen af siden.

==- Hvor ser jeg min IP?
Du kan se din IP ved at gå ind på dit [Dashboard](https://danbyte.net/dashboard). 
Der inde klikker du blot på det produkt du vil se IP'en på, og så vil den i en grøn knap.
![IP Address](/img/ip.png)
Bemærk at dette er en DNS Addresse.
Hvis du skal brug en rigtig IP, så skal du bruge en af følgende, afhængelig af hvilken server du er på:

 **G1:** 194.15.36.197

**G2:** 94.130.141.38

**G3:** ikke aktiv endnu

==- Hvordan logger jeg ind på mit gamepanel?
Du kan logge ind på dit gamepanel ved at gå ind på [DanByte.net](https://danbyte.net/dashboard) og klikke på en af dine servere.

Herefter klikker du på "Log ind på panelet", og så vil du blive sendt videre til dit spille panel.
![IP Address](/img/ip.png)

==- Min Rust server ville ikke connecte til RCON, hvad gør jeg?
Du skal manuelt allokere en port til RCON, da Rust ikke gør det automatisk.
Samtidig skal du også sætte en query port, og evt en port til Rust+.

Dette gør du ved at gå ind på dit [panel](https://panel.danbyte.net) og klikker på din server.

Herefter klikker du på `Network` og så `CREATE ALLOCATION`.<br>
Det er en god ide at give den et navn, så du kan huske hvad den er til.

Nu skal du klikke på fanebladet `Startup` og find RCON Port, Query Port, og evt Rust+ Port.

Her skal du skrive de porte du lige har allokere, og så trykke på `Save` i bunden af siden.

Nu skal du genstarte din server, og så skulle det gerne virke.

==- Hvordan installerer jeg plugins på min Minecraft server?
For at installere plugins på din Minecraft server, skal du først gå ind på dit [panel](https://panel.danbyte.net) og klikke på din server.
Her skal du sikre dig at din server understøtter plugins. (Hvis du ikke har pillet ved noget, så gør den det i forvejen)

Nu skal du finde et plugin du gerne vil installere, og downloade det. (Det skal være en .jar fil)

Her er nogen forskellige steder du kan finde plugins:

[!button Spigot](https://www.spigotmc.org/resources/)

[!button CurseForge](https://www.curseforge.com/minecraft/bukkit-plugins)

[!button BuiltByBit](https://builtbybit.com/resources/categories/minecraft-plugins.1/)

Når dette er gjort skal du gå ind på dit [gamepanel](https://panel.danbyte.net) og klikke på din server.

Her skal du klikke på `File Managers` > `Plugins` og så `Upload`. 
Her skal du så uploade den .jar fil du lige har downloadet.

Nu skal du genstarte din server, og så skulle det gerne virke.

(Bemærk at nogen plugins kræver andre plugins for at virke, så det er en god ide at læse beskrivelsen på pluginet)

==- Hvordan installerer jeg modpacks på min Minecraft server?
For at installere mods på din Minecraft server, skal du først gå ind på dit [panel](https://panel.danbyte.net) og klikke på din server.

Her skal du klikke på `Version` > `Modpacks` og så `vælg den du ville bruge`.

Nu skal du genstarte din server, og så skulle det gerne virke.
(Husk at nogen modpacks kræver mere RAM end andre, så det er en god ide at tjekke hvor meget RAM din server har)

==- Hvordan logger jeg ind med SFTP?
For at logge ind med SFTP, skal du først gå ind på dit [panel](https://panel.danbyte.net) og klikke på din server.

Her skal du klikke på `Settings` > `SFTP DETAILS` og så klikker du blot på `Launch SFTP`.

Det eneste du skal gøre nu, er at skrive din adgangskode, og så er du inde.

Hvis du ikke har et SFTP program, så kan du bruge [!button FileZilla](https://filezilla-project.org/). Eller du kan bruge [!button WinSCP](https://winscp.net/eng/download.php).

Der er nogen IDE (Integrated Development Environment) som også har SFTP indbygget, så du kan vælge at koble din server direkte til din IDE. (Dette er dog ikke nødvendigt)

==- Jeg kan ikke logge ind på mit gamepanel, hvad gør jeg?

Vi bruger noget der hedder Single Sign On (SSO), som gør at du kan logge ind på alle vores services med det samme login.

Nogen gange kan det dog drille, og så kan du ikke logge ind på dit gamepanel, fra panel.danbyte.net.
men kun inde fra dit [Dashboard](https://danbyte.net/dashboard).

For at løse dette, skal du blot tilgå det inde fra dit [Dashboard](https://danbyte.net/dashboard). 
Nu burde din browser huske dig, og så skulle det gerne virke.

==- 

## Andre guides

Du kan klikke ude i venstre side, for at se nogen af de andre guides vi har lavet.






