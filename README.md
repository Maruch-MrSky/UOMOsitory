## projekt UOMO s Tematem diagramů RPG 
**bude obsahovat úvod a 3 diagramy:**
- Textový popis projektu 
- Model případů užití *(UseCase diagram)* ✅
- Analytický model tříd *(analytic Class diagram)*  ✅ *(vicemene)*
- Návrhový model tříd *(Object diagram)*

# TODO
- **Návrhový model** (přetypovat atributy a operace)
- Vztahy v analytickém modelu ✅
- Textový popis modelu

### připomínky
*připomínky a nápady*

-Přidat datový typ do atributu "inventar" v třídě "Postava" (proč to nemá kulatý odrážky :(  )

[**Quick SYSP Button**](https://github.com/Maruch-MrSky/SYSPository)

[**pozadavky projektu**](https://oliva.uhk.cz/ultra/courses/_1844_1/cl/outline)

## ÚVOD

Model popisuje nenáročnou hru s RPG prvky a multiplayerem. Hráči si můžou vytvořit postavu, vysílat ji na mise, následně získávají expy, zlato a vyzbroj, kterou můžou využívat nebo prodávat. 
O postavách jsou vedeny základní informace (id, jméno, level, expy, hit pointy, zlato, vybavená výzbroj a splněné mise).

Pro získání výzbroje můžou hráči buď na misi (mise má popis, délku mise, odměnu v podobě expů, zlata a výzbroje), nebo ji můžou nakoupit v obchodě (obchod obsahuje nabídku výzbroje a čas obnovy nabídky). Samotná výzbroj má id, název, popis a cenu a dělí se za brnění s hodnotou odolnosti a zbraně s poškozením a rychlostí útoku.

Dále se hráči mohou sdružovat do guild, u guildy systém zaznamenává název guildy, hlavu guildy, seznam členů, žebříček guild a zda probíhá nájezd na jinou guildu.

Hráči se mohou vzájemně poměřovat na Eventech (je zaznamenáván název, popis, délka trvání eventu, žebříček účastnících se hráčů a nějakou odměnu).

Hráči mezi sebou mají možnost komunikovat globálním chatem, který bude zobrazovat odesilatele a zprávu kterou odeslal.

Hru spravují admini, kteří mají možnost vytvářet/upravovat/odebírat výzbroj, zahájit/spravovat/ukončit eventy, přidat/upravit/odebrat mise a mazat nevhodné zprávy v chatu.
