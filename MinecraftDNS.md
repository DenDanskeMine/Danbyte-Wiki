---
icon: globe
label: Minecraft DNS
authors:
  - name: Christian Rose
    email: support@danbyte.net
    link: https://danbyte.net
category: Minecraft    
---

# Minecraft DNS

Har du dit eget domæne som du ønsker at koble til din Minecraft server?

Så er det i hvert fald her du kan lære hvordan du gør.

## Step 1

Find din IP til din server.

**G1:** 194.15.36.197

**G2:** 94.130.141.38

**G3:** ikke aktiv endnu

## Step 2

Logind på din Dns udbyders hjemmeside, og find din DNS Manager.

Nu skal du oprette en ny DNS record, og vælge `A` som type.

I feltet `Name` skal du skrive det subdomæne du gerne vil bruge. (f.eks. `Play`)<br>
Hvis du ikke vil bruge et subdomæne, så skal du bare skrive `@` i stedet.

I feltet `Value` skal du skrive IP'en til din server.
Dette er den IP du fandt i step 1.

## Step 3

Nu skal du lave en SRV record. Som pejer på den A record du lige har lavet.
I feltet `Name` skal du skrive dit `A` navn fx: `Play`<br>
I feltet `Service` skal du skrive `_minecraft`<br>
i feltet `Protocol` skal du vælge `tcp`<br>
I feltet `Priority` skal du skrive `1`<br>
I feltet `Weight` skal du skrive `5`<br>
I feltet `Port` skal du skrive din port fx `25566`<br>
I feltet `Target` skal du skrive domænet på den server hvor din A record er på.<br>

Vi har disse domæner:

**G1:** `g1.danbyte.net`

**G2:** `g2.danbyte.net`

**G3:** `g3.danbyte.net`

Du kan i principet også bare skrive din A record her. 
Jeg vil dog anbefale at du bruger et af vores domæner, så du nemt kan se at det er vores server du bruger.
![DNS](/img/dnssrv.png)