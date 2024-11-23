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
-Přidat datový typ do atributu "inventar" v třídě "Postava"

[**Quick SYSP Button**](https://github.com/Maruch-MrSky/SYSPository)

**ÚVOD** 

Model popisuje nenáročnou hru s RPG prvky. Hráč si může vytvořit postavu, vysílat ji na mise, následne získavať expy, zlato a vyzbroj, kterou může využívat nebo prodávat. 
O postavách jsou vedeny základní informace (id, jméno, level, expy, staty, zlato, inventář a vybarvená výzbroj)

Pro získání výzbroje muzou hráči buď na misi (mise má popis, délku mise a odměnu v podobě expů, zlata a vyzbroje), nebo ji můžou nakoupit v obchodě (obchod obsahuje výzbroj a čas obnovy zboží). Samotná výzbroj má id, název, popis a cenu a dělí se za brnění s hodnotou odolnosti a zbraně s poškozením a rychlostí útoku.

Dále se hráči mohou sdružovat do guild, u guildy systém zaznamenáva název guildy, hlavu guildy, počet a jména členů a zda probíhá nájezd na jinou guildu.

Hráči se mohou vzájemně poměřovat na Eventech (event zaznamenava název , popis, žebříček účastnících se hráčů,...
