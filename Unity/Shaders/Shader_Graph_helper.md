
## Nodes
* **Split** - Օրինակ UV Map-ը կբաժանի 4 կանալի
* **One Minus** - 1-ից կհանի արժեքը
* **Fraction** - Օրինակ եթե **tillin and offset** node-ի tilling-ը **rectangle** node-ի համար չի աշխատում, սա դնելով միջանկյալ՝ կաշխատի
* **Blend** - Կարանք խառնենք գույները տարբեր ռեժիմներով
* **Smoothstep** - Կոնցենտրանցիանա կարգավորում։ Կարանք տանք Noise-ից հետո ու ռեզկստը փոխենք
* **Invert Colors** - Օրինակ շումի գույները տեղերով կփոխի
* **Normal From Height** - Height map-ը կդարձնի Normal map
* **Remap** - Օրիանակ շումի գուների պայծառություննա կարգավորում
* **Combine** - **Split**-ի հակառակը
* **Rectangle, Rounded Rectangle** - Սովորական ուղղանկյուն, կլորացրած եզրերով ուղղանկյուն
* **Step** - Եթե նշված արժեքից մեծա՝ 1, եթե փոքրա՝ 0
* **Length** - կտա վեկտորի երկարությունը
* **Triangle Wave** * - Սինուսոիդի նման ֆունկցիայա, բայց գծային անցումներով։ (0, -1), (0.5, 1), (1, -1)
* **Sample Texture** - Texture 2D Asset-ը ռեգուռովկա անելու համարա
* **Triplanar** - UV map չունեցնող օբյեկտի համար գեներացնում է այն
* **Saturation** - Օրինակ գունավոր տեքստուրը կարող ենք դարձնել սև-սպիտակ
* **Sample Gradient** - Կարանք in-ին տանք **gradient** ու **heigth map** և սև ու սպիտակը դարձնենք գրադիենտի գույներով
* **Projection** - A-ն պրոյեկտումա B-ի վրա
* **Scene Color** - Տալիսա կակ տը սցենայի գույնը, կարա կիսաթափանցիկ լինի, եթե pipeline-ի սեթինգսներից միացնենք opoque texture-ը: Եթե իրան տանք օրինակ screen position-ը, ապա կվերադարձնի տվյալ պիքսելի գույնը
* **Saturate** - Ստացած արժեքը սեղմումա 0_1 միջակայքում։ 

## Other
* **Normal map**-ն աշխատում միայն լույսի ուղիղ ճառագայթների դեպքում։ Որպեսզի այն աշխատի նաև լույս չընկնող հատվածներում, հարկավորա **Ambient Occlusion**-ին տալ **Height map**
* Թիվը միշտ կարող է վերածվել գույնի և հակառակը։ 0՝ սև, 1՝ սպիտակ
* **Smoothnees**-ին կարանք Heigth map տանք