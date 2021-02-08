<style>
.phb#p1{ text-align:center; }
.phb#p1:after{ display:none; }
.phb p+p { margin-top: .2em; }
.phb .footnote { color: #d4ad6d; font-weight: bold;; }
.phb .pageNumber { color: #d4ad6d; font-weight: bold;; }
.phb:after { background-image: url(https://raw.githubusercontent.com/Tougher-Together-DnD/invasion-of-eirinn/main/Images/footer.png); }
.phb blockquote { margin-top: 1em; margin-bottom: 2em;}
.phb h1, .phb h2, .phb h3, .phb h4 {
    color: #336600;
}
</style>

<img 
  src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/homebrew-cover-v1.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:816px;'/>
  
<img 
  src='https://raw.githubusercontent.com/Tougher-Together-DnD/common-assets/main/logos/tougher-together-logo-red.webp' 
  style='position:absolute;left:320px;top:10px;width:20%'/> 

<h1 style='padding-top: 100px;text-shadow: 5px 5px #000;-webkit-text-stroke: 2px black;color: white;font-size: 70px;'>The Green Isles</h1>

<img 
  src='https://raw.githubusercontent.com/Tougher-Together-DnD/common-assets/main/images/dnd/dnd-bar.png' 
  style='position:absolute;top:220px;left:85px;width:80%'/>

<img 
  src='https://raw.githubusercontent.com/Tougher-Together-DnD/common-assets/main/images/dnd/dnd-banner.png' 
  style='position:absolute;bottom:120px;left:0px;width:50%'/>

<p style='position:absolute;bottom:129px;left:0px;width:50%​;font-weight: bold;color: white;font-size: 16px;'>TOUGHER TOGETHER HOMEBREW</p>

<p style='position:absolute;bottom:60px;left:80px;width:700px;color: white;font-size: 24px;'></p>
  
\page

<style>
  .toc a {
    color: inherit !important;	/*toc specifically wants black text. This resets the headers*/
  }

  .toc li span:nth-child(2){	/*Allow dot leaders to fill remaining space but not overlap*/
    width: auto;
    overflow: hidden;
    white-space: nowrap;
    display: block;
  }

  .toc li span:nth-child(2):after{
    font-family		: BookSanity;	/*Remove any header styles from dot leaders*/
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    content:
      " ........................................"
      "........................................."
      "........................................."; 
  }
  
  .toc li span:first-child{
    float: right;
    font-family		: BookSanity;	/*Remove any header styles from page numbers*/
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    margin-left		: 1px;	/*Leaves a small space between page numbers and dot leaders*/
  }
  
/*Special cases for headings*/    
  .toc li h3 span:nth-child(2):after{
  	content: " ";						/*Remove dot leaders on h3*/
  }
  
  .toc li h3 {
    margin-bottom: 4px !important;		/*Special spacing for h3*/
    margin-top: 10px !important;
    line-height: initial !important;	/*For some reason Multi-line h3 line spacing changed*/
  }
  
  .toc li h3 span:first-child{
  	line-height: 1.8em !important;  	/*Line page numbers up with Multi-line h3 better*/
  }
  
  .toc ul ul {
  	margin-left: 10px !important;		/*Original lists intented too much*/
  }
  
  .toc>ul>li {
    margin-bottom: initial !important;	/*margin for list items needs to be removed or 0*/
  }
</style>

<div class='wide' style="text-align: center">
# Contents
</div>

<div class='toc'>
- ### [<span>3</span><span>The Green Isles</span>](#p3)
 - #### [<span>3</span><span>Summarized Timeline</span>](#p3)
 - #### [<span>4</span><span>People</span>](#p4)
  - [<span>4</span><span>Firbolg</span>](#p4)
  - [<span>5</span><span>Formorians</span>](#p5)
  - [<span>5</span><span>Tuathe De Danann</span>](#p5)
  - [<span>5</span><span>Orc Horde</span>](#p5)
  - [<span>5</span><span>Northlanders (Uthgardt Raiders)</span>](#p5)
  - [<span>5</span><span>Kelts</span>](#p5)
  - [<span>6</span><span>Traditionalist</span>](#p6)
  - [<span>6</span><span>Loyalist</span>](#p6)
  - [<span>6</span><span>Sea Princes</span>](#p6)
  - [<span>6</span><span>Others</span>](#p6)
 - #### [<span>6</span><span>Culture and Customs</span>](#p6)
  - [<span>6</span><span>The Tenets</span>](#p6)
  - [<span>7</span><span>Personhood</span>](#p7)
  - [<span>7</span><span>Honor Price</span>](#p7)
  - [<span>7</span><span>Bards and Judges</span>](#p7)
- ### [<span>8</span><span>Aowes Si Calendar</span>](#p8)
 - #### [<span>8</span><span>Time Keeping</span>](#p8)
 - #### [<span>8</span><span>Festival Days</span>](#p8)
  - [<span>8</span><span>Imbolc</span>](#p8)
  - [<span>8</span><span>Beltaine</span>](#p8)
  - [<span>8</span><span>Aban Artur</span>](#p8)
  - [<span>8</span><span>Lughnasadh</span>](#p8)
  - [<span>8</span><span>Samhain</span>](#p8)
- ### [<span>9</span><span>Keltic Pantheon</span>](#p9)
 - #### [<span>9</span><span>Dieites</span>](#p9)
  - [<span>9</span><span>Danu</span>](#p9)
  - [<span>9</span><span>Belenus</span>](#p9)
  - [<span>9</span><span>Ogma</span>](#p9)
  - [<span>9</span><span>Silvanus</span>](#p9)
  - [<span>9</span><span>Cernunnos</span>](#p9)
  - [<span>9</span><span>Dagdha</span>](#p9)
  - [<span>10</span><span>Aine</span>](#p10)
  - [<span>10</span><span>The Morrigan</span>](#p10)
  - [<span>10</span><span>Lir</span>](#p10)
 - #### [<span>10</span><span>Triumvirate Sisterhood</span>](#p10)
- ### [<span>11</span><span>Saltmarsh (Starting Area)</span>](#p11)
 - #### [<span>11</span><span>Important Figures</span>](#p11)
  - [<span>11</span><span>Eda Oweland</span>](#p11)
  - [<span>11</span><span>Eliander Fireborn</span>](#p11)
 - #### [<span>11</span><span>Character Hooks</span>](#p11)
  - [<span>11</span><span>Backgrounds</span>](#p11)
  - [<span>12</span><span>Five Factions</span>](#p12)
</div>

<div class='toc'>
- ### [<span>13</span><span>Appendix A: Aowes Si Calendar</span>](#p13)
- ### [<span>14</span><span>Appendix B: Keltic Pantheon</span>](#p14)
- ### [<span>15</span><span>Appendix C: Homebrew Rules</span>](#p15)
 - #### [<span>15</span><span>Modified RAW</span>](#p15)
  - [<span>15</span><span>Attacking Climbing Creatures</span>](#p15)
  - [<span>15</span><span>Crew Actions Players Roll Modifier</span>](#p15)
  - [<span>15</span><span>Flanking</span>](#p15)
  - [<span>15</span><span>Concussions</span>](#p15)
  - [<span>15</span><span>Health Potions Give Max Value</span>](#p15)
  - [<span>15</span><span>Inspiration</span>](#p15)
  - [<span>15</span><span>Instant Kills</span>](#p15)
  - [<span>15</span><span>Optional Rule: Diagonals</span>](#p15)
  - [<span>15</span><span>Shape Shifting While Caged</span>](#p15)
  - [<span>16</span><span>Shooting Prone</span>](#p16)
  - [<span>16</span><span>Sleeping Counts as Paralyzed (unless magically induced)</span>](#p16)
  - [<span>17</span><span>Lingering Injuries</span>](#p17)
</div>

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII=" height="500">

#### Extras 
**Created by [Mhykiel](https://www.worldanvil.com/author/Mhykiel).**   
**Current Version:** 1.0  
**Cover image:**  
Modified from "The Magic Cup" by [Jim Fitzpatrick](https://jimfitzpatrick.com/)


<div class='pageNumber auto'></div>
<div class='footnote'>CONTENTS</div>
\page

# The Green Isles

<div class='descriptive'>
"From that island at the end of the world, no soldier returned without tales of wonder – walking forests, talking fae, enigmatic shapes half man and half beast: things that you ought not to believe unless you see them yourself."
  
  ~Margo Verida, Amnian Bard
<br>
</div>

The Green Isles have always sparked debate among scholars. Some convinced they were fanciful long tales by sailors. For millennium they were surround by the Maelstrom, a wall of thunderous dark clouds extending from sea to sky. The wall of storm has collapsed around the insular lands, yet the extra-planar mists remain. With the upheaval of recent world events some in the world are still reluctant to accept their emergence upon the Prime Material plane.

The archipelago is "Domain of Dread" on a collision course with the Material plane. During its "fall" it traverses the Feywild and Shadowfell. In ages past it pulled essences from the Inner and Outer Planes as well.

The Tuathe De Danann, having won wars against the other races, have established themselves as the De Facto rulers. But an unrighteous misdealing has cursed their reign to be short lived and fraught with conflict. Their numbers shrink. In the midst of debating their next step, a battle broke out with Elemental Evil Cultist, Cult of the Eternal Flame. During that fight Warchief Sren in one mighty blow split Nuada's shield in two, severing Nuada's offhand arm in the same strike. A young blonde haired, blued eyed warrior named Bres lifted Nuada's severed hand in the air, using it a s a rallying battle cry and charged forth routing the cultist advance.

According to ancient law: Rulers were to be physically fit. Nuada had to resign, passing the crown to one elected among the grandchildren of Dagdha (His father's father). An election was held and the attractive war hero Bres became High King. But King Bres is also half-Fomorian, and his rule over The Isles include excessive taxes, slave trade, and other machiavellian machinations.

Bres is the Villain. He plans to distabilize the region for a Fomorian conquest. The party will not only have to defeat Bres, but ruin his reputation as the destined High King and expose him for the cruel dictator he is. While safegaurding The Isles against other nefarious plots.

> ##### Domains of Dread.
> Are a series of demiplanes located in a remote corner of the Shadowfell and hidden from the rest of the plane by thick walls of mist.
>
> Most often a mysterious Dark Power controls the demiplane and elects a champion, a Dark Lord, to rule the land on their behalf.

## Summarized Timeline
A list of world changing events in the Forgotten Realms and their impact upon The Green Isles.

- **-31,000 DR Ao (Overgod) sundered the world into two worlds: Abeir and Toril.**

As a Domain of Dread in the middle of emergence the Splitting of the worlds reduced the chaotic energies here in half. The Isles become inhabitable by elementals, giants and dragons. However, the magical weave here is almost palpable to magic users. Indigenous creatures survive radiated by these otherworldly energies.

- **-25,000 DR The Firbolg invade.**

The Firbolg were a race of giant-kin from the Osteria empire. In accordance with "The Ordning", a Jotun social structure, they were used as slave labor. Tasked with carrying supplies across construction sites, their name means "men of bags".

The Osteria empire was weakened by a thousand year war with dragons. The Firbolgs revolted, denied The Ordning, and fled for freer lands. Extinct today, their simple stone monuments can still be seen across the islands.

- **-17,600 DR The Fomorians invade.**

The creation of Evermeet during The First Sundering displaced aquatic and deep ocean cultures. A mix of aquatic refugees joined together calling themselves Fomorians. The Fomorians gained a foothold upon the coastal shelves.

- **-17,000 DR The Tuatha De Danann (Tuathde) invade.**

After the First Sundering, Archfey and Leshay attuned to nature were disturbed by the use of such magic. They set off in four boats searching for remote lands. Entrenched with a mentality to isolate themselves from other races.

After arriving upon The Isles, the fey asked the Firbolg to give up half the land. The giants refused and war erupted. The Tuathde won, but instead of taking half as asked for, they transplanted the Firbolg to a reserve on Connacht island (1/8th of the land).

Each boat carried an acorn, that magically held a major Tuathde city. They planted their cities and burned the boats. The smoke of which mixed with the mist to form a wall of storm clouds. The destructive "Maelstrom" to keep other races from entering. The wall extended from sea surface to clouds above. In between times of relative peace and trade, armed conflict would erupt between the Firbolg, Fomorians, and Tuathde races.

<div style='margin-top:140px'></div>


<div class='pageNumber auto'></div>
<div class='footnote'>The Green Isles</div>
\page

- **-11,800 DR The Eladrin arrive.**

After the First Crown War, a group of Lashay and Noble Eladrin were shocked and disenfranchised with their elven peers. They sought to travel to Evermeet, only to become lost in the Trackless Sea. Overcame by the maelstrom they ship wrecked upon The Green Isles. Drawn to the Archfey society of the Tuathde and the influence of the Feywild upon the islands, they chose to stay. Overtime establishing the Seelie Court with the Archfey. Some Archfey were worshiped by the Elves and sentient creatures enough to attain deity levels of power. 

Later on during the Crown Wars a powerful Sorceress taught by the Tuathde, sought to end the war between Corellon and Lolth. She cast high magic ritual to attain godhood. Some of her wizards however were still greedy for dynastic power, and many believe influenced by Fomorian agents. These wizards attempted to siphon power off for themselves (an act that would kill her). In a bid for survival against such betrayal she altered her song and eventually became the Raven Queen. The loss of faith in the Elven pantheon and people pulled her downward into the Shadowfell. Many of her followers resigned themselves to that plane as well. Among the Tuathde she is known as The Morrigan.

- **-339 DR The Four Cities fall.**

The Four cities of the Tuatha De Danann had grown into marvels of might and magic. Mountains intwined with roots from great oak trees, floated above the landscape and could move as they saw fit. Karsus' Folly was an unforeseen catastrophe that sent the cities crashing to the ground. The surviving Tuathde still have not recovered. Lacking the numbers to perform the High Elf Magics again, the Maelstrom, the protective wall of storm fell.

- **-300 DR The Orc Horde invade.**

A mist still floats around the insular lands, but travel in and out are much easier. Now exposed to the rest of Toril, Orcs landed in search of victory and conquest. Seizing Connacht the Orcs destroyed what was left of the pureblood Firbolgs. Renaming the island to Oman.

The Fomorians, created the Unseelie court. In contrast to the Tuathde, they idealized dominion and uncontested power. Convinced the Orcs would seize control of the surface, the Fomorians sought to empower themselves through pacts with demons. Rituals connected to the Abyss deformed many Fomorians into monstrosities. Worship of Orcus became popular. Orcus has taken an interest in The Isles, suspecting to find the Raven Queen's true name here.

- **-250 DR Barbarian Settlers.**

Having defeated Orcs in their homelands some barbarian warriors sailed in search of Orc encampments. The Uthgardt tribe arrived through the mists. An alliance of necessity was struck between the Northlanders and the Tuathde. The descendants of that venture eventually become the Pizzly (half-polar half-grizzly bear) tribe. They raid caravans and coastal cities alike when not squashing an Orc population boom.

<br>
<div style='margin-top:250px'></div>
**Image used:**  
"Fomorians" by John Duncan

While the Uthgardt shun all magic except for their shamans, some departed the tribe and were taught by the Fey to become the first Kelts, Druids and Judges. Often decorating their bodies in magical blue tattoos before battle.


- **1385 to 1395 DR Year of Blue Fire.**

The Spellplague changed the world. The portals to the outer realms closed. The Feywild and Shadowfell settled into being parallel with the Material Plane around The Isles.

The Sword Coast kingdom of Amn lost its trade routes to the Western continent of Maztica. Some of these ships harbored in The Green isles. The defunct Luskan empire, turns to piracy. A few smaller pirate dynasties establish themselves as The Sea Princes among The Isles. Secret coves of demon-worshipping Luskan pirates deal in a black market and have a stable trade of slaves with the Fomorians.

- **1491 DR Elemental Evil.**

The Cult of the Eternal Flame, operated from the Dread Forests. Amn and Tuathde troops squashed the uprising and secured the *Wild Flame Pact* alliance. During the last battle the Tuathde High King Nuada lost his arm. Bres reigns as High King in the region.

## People
The population is mostly comprised of Humans (35%), Fey and Elves (25%), Halfings (10%), Half-Elves and Half-Orcs (5%), Dwarves (5%), Other (20%).
In order of arrival to The Green Isles.

### Firbolg
When they arrived the Firbolg were composed of Hill Giants, Verbeeg and other giant-kin. These refugees revolted against The Ordning of an ancient Jotun empire.

<img 
  src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/fomorians-top-right.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:816px' />
  
<img 
  src='https://github.com/Tougher-Together-DnD/common-assets/blob/main/images/homebrewery/default-paper-stains/top-right-corner.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:916px' />

  <div class='pageNumber auto'></div>
<div class='footnote'>PEOPLE</div>
\page

The Isles were still erupting with planar energies and ruled by wild primordials, dragons and wyrms. The Firbolg crafted a rather civilized culture from an unforgiving terrain. They made stone monuments of 25 ton stones, that mark important spots upon the islands. But the Firbolg themselves are thought to be extinct.

### Fomorians
A nation that lives underwater around The Isles. The Fomorians host the Unseelie Court. A collection of powerful tribal leaders more than a court. They loosely rule over Fey, Merrow, Saughain, Koalinth and other evil inclined creatures. However, the Sea Elfs, Lizardfolk, and an offshoot of Merfolk still rule themselves in small communities.

While some Fomorians seem focused on wanton destruction, they are not dim witted. Often working behind the scenes to have power consolidated before they take it all away. The Fomorians value the strength to take what one wants. Many Fomorians have turned to demon pacts to gain extra powers or self mutation, augmentation to overcome perceived weaknesses in their own bodies. (Simic Hybrids known as the Reformed Fomorians)

Their ultimate goal is seize power over all of the The Green Isles and extend that dominion outward. Allied with the Sea Princes, whom they trade with for ill gotten cargo and slaves alike.

### Tuathe De Danann
Composed of Archfey, Elfs, Centaurs, and other woodland fey the Tuathde are the defacto rulers of Eirinn (the largest island in the archipelago). They maintain the Seelie court. Once a great court of noble Eladrin, teaching the ancient ways of Druidic and High Elf Magic to newcomers. Their numbers are in short supply now.

They maintain an alliance with the Fearun nation of Amn, manning Burle as a defensive post against aberrations from the Dread Forest or Orcs from Oman (Connacht).

### Orc Horde
The Orc Horde have control over the wild untamed island of Connacht, now called Oman. Its thick jungles, swamps, and wildlife are formidable obstacles before reaching the the fortified caldera the Orcs live at.

Not known for their ship building the Orcs have the unusual habit of being rather settled in the region. They search for portals or means to expand outward from The Green Isles. It's not uncommon to see aberrations, trolls, and giant-kin among their raiding parties.

### Northlanders (Uthgardt Raiders)
The Northlanders are a nomadic people that migrate following the elk and large game of The Isles. They claim lineage back to the original Uthgardt hunting party that found their way through the mists. Uthgar killed a Pizzly Bear in combat.

A fearsome bear with webbed feet, as large as two horses tied side to side, white fur with a mane of reddish brown spiky tips, a long prehensile tail, and jaw that could crack a shield in two. The Northlanders call themselves the Pizzly Tribe in honor of Uthgar's prowess. The body of which is burried in a secret mound.

They treat each person as they come. One season they might raid a caravan, and the next season attempt to trade with a caravan from the same merchant guild. Official associations that are not blood relations are a foreign concept to the Northlanders. Their long boats are fast, strike without warning ships and ports alike.

They are sworn enemies of The Horde and are accreditted with some of the most daring attacks on Oman soil.

### Kelts
Uthgardt tribes disdain magic except for their shammans and magical weapons. To cast a fireball from a distance is seen as cowardly. Over time some Uthgardt have left the tribe to become more attuned to nature. Having been taught the Druidic ways by the Archfey Tuathde, they call themselves the Kelts. They still admire bravery and a warrior mentality. Often painting themselves in magical blue tattoos and patterns before running into battle stark naked. The woman paint their hair and skin white, eyelids a brillant blue, then wear long flowing black dresses before they run into battle eyes closed.

Some of the Kelts serve as reknown Judges and Bards to the realm.

### Traditionalist
From Tethyr came a group of Tethyrian settlers. Being accostumed to working with Wood Elfs, the Traditionalist were content to live peaceful lives fishing and farming the area. They established small settlements alog the shoreline of Eirinn, most noteably Seaton and Saltmarsh. A few hundred years later with the Tuathde shrinking in number, attacks against the settlements by aberrations and Unseelie became more prevalent. They called upon the Council of Five in Amn for assistance securing the tradeposts and routes.

Amn troops argmented with Shield Dwarves from northern Fearun supported the disperse settlements. Amn has given mines to the Dwarves as compensation, to the consterantion of many natives.

### Loyalist
The Loyalist are those loyal to Amn. Mostly composed of military units they arived and began occupying the cities, treating the Traditionalist as if they were colonies of Amn. The city of Seaton was even awarded as a province to govern to an Amnian oligarch. Occasionally spats of unrest erupt between the Traditionalist and the Loyalist in the larger towns like Saltmarsh. In Amn arcane magic is outlawed. As well as many things considered contriband, items embargoed against Amn enemeny states.

<div class='pageNumber auto'></div>
<div class='footnote'>A SUMMARIZED TIMELINE</div>
\page

<br>
<div style='margin-top:220px'></div>

The Traditionalist, which include halflings, half-elfs, and human families, generations entrenched in The Isles moan under the new regulations. Accustomed to a little arcane magic use and freedom, these families bemoan the tradeoff of personal freedom for secure trade as "unconstitutional" and a reach for power extending past of any promise or contract they agreed to.

### Sea Princes
Pirates hailing from the Faerun nation of Luskan attack merchant ships. They procure cargo and humanoid occupants as slave labor to sell on the black market. Some of whom are sold to the Fomorians for demon rituals. The Sea Princes enjoy a fair amount of freedom away from the High Captains and factions of their home port Luskan. Calling themselves the Sea Princes.

The Sea Princes have a hand in all smuggling activity in the area.

### Others
There are other islands and races scattered about The Isles not discusses here.

## Culture and Customs
### The Tenets

<div class='descriptive'>
"How do you live here? There isn't a tree to hang a man, water to drown a man nor soil to bury a man?"
  
  ~Dorn Ludlow, Tethyrian General
</div>

When a Tethyrian General Ludlow landed upon Eirinn, there were already people living among the barren hills. Just under the white peaks, land crowded with moss covered stones and crab grass. He asked, "How do you live here? There isn't a tree to hang a man, water to drown a man nor soil to bury a man?" The residents responded, "With a truth seeking heart, strength of body, and by fufilling our words." Ludlow agreed and slaughtered the town. Building a fort atop the ruins. Subsisting off the land as the previous people had done.
```
```
<br>

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNkYAAAAAYAAjCB0C8AAAAASUVORK5CYII=" height="210">

**Image used:**  
"Twilight of the Gods" by Jim Fitzpatrick
<br>

The Isles have a way of punishing those that break The Tenets: Seek Truth, Strength, and Keep one's Word.

That's not to say people do not lie. They often obscure deeper motives with smaller truthful ones, engage in double speak, wear disguises and fake personas, or fufill a promise, contract, in adherence to the litteral instead of the spirit.

For instance, a great warrior was put under a Geas by a powerful wizard to fetch a sentient sword. The warrior added, "When next you see me I shall have the sword held in hand." When the warrior returned, after a challenging adventure, on top of the wizard's tower he showed the sword in his hand. As the wizard reached out to seize it, the warrior threw it high into the air. Where the wind caught hold of the moonblade and flew it away to its rightful master. The wizard infuriated but the warrior was safe in the knowledge that he had fethced the sword as promised.

> ##### Gaesa
> Gaes (singular) are charges or taboos (not to mention the spell "geas"). One can willing enter a Geas some of which may conflict. For instance, Another warrior had a geas that banned him from eating dog meat, but there was a powerful general taboo against refusing hospitality. A villianous witch offered the warrior shelter during a storm (one she caused) and offered him a dinner of dog meat. The warrior obliged and the next day died at the hand of the witch's three sons, who faced the warrior upon the road home.

Also because a leader may inadvertly make promise backed by their people, some may have taboos they are unaware of.

All the races, even most Orcs, are keen to keeping The Tenets, less The Isles strike one dead. The Loyalist, being the newest to arrive to The Isles consider the taboos and Tenets polite superstition. Unaware of their real power.

<img 
  src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/twilight-of-gods-top.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:816px' />
  
<img 
  src='https://github.com/Tougher-Together-DnD/common-assets/blob/main/images/homebrewery/default-paper-stains/top.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:916px' />

<div class='pageNumber auto'></div>
<div class='footnote'>CULTURE AND CUSTOMS</div>
\page

### Personhood
Each person is generally judged on their own merit. Drow, Tiefling and other races accustomed to hatred in Fearun will find The Green Isles refreshing. The people warmly welcome each other despite parentage. A condition of fate the person had no control over, therefore can not rightly be held accountable for. There are some who hold racist grudges against the Uthgardt or Fomorians, but that is on an individual basis.

Except Orcs. While a town may be weary of one full blooded Orc, a group of 2 or more is usually met by the militia.

Women have just as many rights as men. They own property, optionally divorce, and more. They actually tend to be the inheritors of skilled profesions. Woman tend to have the civilized skills of weaving, blacksmithing, farriers, ect.

Rights of inheritence to a land or position are passed down to grandsons (granddaughters if male heirs are absent). When a new king needs elected, the next is chosen from the grandsons of the king's father.

There are however nations like the Fomorians, Sea Princess, or Orcs that take slaves. And treat them as below livestock in usefulness. This practice is highly discouraged and even outlawed in most of the other nations.

Sometimes prisoners are exchanged as collateral for an arrangment. A "you do as you promise, or they die" type of deal. The exchange is usually one for one. And there is a taboo against asking for women or children. Tho women are free to volunteer themselves. Which both parties take as a great honor, a testement to their trustworthiness. 

### Honor Price
Offenses are handled differently across the land compared to other Fearun nations. Often the jails go unused as people settle disputes among themselves. Petty crimes such as thievery result in the guilty paying the Plaintiff an honor price.

An Honor price is set by the station, class, or reputation of a person. What might be concluded as what a man is worth. Woman have the same honor price plus three bags of flour and if she is not married, a dowry cost as well.

High crimes such as murder, charge the guilty twice the honor price or death.

If there is a dispute about guilt, a Judge is called upon. Judges can be Druids, Witches, Archfey or other classes. They are respected in the land for their rulings. Which are meant to avert any Tenet or Gaes breaking when carrying out a punishment or recompensation.

A Tribe, Guild, or town would be respnsible for making sure the guilty party pays their due. Or the land might strike them down for the groups apathy.

People can also take out loans up to their Honor Price.

> ##### Campaign Rule: Honor Price.
> A Player character will have an Honor Price that is: (Level x 100gp) plus the optional (reknown points x 10gp) minus any honor prices paid.
>
>An NPC's honor price is usually their CR x 100gp.
>
>If a Player Character's Honor Price reaches zero they may be forced into indentured servitude, slavery, or have a gaes levied against them.

### Bards and Judges
Among the civilized people of The Green Isles, Bards and Judges hold a special reverence. They keep the history, knowledge, and law.

It is money well spent to have a Bard sing songs or write poems to praise your deeds. Or ill fortune if they should take offense and spread through mokery and satire your short comings.

Judges are respected elders and can be sought out for ways to end curses, gaes, or to affirm a guilty party.

> ##### Reputation.
> The players will have to win the favor of towns they come across. One way of softening them up is to have a bard perform ballads and poetry on your behalf.
>
> A good performance will sway the people to your cause, while a bad performance will let everyone know of your Flaws (character sheet flaws).
>
> A player Bard should not praise their own exploits. This is seen as arrogant and untrustworthy by the locals. However, a Player Bard can put on a perfomance to heighten or diminsih the reputation of others.
>
>Conversly shows involving Feats of Strength or telling a Fishing Tale (*Ghost of Saltmarsh*). Might win the crowds favor.

<div class='pageNumber auto'></div>
<div class='footnote'>CULTURE AND CUSTOMS</div>
\page

# Aowes Si Calendar
The citizens of the Green Isles have a more lesiure attitude with time. That do not hussle around concerned about the minute. The tell time to eat, sleep, plant, and more by the moon, sun, and stars. Only some of the larger towns have a bell tower that ring at regular hours. When meeting someone, you may have to wait.

**For a quick Reference chart see:
[Appendix A: Aowes Si Calendar](#p13)**

## Time Keeping
 - A year consists of 365 days (366 on a leap year).
 - Each year divided into 12 months of 30 days and 4 festivals (5 on a leap year)
 - Each month begins (roughly) the day after a New Moon, and consists of 3 weeks.
 - Each week, called a "tenday" is 10 days long.

## Festival Days

Festival Days occur between months and on average every three months.

### Imbolc

Ushered in by the blooming of *blackthorn* at the end of *Birch Moon*. Imbolc is celebration of the first day of spring. The celebrations are strongly associated with Brigid. Seen as time when she evolves from the Hag of Winter into the Maiden of Rivers.

The people celebrate with wearing wreaths, circles of flowers, and diving from animal behavior like badgers and serpents.

<div class='descriptive'>
The serpent will come from the hole
On the brown Day of Brídgit,
Though there should be three feet of snow
On the flat surface of the ground.
  
  ~Old Imbolc divination poem, stating if the Serpent leaves its hole then the snow will melt early.
</div>

### Beltaine

Beltaine marked the beginning of summer, the beginning of the "Light Half" of the year, after *Alder Moon*. It was when cattle were driven out to the summer pastures. 

Rituals were performed to protect the cattle, crops and people, and to encourage growth. Special bonfires were kindled, and their flames, smoke and ashes were deemed to have protective powers.The people and their cattle would walk around or between bonfires, and sometimes leap over the flames or embers.

These gatherings would be accompanied by a feast, and some of the food and drink would be offered to the Tuatha De Danann and wild fey. Doors, windows, byres and livestock were decorated with yellow flowers, sashes, or paint.

### Aban Artur (Leap Year Festival)

Follows Beltaine on leap years.

Traditionally the day was used for fairs, bazaars, musical and theatrical performances, and tournaments of skill and magical ability. Nobles usually held court to hear the petitions of their people and to make or renew trade pacts, alliances, and agreements.

The Uthgardt and Kelts would meet at the sacred mounds and celebrate their shared ancestry on Aban Artur.

### Lughnasadh

Lughnasadh marks harvest time, At the end of *Oak Moon*. Every celebrates in the bounty. It inspired great gatherings that included religious ceremonies, ritual athletic contests, feasting, matchmaking, and trading.

A bull (or two) are often ritually sacrificed and shared among all who come to entertain and be entertained by the festicities.

### Samhain

The day traditionally marked the onset of winter. At the end of *Ivy Moon*. The cattle were brought down from the summer pastures and penned in smaller fields. The last crops were harvested and stores of food and reserves prepared for the "Dark Half" of the year.

Some wild Fey, theirs emotions mirroring the changing times, would become inconsolable, even dark, or viciously hungry. One might disguise themselves in monstrous garb to trick the Fey into looking for an easier meal. This is also when the veil between the Other worlds is thin. Travelers from the Shadowfell might arrive in town, or vice versa.

<img src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/calendar-square.png?raw=true' style='position:absolute; object-fit: contain; height:350px;bottom:15px;right:30px;width:375px;mix-blend-mode:darken' />

<div class='pageNumber auto'></div>
<div class='footnote'>AOWES SI CALENDAR</div>
\page

# Keltic Pantheon
It is called the Keltic pantheon because that is the people the human settlers learned it from. These are the gods and goddesses worshipped amoung Tuathde (the Fey and Elves) of the Green Isles. Some of which are respresented in the Fearun pantheon as well.

Other Pantheons are worshipped througout The Green Isles as well.

**For a quick Reference chart see:
[Appendix B: Keltic Pantheon](#p14)**

> ##### Exarchs
> An exarch can be any Chosen, Demigod, Saint, archangel, or being of power that pledges their service to a particular Deity. The exarch gains no additional powers from this relationship as they are normally of considerable power already to earn the position.
>
> Unlike true deities, exarchs are not bound to live in Astral Dominions with their patrons. Many choose to live on the Material Plane, more directly engaged in the lives of their mortal followers.

## Deities

Tuatha De Danann means "Children of Danu".

### Danu

Also known as Chauntea, the Faerunian goddess of life and bounty, who viewed herself as the embodiment of all things agrarian. The Earthmother was seen as the tamer parallel of Silvanus, The Forest Father of druidry and wilderness, as she was the deity of agriculture and plant cultivation. She birthed the Tuatha De Danann.

### Belenus

Among Humans known as Lathander,"The Morning Lord" is gaining popularity. His saints are known among the towns for their miracles and destroying of monsters. Of which Saint Cuthbert is the most prevelant.

It is said Belenus and Danu (Chauntea and Lathander) fathered the Tuathde Danann.

### Ogma

Is the Faerûnian neutral greater deity of bards, inspiration, invention, and knowledge. And yet his worship among The Green Isles has existed for ages among the Tuatha De Danann. Fathering such Exarchs like **Diancecht (keltic god of medicine)**.
```
```
### Silvanus 

Is the Faerunian god of nature, and one of the oldest and most prominent gods in the pantheon. Formerly considered only the god of wilderness and druids, the Forest Father was often seen as the wilder counterpart to Chauntea the Earthmother.

### Cernunnos

Is the god of animals and forests, especially at night. He is chaotic neutral, but leans towards chaotic good. His chaotic nature represents the wildness of nature, and the dangers of the forest. The forests are ambivalent towards the suffering of the unwary travelers who find themselves trapped inside, but always leaves a path to survival for those who know the way. Cernunnos rarely directly aides mortals, but will often give those who are worthy the means of succeeding through their own effort.

He is patron of druids, centaurs, and satyrs. And the Exarch of Silvanus (who is suspected of being his father).

### Dagdha

Is the offspring of Danu and Lathander and a Deity in his own right. Yet he chooses to live as Danu's Exarch upon the Material plane. Teaching and supporting The Tuatha De Danann. He Fathered the The three Triumvirate Sisterhoods (in order of birth):
 - Eirinn, daughters of a Shiallia, A Fearun Korred goddess of fertility, pregnent forrest creatures and life.
 - Brigid, daughters of Fomorian sea goddess Umberlee.
 - Arawn, daughters of The Morrigan.
 
<img src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/goddess-square.png?raw=true' style='position:absolute; object-fit: contain; height:435px;bottom:30px;right:30px;width:375px;mix-blend-mode:darken' />
 
<div class='pageNumber auto'></div>
<div class='footnote'>KELTIC PANTHEON</div>
\page

### Aine

Also known as Selune, the goddess of the moon in the Faerûnian pantheon.Hers was the moon's mysterious power, the heavenly force that governed the world's tides and a mother's reproductive cycles, caused lycanthropes to shift form, and drew one to the brink of madness, and back again. Her nature, appearance, and mood all changed in turn with the phases of the moon. Her name was shared by the moon of Toril, Selûne;[3] it was unknown if the moon was named for the goddess or the goddess for the moon.[1] Regardless, most Faerûnian humans believed the moon to be the goddess herself watching over the world and the lights that trailed behind it to be her tears, from both joy and sorrow.

### The Morrigan

The Raven Queen is an unaligned patron-deity in the core pantheon, and she resides in the Shadowfell, also called the "Plane of Shadow." She was introduced in the Player's Handbook. The name of this goddess of death is long forgotten, but she is called the Raven Queen. She is the spinner of fate and the patron of winter. She marks the end of each mortal life, and mourners call upon her during funeral rites, in the hope that she will guard the departed from the curse of undeath. Any familiars you create that are related to her resemble ravens, and they are treated as such.

She expects her followers to abide by these commandments:

 - Hold no pity for those who suffer and die, for death is the natural end of life.
 - Bring down the proud who try to cast off the chains of fate. As the instrument of the Raven Queen, you must punish hubris where you find it.
 - Watch for the cults of Orcus and stamp them out whenever they arise. The Demon Prince of the Undead seeks to claim the Raven Queen's throne.

### Lir

Known around Fearun as Vulkar, the Captain of the Waves, was an exarch of Tempus, patron of sailors, ships, favorable winds, and naval combat.

### Triumvirate Sisterhoods
Some goddesses manifest themselves as a Triumverate Sisterhood. At least it can be confusing if they are the same entity or not. One is portrayed as a youthful girl, another as middle aged woman, and another as an old lady. The maiden, mother, and crone. The waxing, full, and waning moons.

This similiar to how the Noble Elandrin alter their appearence and abilities to best suit a "Season" they are currently feeling. In like fashion these goddesses change in respect to the the aspect they currently embody.

<div class='classTable wide'>
##### Keltic Pantheon
| Diety | Alignment | Domains | Symbol | Some Aliases | Also Fearun |
|:-----:|:---------:|---------|:------:|:------------:|:-----------:|
| Aine | CG | Knowledge, Twilight, Night | Pair of eyes surrounded by seven stars | Selune | ✔️ |
| Arawn ♻️ | NE | Explosives, Violent Death, Sudden Death | Tower overlaid with Lightningbolt | Young Lady Death, St. Barbara | - |
| Belenus | NG | Life, Light, Youth | Solar disk and standing stones | Lathander | ✔️ |
| Brigid ♻️ | CN | Rivers, Livestock (especially Horses), Winter Snow | Footbridge | - | - |
| Cernunnos | CN(G) | Hunting, Fishing, Nature | Red face with antlers | White stag | - |
| Dagdha | CG | Nature, Trickery | Bubbling cauldron or Shield | - | - |
| Danu | NG | Life, Agriculture | Sheaf of grain or a blooming rose over grain | Chauntea, Earthmother | ✔️ |
| Diancecht | LN | Medicine, Healing | Crossed oak and mistletoe branches | - | - |
| Eirinn ♻️ | CG | Lava Flows, Land, Shorelines | Harp | Eiru, Folda, Banba | - |
| Lir | CG | Sea, Tempest, Sailing | A cloud and three lightning bolts | Valkur | ✔️ |
| The Morrigan | LN | Battle, Death | Raven head | Raven Queen | ✔️ |
| Oghma | N | Knowledge | Unfurled scroll | - | ✔️ |
| Silvanus | CN | Wild Nature | Oak Leaf | Treefather | ✔️ |
  ♻️ Triumvirate Sisterhood
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>KELTIC PANTHEON</div>
\page

# Saltmarsh (Starting Area)
Nestled on the southern coast of the Eirinn is Saltmarsh, a sleepy fishing village that sits on the precipice of destruction. Smugglers guide their ships to hidden coves, willing to slit the throat of anyone foolhardy enough to cross their path. Cruel sahuagin from the Fomorian empire gather beneath the waves, plotting to sweep away coastal cities. Drowned sailors stir to unnatural life, animated by dark magic and sent forth in search of revenge. Amnian Loyalist, a secret cult of a forbidden god, and others extend their reach outward from the port towns intent on conquering The Green Isles. While Saltmarsh slumbers, the evils that seek to plunder it grow stronger. Heroes must arise to keep the waves safe!

## Important Figures
**Eda Oweland** - Eda is the current senior member of the town council, as well as the owner of three large fishing boats. She has lived in Saltmarsh all her life and has been elected to the council three times. She is suspicious of the dwarves’ mining enterprise and the increasing Amnian presence it brings.

**Eliander Fireborn** - Eliander fought in the army of Amn, where he earned a name driving out abberations and cultist away from the settled lands. Eliander suffered a tremendous injury to his leg in a battle against an owlbear and now walks with the use of a finely carved wooden cane.

Despite his injury and advancing age, the burly figure Eliander is a local celebrity thanks to his facility with languages, and he is often called upon by the town’s various organizations to assist with translations. He intends to settle in Saltmarsh and live out his life after retirement. Tho he knows how precurioous the Amnian and traditionalist relationship is. And his replacement may not be as understanding.

> ##### Got to pay the Bills.
> Eda Oweland, Eliander Fireborn, Gellan Primewater, Anders Solmor, and Manistrad Copperlocks are all town council members in Saltmarsh, and a good place to start looking for work.
> As well as the local shops and taverns in the area.
```
```
## Character Hooks

> ##### Forgotten Realms Reworked.
>The Green Isles are a collection of islands halfway across the Trackless Sea in *The Forgotten Realms*. The setting is inspired by Celtic myths and hibernian monsters. As such it borrows from the Moonshae Isle adventures or rewrites them.
>
>To eliminate confusion with the Moonshae Isles, The Green Isles replaces them. Do not use them as a canon source for this campaign.

### Backgrounds
**Saltmarsh Resident:** You can create a character using the optional backgrounds provided in *The Ghosts of Saltmarsh*. Get with the DM beforehand to make sure the background is incorporated into the whole campaign.

**Homecoming:** The character was kidnapped and sold into slavery by the Sea Princes. Growing up in a foreign land or aboard a ship, has earned their freedom and are returning home. Their families, if still alive assume the charcater is dead.

**In Debt or Criminal Trouble:** The character is feeling the heat of their less than honorable actions. They figure a land half rumored to be myth is a good place to escape to.

**Amnian Soldier or Marine:** You wouldn't be the first Amnian to settle in Saltmarsh.

**Quest for Knowledge:** A land from the beganning of time, Anceint Archfey, Giants who revolted against the Ordening, said to feel the weave brush against your hair as you walk around... Enough to entice any magic user seeking spells long lost or power easier to manifest.

**Seaborne:** You are a race from under the waves. Your leaders are losing a battle against the Fomorians, and ignore the land dwellers. But the oceans are used by both species and you suspect aid or allies can be garnered from the land dwellers in Saltmarsh.

<br>
**Image used:**  
Unknown by Unknown Artist taken from Wallpaperwikis.com

<img 
  src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/music-for-dragon-bottom.png?raw=true' 
  style='position:absolute;top:658px;left:0px;width:816px' />
  
<img 
  src='https://github.com/Tougher-Together-DnD/common-assets/blob/main/images/homebrewery/default-paper-stains/bottom.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:916px' />

<div class='pageNumber auto'></div>
<div class='footnote'>SALTMARSH (STARTING AREA)</div>
\page

### Five Factions
Sometimes characters die. One way of carrying on a charcters story, and impact in the world, past death is with using factions.

For instance: A player at the table rolls up and plays a human wizard. Who is a member of the Harper Faction investigating the Firbolg ruins of The Green Isles. During the adventure that wizard dies. The next character the player rolls is an assasin rogue, also from the Harper Faction tasked with discerning what has happened to the up and coming wizard.

**The Lords' Alliance:** A political and economic coalition of cities spread throughout the North and the Sword Coast. The alliance owes its success to effective cooperation and diplomacy between its members, who work to align their separate settlements toward a mutual purpose. This cooperation is easier during times of crisis, making the Lords' Alliance a powerful force when threats require a united front.

**The Harpers:** Members of this clandestine network of spellcasters and spies pride themselves on being incorruptible defenders of the greater good and champions of the oppressed. The organization is benevolent, knowledgeable, and secretive.
The Order of the Gauntlet

**The Order of the Gauntlet:** A dedicated, tightly knit group of holy-minded crusaders driven by a finely honed sense of duty and honor. They seek to uphold justice as best they can, and to continually test their mettle against the forces of evil.

**The Emerald Enclave:** The reach of the Emerald Enclave stretches far and wide across Faerun. Living deep in the wilderness demands great fortitude and the mastery of certain fighting and survival skills. The enclave is charged with defending sacred groves, protecting endangered beasts that cannot fend for themselves, and preserving the natural balance.

**The Zhentarim:** Members of the shadowy Black Network consider themselves part of an extended family, and rely on the larger organization for resources and security. Zhentarim bonds of oath and honor hold the network together and galvanize its members in united purpose. When a merchant caravan needs an escort, a noble needs bodyguards, or a city needs trained soldiers, the Zhentarim provides the best-trained fighting forces money can buy. 

> ##### The Five Factions.
> Listed here is a short summary of the factions used in Adventure League, but there is much canon written on them. There other factions and guilds that operate in *The Forgotten Realms*

<br>
**Image used:**  
"Lugh attacks the Fomor Army" by Jim Fitzpatrick

<img 
  src='https://github.com/Tougher-Together-DnD/invasion-of-eirinn/blob/main/Images/lugh-attacks-right.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:816px' />
  
<img 
  src='https://github.com/Tougher-Together-DnD/common-assets/blob/main/images/homebrewery/default-paper-stains/left-column.png?raw=true' 
  style='position:absolute;top:0px;left:0px;width:916px' />

<div class='pageNumber auto'></div>
<div class='footnote'>FIVE FACTIONS</div>
\page

# Appendix A: Aowes Si Calendar
<br>
**For more info see the article:
[Aowes Si Calendar](#p8)**

<div class='classTable wide'>
##### Aowes Si Calendar
| Semi-Harptos Month | Colloquial Description | Gregorian Month | Aowes Si Month |
|:------------------:|:----------------------:|-----------------|:--------------:|
| Hammer | Deepwinter | January | Birch |
| Greengrass | Festival | - | Imbolc |
| Alturiak | The Claw of Winter or Claws of the Cold | February | Rowan |
| Ches | The Claw of Sunsets | March | Ash |
| Tarsakh | The Claw of the Storms | April | Alder |
| Midsummer | Festival | - | Beltaine |
| Shieldmeet | Four year leapday | - | Aban Artur |
| Mirtul | The Melting | May | Willow |
| Kythorn | The Time of Flowers | June | Hawthorn |
| Flamerule | Summertide | July | Oak |
| Harvesttide | Festival | - | Lughnasa |
| Eleasias | Highsun | August | Holly |
| Eleint | The Fading | September | Hazel |
| Marpenoth | Leafall | October | Ivy or Vine |
| Feast of Moon | Festival | - | Samhain |
| Uktar | The Rotting | November | Reed |
| Nightal | The Drawing Down | December | Elder |
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>Appendix A: AOWES SI CALENDAR</div>
\page

# Appendix B: Keltic Pantheon
<br>
**For more info see the article:
[Keltic Pantheon](#p9)**

<div class='classTable wide'>
##### Keltic Pantheon
| Diety | Alignment | Domains | Symbol | Some Aliases | Also Fearun |
|:-----:|:---------:|---------|:------:|:------------:|:-----------:|
| Aine | CG | Knowledge, Twilight, Night | Pair of eyes surrounded by seven stars | Selune | ✔️ |
| Arawn ♻️ | NE | Explosives, Violent Death, Sudden Death | Tower overlaid with Lightningbolt | Young Lady Death, St. Barbara | - |
| Belenus | NG | Life, Light, Youth | Solar disk and standing stones | Lathander | ✔️ |
| Brigid ♻️ | CN | Rivers, Livestock (especially Horses), Winter Snow | Footbridge | - | - |
| Cernunnos | CN(G) | Hunting, Fishing, Nature | Red face with antlers | White stag | - |
| Dagdha | CG | Nature, Trickery | Bubbling cauldron or Shield | - | - |
| Danu | NG | Life, Agriculture | Sheaf of grain or a blooming rose over grain | Chauntea, Earthmother | ✔️ |
| Diancecht | LN | Medicine, Healing | Crossed oak and mistletoe branches | - | - |
| Eirinn ♻️ | CG | Lava Flows, Land, Shorelines | Harp | Eiru, Folda, Banba | - |
| Lir | CG | Sea, Tempest, Sailing | A cloud and three lightning bolts | Valkur | ✔️ |
| The Morrigan | LN | Battle, Death | Raven head | Raven Queen | ✔️ |
| Oghma | N | Knowledge | Unfurled scroll | - | ✔️ |
| Silvanus | CN | Wild Nature | Oak Leaf | Treefather | ✔️ |
  ♻️ Triumvirate Sisterhood
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>APPENDIX B: KELTIC PANTHEON</div>
\page

# Appendix C: Homebrew Rules

## Modified RAW
Occasionally the DM will adjust the Rules-As-Written (RAW). Listed here are some Homebrew modifications and their explanations.

### Attacking Climbing Creatures
**RAW:** Player's Handbook (pg. 191)
<div class='descriptive'>
Flying Movement
 
Flying creatures enjoy many benefits of mobility, but they must also deal with the danger of falling. If a flying creature is knocked prone, has its speed reduced to 0, or is otherwise deprived of the ability to move, the creature falls, unless it has the ability to hover or it is being held aloft by magic, such as by the fly spell.
</div>

**HOMEBREW:** In the same vein of thought as for flying movement, when attacking a climbing creature you can knock the creature to the ground if:
 - The attack knocks the creature prone
 - Reduces the spped of the creature to 0
 - Or is otherwise deprived of its ability to move (ie. contact the surface)
 
One caveat is a scenario where a web would restrain a creature dropping their movement to zero. Yet at the same time the web itself restrains the creature in place upon the wall.

### Crew Actions Players Roll Modifier
Please rever to the in game handouts for all the changes made to Officer and Crew Actions.

**Homebrew:** To increase the impact of a player choosing to take a Crew Action while aboard vehicles, after any required ability checks or To Hit checks made, the player can roll a 1d10 and add it to the effect. For example could be 1d10 feet added to Movement, or 1d10 damage added to Operate Weapon.

NPC crew add their Crew Moral as a flat modifier.

### Flanking
**RAW:** Dungeon Masters Guide (pg.251)
<div class='descriptive'>
Optional Rule: Flanking
  
If you regularly use miniatures, flanking gives combatants a simple way to gain advantage on attack rolls against a common enemy.
</div>
<div class='descriptive'>
A creature can’t flank an enemy that it can’t see. A creature also can’t flank while it is incapacitated. A Large or larger creature is flanking as long as at least one square or hex of its space qualifies for flanking.
  
Flanking on Squares. When a creature and at least one of its allies are adjacent to an enemy and on opposite sides or corners of the enemy’s space, they flank that enemy, and each of them has advantage on melee attack rolls against that enemy.
  
When in doubt about whether two creatures flank an enemy on a grid, trace an imaginary line between the centers of the creatures’ spaces. If the line passes through opposite sides or corners of the enemy’s space, the enemy is flanked.
</div>

**HOMEBREW:** To simplify applying Flanking, the following must be true: 
 - The line must intersect the center of the enemy area.
 - Both Attackers must be melee attacking it, or sufficiently getting its attention.

The effect of Flanking is to <mark>add +2</mark> to the attack roll. This doesn't wash out abilities that would grant advantage and the +2 is a fair trade for a tactical position. (think similar tactile positions like Cover.)

### Concussions
**HOMEBREW:** When a player reaches zero hit points and falls unconcious, they can be healed and brought back on their feet. Each time this occurs adds a level of exhaustion.

**RAW:** Player's Handbook (pg. 291)
<div class='descriptive'>
An effect that removes exhaustion reduces its level as specified in the effect's description, with all exhaustion effects ending if a creature's exhaustion level is reduced below 1.
  
Finishing a long rest reduces a creature's exhaustion level by 1, provided that the creature has also ingested some food and drink. Also, being raised from the dead reduces a creature’s exhaustion level by 1.
</div>

### Health Potions Give Max Value
**RAW:** Dungeon Master Guide (pg. 139)
<div class='descriptive'>
Potions are consumable magic items. Drinking a potion or administering a potion to another character requires an action.
</div>

**HOMEBREW:** Simply said Health potions give max value of die roll. Unlike previous Homebrew Rules, <mark>it requires an action to drink a potion RAW.</mark>

<div class='pageNumber auto'></div>
<div class='footnote'>APPENDIX C: HOMEBREW RULES</div>
\page

### Inspiration
**RAW:** Player's Handbook (pg.125)
<div class='descriptive'>
Inspiration is a rule the Dungeon Master can use to reward you for playing your character in a way that's true to his or her personality traits, ideal, bond, and flaw. By using inspiration, you can draw on your personality trait of compassion for the downtrodden to give you an edge in negotiating with the Beggar Prince. Or inspiration can let you calI on your bond to the defense of your home village to push past the effect of a spelI that has been laid on you...
  
lf you have inspiration, you can expend it when you make an attack rolI, saving throw, or ability check. Spending your inspiration gives you advantage on that roll!. Additionally, if you have inspiration, you can reward.
</div>

**HOMEBREW:** Inspiration is rewarded for good roleplay, creative ideas, or just for being awesome. RAW does not stack and there are already many ways a player can get advantage on a roll. This homebrew gives a pool of points for a player to use at any time they want.

The DM will roll a 1d6 for inspiration points, which the player can accumulate as a resource.

They do not expire for the duration of the campaign. When you make an attack roll, saving throw, or ability check you can adjust the die roll with a number of points from your inspiration pool.

Example: Your PC receives two rewards of inspiration from the DM. Two rolls of 1d6, 3 and 2 respectively. When the combat is intense and your PC has to leap across a gorge, while making the ability check you roll 11. After the roll you inform the DM you will use 4 out of 5 points of inspiration to make the roll a 15. Thereby leaping across the gorge.

### Instant Kills
**RAW:** Player's Handbook (pg.13)
<div class='descriptive'>
Your character's hit points define how tough your character is in combat and other dangerous situations.
</div>

**RAW:** Player's Handook (pg. 196)
<div class='descriptive'>
Hit points represent a combination of physical and mental durability, the will to live, and luck.
</div>

**HOMEBREW:** We have to understand that having 100 HP does not mean you can eat a grenade because it is written somewhere a grenade causes 2d6 dmg. We want the story to make sense and actions to have "believable" consequences. To keep the threat of death looming in the STORY while playing, if initiative has not been rolled Instant Death from damage is possible.

This means being killed in your sleep is a possibility. Which the party can mitigate by establishing a guard roster. You can sneak up and assassinate a NPC or Character, given you achieve all the required stealth rolls and Difficulty Checks. When the Villain holds a knife to a subdued character's neck, and threatens to kill them with a single slash, it is possible the character to have an Instant Death (DM may decide on rolling a percentage roll for extenuating circumstances).

### Optional Rule: Diagonals
**RAW:** Dungeon Master Guide (pg. 252)
<div class='descriptive'>
The Player’s Handbook presents a simple method for counting Movement and measuring range on a grid: count every square as 5 feet, even if you’re moving diagonally. Though this is fast in play, it breaks the laws of geometry and is inaccurate over long distances. This optional rule provides more realism, but it requires more effort during combat.
  
When measuring range or moving diagonally on a grid, the first diagonal square counts as 5 feet, but the second diagonal square counts as 10 feet. This pattern of 5 feet and then 10 feet continues whenever you’re counting diagonally, even if you move horizontally or vertically between different bits of diagonal Movement. For example, a character might move one square diagonally (5 feet), then three squares straight (15 feet), and then another square diagonally (10 feet) for a total Movement of 30 feet.
</div>

**HOMEBREW:** Implementing this. This method will be turned on in the game maps. By using this feature, accurate ranges to creatures flying or swimming can be calculated.

### Shape Shifting While Caged
**RAW:** Player's Handbook (pg.66)
<div class='descriptive'>
**Wild Shape**
  
You choose whether your equipment falls to the ground in your space, merges into your new form, or is worn by it. Worn equipment functions as normal, but the DM decides whether it is practical for the new form to wear a piece of equipment, based on the creature’s shape and size. Your equipment doesn’t change size or shape to match the new form, and any equipment that the new form can’t wear must either fall to the ground or merge with it. Equipment that merges with the form has no effect until you leave the form.
</div>

**RAW:** Dungeon Master Guide (pg.249)
<div class='descriptive'>
Improvising Damage
<table style="border: 1px solid black;">
  <th style="border: 1px solid black;">Dice</th><th style="border: 1px solid black;">Examples</th>
  <tr style="border: 1px solid black;">
    <td style="border: 1px solid black;">10d10</td>
    <td style="border: 1px solid black;">Crushed by compacting walls, hit by whirling steel blades, wading through a lava stream</td>
  </tr>
</table>
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>APPENDIX C: HOMEBREW RULES</div>
\page

**HOMEBREW:** When shape shifting, the player must have enough space to accommodate the new creature. If the character is caged, shape shifting can break the cage. The damage needed to break the cage is dealt to the new form. 5d10 bludgeoning per side (5ft section). If the cage is made with spikes pointing inward an additional 2d4 piercing is incurred for each spiked side.

Additionally, When carrying or holding magic items. Only magic items you are attuned with can merge with your shape.

### Shooting Prone
**RAW:** No rule changes the attacker's roll when prone.

**HOMEBREW:** For little realism, a Character can drop prone to <mark>add +2</mark> atop their non-spell ranged attacks. They still have to spend half movement to stand up again. This attempts to simulate the added precision a shooter gets when dropping their center of gravity and stabilizing their gun.

### Sleeping Counts as Paralyzed (unless magically induced)
**RAW:** Player's Handbook (pg.291)
<div class='descriptive'>
Paralyzed
 - A paralyzed creature is incapacitated (see the condition) and can't move or speak.
 - The creature automatically fails Strength and Dexterity saving throws.
 - Attack rolls against the creature have advantage.
 - Any attack that hits the creature is a critical hit if the attacker is within 5 feet of the creature.
</div>

**RAW:** Player's Handbook (pg.291)
<div class='descriptive'>
Unconscious
 - An unconscious creature is incapacitated, can't move or speak, and is unaware of its surroundings.
 - The creature drops whatever it's holding and falls prone.
 - The creature automatically fails Strength and Dexterity saving throws.
 - Attack rolls against the creature have advantage.
 - Any attack that hits the creature is a critical hit if the attacker is within 5 feet of the creature.
</div>

**HOMEBREW:** An unconcious creature is oblivious to their surroundings. A paralyzed creature can still hold onto things and sense their surroundings. Gameplay wise this means a sleeping creature is considered paralyzed and can still use their passive perception to wake up. From steps or noise around them.

However, an unconcious creature is oblivious and can only be woken up by taking damage, or someone shaking them awake. Magically induced slumbers apply the unconcious condition.

<div class='pageNumber auto'></div>
<div class='footnote'>APPENDIX C: HOMEBREW RULES</div>
\page

### Lingering Injuries
You may notice that many of the NPCs in this campaign have some permenant damage. The adventuring life is a hard one.

**HOMEBREW:** When an attack does one or more of the following to a creature:
 - Gets hit by a critical
 - Drops to zero hit points
 
<br>
<div class='classTable wide'>
##### Lingering Injury
| 2d4 + 1d12 | Result | Effect | Remedy |
|:----------:|:------:|:------:|:------:|
| 3-4 | Lose a Leg or Foot | Your walking speed is halved. You Fall prone after taking the *Dash* Action. You have disadvantage on Dexterity checks made to balance. | Prosthetic or *Regenerate* spell. |
| 5 | Lose an Eye | You have disadvantage on Wisdom (Perception) checks that rely on sight and on ranged attack rolls. If you have no eyes left after sustaining this injury, you're blinded. | Magical Seer Stone or *Regenerate* spell |
| 6 | Limp | Your walking speed is reduced by 10. You Fall prone after taking the *Dash* Action.| Using a cane in one hand, your walking speed is reduced by 5 and you no longer fall prone after the *Dash* action. This heals after 4 weeks of rest, or when you receive at least 100 points of magical healing. |
| 7-8 | Internal Bleeding | At the start of your turn (or each hour outside of combat), take 1d4 necrotic damage. | The bleeding can be stopped when you receive at least 50 points of magical healing, or a charge from a Healer's Kit |
| 9-14 | Minor Scar | You sustain a cosmetic scar. | Healed with *minor restoration* |
| 15-16 | Broken Ribs | Whenever you attempt the attack action, you must make a DC 10 Con save or lose the action. Expending the intended spell slot or ammo | This heals after 4 weeks of rest, or when you receive at least 50 points of magical healing. A charge from a Healer's Kit can be used to halve the remaining recovery time. |
| 17 | Pulled Shoulder | You can not use two-handed items. If you can only hold a shield or weapon in one hand. You have disadvanatge on Strength based rolls. | This heals after 4 weeks of rest, or when you receive at least 100 points of magical healing. |
| 18 | Horrible Scar | Your disfigurement gives you disadvantage on Persuasion and Insght checks | Magical healing of 6th level and higher can remove the scar. |
| 19-20 | Lose an Arm or Hand | You can no longer hold anything with two hands, and you can hold only a single object at a time, you do not have a free hand. | Prosethetic or *Regenerate* spell |

❇️ Magic such as the *regenerate* spell can restore lost body parts.
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>APPENDIX C: HOMEBREW RULES -LINGERING INJURIES</div>
