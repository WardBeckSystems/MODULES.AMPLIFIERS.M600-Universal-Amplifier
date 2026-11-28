# M600 Universal Amplifier · Amplifiers

Ward-Beck Systems M600, 1967|0. Wiki page: [M600 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M600.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 97 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 14 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 27 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 209 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 5 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 30 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 69 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [19 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1970 - M600 - P003 - 1-1.jpg](MANUALS/1970%20-%20M600%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Transducer gain** | 50-70 dB, +/ -0.5 dB |
| **Frequency response** | +/ -0.25 dB from Hz greater than dB 20 kHz kHz |
| **Equivalent input noise** | -126 dBm (10 Hz ~128 dBm (10 Hz 100 kHz bandwidth) kHz bandwidth) |
| **Total harmonic distortion** | Less than 0.257 from Hz 20 kHz. Less than 0.59 from 20 Hz 20 kHz (Measured +30 dBm output level |
| **Source impedance** | 150/600 ohms balanced unbalanced |
| **Input impedance** | Greater than 10X source impedance |
| **Input level** | dBm norniinal -20 dBm max |
| **Load impedance** | 150/600 ohms balanced unbalanced |
| **Output impedance** | Less than 1/5 Load impedance |
| **Output level** | +30 dBm watt) max |
| **Phasing** | The low terminal number the input pair and the low terminal number the output pair are phase. |
| **Power requirements** | volts dc, regulated from M648 equivalent 100 MA watt output level |
| **Ambient temperature** | 60 degrees Celsius |
| **Dimensions** | wide mm 3.4&quot; high mm 336 Mi) deep |
| **Weight** | Ibs (1.4 kg) net |

## Circuit description

From [1970 - M600 - Audio Amplifer (2).pdf](MANUALS/1970%20-%20M600%20-%20Audio%20Amplifer%20(2).pdf) pages 6-11 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The &quot;1600 OUtput Impe'dance i s prima.. il y thai oft he de.....indlng ~sls l.. nce of out p Ul 1.... ns 'on'&gt;er 72.

T 2 p ri &quot;&quot;,r y o ff&quot; r sop timum ma 1chlng oft h e load 10 t h&quot; \/o l tage de ll\/e r&quot;d from the eml ter. oft h e ou~pu t circuit. Cl7 coup ' '''' the audio sig na ' 10 7 2 and prevents any d irec l current ' !&quot;Om flo....i n gin 7 2 primary.

Itl STALLATI Ofj

**1.16 00 AUO to AMPLIFIER**

The M600 plugs d i r «: lf y InlO I h~ MF 6 m,,\,mt!n9 frllR&gt;e which &quot;&quot;'I' b&quot; inS l a l led I n &quot; &quot; la&quot; da.. d ' 9 Inch equlp~nl.... c k wl lh I h., hllrdw,,~ supplied with the rack. The MF6 is furnished w i lh.. lull gu id&quot; c:omp tlrne&quot;. In order 10 accept 1I maximum of leo,,\600 amp li 'i.... &quot; or any combination o f &quot;i ng 'e or multiple width modules nOI exceeding 10 single width modules. II l he mO&quot;''' ling 'ra rne has been procured w i lh less receptacles, these mus l be installed in Ih e lIPPl&quot;'OPrl&quot; u: mod u '&quot; p o &quot;l lions.

Where y e r tlc a l racks pliCe p e,.,,,il sand Ih.. u lli mlll eIn noise lind cros stalk IS demanded, II Is,-&quot; (.o&quot; &quot;&quot; &quot;.. d,, d 10 &quot; I loca '&quot; only nood u 'e! o f I h e &quot;.. met yp e 10 ell c h l ndl \l lduo l MF6 rack Ira &quot;'... Alter nat el y If 1I powers u p ply Is.... q u l.... d to power twos ing le hlod u l.. M6 00 ll&quot;'p l Hie rs, the powers u p ply should b e ' n Sl n l led tot her ' g hl o f Ih e fr a n'e (n orm &quot;, I p r act ice vie....ed from r &quot; e l&lt; front) and me /!I&quot;,p l lf ier sIns t8 11&quot;d to I h e e &quot; treme left. When &quot;,1 &quot;l n9 an,pl ifer types In one fr llme, e x er-ct see &gt;&lt;l r e,&quot; e Care 10 sep e rote cab les o nd a d l'e re 10 proper

1g rounding conven llon s.

For optimum resu ll S, use In tiul /!lte d, shIelded I wist e d pairs for both ' n put and ou tp u l wiring. Cables operating with level differences e&gt;&lt;ceedl ng 2 S de should b e I&quot; e eds ep&quot; ra l e l y and dressed IIpllr l fro&lt; n each o lher and from power wiring.

Jumper term in,,1 9 (ch&quot;, s l ls ground I o f lilt &quot;mp ll fle r s orl II Co&lt;••&quot;on f..ame together and ecooec t n ' 18 A\'IG wire from each fr e me o f &quot; mp llfl e r s 10 the sys tetn ground bus. Hal&lt;e a...epa..e te connection from terminal 10 (c oorrnon l o f each amplifier 10 Ih e Iy s tetn ground bus. Th i $ will prevent cur..&quot;&quot;t coupling, noise and cr-ossreue.

Jump e.. l ermi n a l 2 (-tvl o f &quot; II &quot;,,,,p lllie.. son e CO&lt;'nl'-' f&quot;&quot;me together.. nd connect &quot; ' 18 AWG wire lro&lt;n e&quot;ch Ir &quot; me o f.. mp lllier&quot; tot he -t48 vo t t de powers u p ply term ln.. l.

Ind lvi d u,, 1 sys lems require ground tech n i ques pecu lia&quot; to each sys lem. P ref&quot; r &quot; blythe &quot;on e point &quot; ground system &quot;hou ld be cmn toyed 10 eli &quot;, l n ale ground loops. All Inputs hie lding should he Corl nce ted Individually tot erm i n &quot; l 6 (Inpu t ground) only; the Input $hie ld

ground i s internally c onnec led tot h e point of lowe l t pO len tla t and

carried through vial &quot; r min.. 1 10 tot h e sys letn ground.

The 1&gt;1600 15 designed fo.. depend &quot; b l e, l rouble - I..e e se.. v 1ce; how eve.., as w!lh nil high Qu&quot; ll lye lec t..on lc e q u l p &quot;,,,n t, 0 &quot;&quot;gu l;:... s che d u leo fIns p e&lt;:l lon should beeS I&quot; b li shed. Any IIcculll u l &quot; tl ono f d us l should be pe.. iodica lly.. ~ov &quot;d.....l lh a sof l b&quot;u s h linda v a CUUln hos &quot;.

The ee uve cin:u l l&quot; y may b&quot;..&quot;&quot;,oved fo.. Inspec llon by unplug gin g the SA 122 cin:uH boa.. d. Don ot Inse.. t 0.r-emove the companen l boa..d.....l lh the u nil &quot; n...-gl zed. ~f aull Is suspe&lt;:led, measu.. lng the de: voltage p..&quot;sen l all he t..ansi store tee r-eeee may a'nl5 t 10 d&quot;I&quot;..... lne lhe cause. When compad ng the I1'Ieasu..e&quot;&quot;e nI5 listed I,.. Ihe vol lage c b e.. t cOl'lside.. a lion should b e gi&quot;ero 10 I h e ' act t h &quot; l, for dl.-e&lt;: 1 coupled sec llons, ara u ll In one cln;u ll rna... Cause ab n ormlll i condil ions in e u-e.. cin:ul l,, &quot;ells.....i lh i n I h&quot; s.allle sec l lon.

If 11 Is n ec es s a..... 10 l n te..c h ange 1I c o mp onen l 10 d e le..,n in e Ih e cause o f a I IlUl t, fi..s l.. &quot;move Ihe sol de.. f&quot;olll Ih e p dn led c r..c u l t l oil fillets e esec t etee with Ih &quot; suspected del r.c l; v&quot; component. to cia I hl s, use &quot; 11ghl sold &quot;.. l n g Iron (2 5 wo ll S) i nco &quot;, o, n o l lon with on in e&gt;&lt;p..,n $ lv &quot; vacuum ac lion type h &quot; n d d&quot;so lde ring 100 1.

Place Ih e sol de.. lng iron and Ih e deso l derl ng 1001 on the solder conn ec lion 10 b e eeec tee-ee, When Ih e solder mel ls thoroughly, press Ihe plunger release Ir l g g...-. Apply Ih e soldering Iron on l he connecl ~ ion u n lit Ih e &quot;acuum s l..o ke has been comple led. If N1Y of I h e lead conn ec l lon s Slick 10 l hep rl n led etee cn boe rd, fr~ I t.c.m.....i lh ascribe ora similar sharp l... poin led inS lrumen l. Careful I... remove I h e CO&quot;&quot;ponen l which, jf proV M 10 be sal is fac lo....., rna... be used again fo.o l her app l ic a l lons.

Toto e rent t-e new component, Shape Ih e leads 10 Ih eco r..e CIs pacing. I n se &quot; l Ii'll! p a rI and fold the leads under Ih e pr ln led circuit board to fir&quot;, l... hold lI' eco &quot;,p one n l. Clip off t h &quot; c &gt;lce ss wire I&quot; &quot; v ln gob o,, ! 1/ 6 Inch. Sol d&quot;r tne new leads, using r~ s l nco r e solder and clean 11'1 &quot; board.....I thai n ert fluids uch a s pe rc hlort! l h e '...n&quot;.

The loc &quot; lIon o f C&lt;&gt;&lt;noonerots 15 sho.....n Indra.....i ng 0 122 _06_00 1.

**DC VOLT AGE CHART M I 22**

25 25.5

Ampllffer.... t lo r 50 dB gain.

**&quot;1600 AUDIO AMPLIFIER**

P I AMPLIFIER RECEPTACLE CONNECTIONS

**SOURCE IM&quot;'**

ISO ohms 1 108, I Sla 16 8 and 16

600 ohms e and 16

I np UI Shield Gnd.

**LOA O IMP EOANCE:**

ISO ohms) 10 4, 11 to 12

600,&gt;0.,,, GainS trap

+48\,1 DC z 0'0 to

**104600 AUDIO AMPLIFIER**

GAIN \I/s GAIN SET RESISTANCE

E 'A RESISTANCE VALUES FOR SPECIFIC GAIN

**58 I. ~ K**

60 910

**62 S60**

64 360 66 200

68 100

70 0

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTThlaDhGVlFBeUE/view?resourcekey=0-HNG5AoIdprZxVSi4iQRRmQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTThlaDhGVlFBeUE&resourcekey=0-HNG5AoIdprZxVSi4iQRRmQ" width="240" alt="1970 - M600 - wbsps - promo - m600 - 003.jpg"></a><br><sub>1970|3 · wbsps - promo - m600 - 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd281N1VZazNta1E/view?resourcekey=0-kF523pcbEWybQXkMyGbwBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd281N1VZazNta1E&resourcekey=0-kF523pcbEWybQXkMyGbwBA" width="240" alt="1970 - M600 - wbsps - promo - m600 - 004.jpg"></a><br><sub>1970|3 · wbsps - promo - m600 - 004</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1970|3 · wbsps - module - m600 - front_small](https://drive.google.com/file/d/0B0yR0b5T78SKMmJtNFcxc24wVm8/view?resourcekey=0-i1AATUFkdTRWPzwD16MBlA)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLTVWRFpUUE12UWs/view?resourcekey=0-e3jI-oomLJ66IQk_P5aFFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLTVWRFpUUE12UWs&resourcekey=0-e3jI-oomLJ66IQk_P5aFFw" width="240" alt="1970 - M600 - 600-04-010 - AUDIO AMPLIFIER PERSPECTIVE LAYOUT.jpg"></a><br><sub>1970|3 · 600-04-010 - AUDIO AMPLIFIER PERSPECTIVE LAYOUT · <a href="MECHANICAL/1970%20-%20M600%20-%20600-04-010%20-%20AUDIO%20AMPLIFIER%20PERSPECTIVE%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXhxN29ncENFX3c/view?resourcekey=0-e25W7z-HJUnRVizuj0rCqQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXhxN29ncENFX3c&resourcekey=0-e25W7z-HJUnRVizuj0rCqQ" width="240" alt="1970 - M600 - 600-04-010.jpg"></a><br><sub>1970|3 · 600-04-010 · <a href="MECHANICAL/1970%20-%20M600%20-%20600-04-010%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUlTVURTckZBczQ/view?resourcekey=0-XxefJ10yqSQGrJyOWkVf2g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUlTVURTckZBczQ&resourcekey=0-XxefJ10yqSQGrJyOWkVf2g" width="240" alt="19xx - M600 - DOC - wbsps - promo - mf6 mounting frame - front.jpg"></a><br><sub>19xx - M600 - DOC - wbsps - promo - mf6 mounting frame - front</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M600 - DOC - wbsps - module - mf6 mounting frame - front](https://drive.google.com/file/d/0B0yR0b5T78SKUFZLNEYyM21fTEk/view?resourcekey=0-PSphRmetzXxs0xCNu1BjOw)

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVUE1cjlEY0FjSWM/view?resourcekey=0-fzJb7NeGk6EUYvhmwS6yEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVUE1cjlEY0FjSWM&resourcekey=0-fzJb7NeGk6EUYvhmwS6yEQ" width="240" alt="1970 - M600 - 00-02-012 - AUDIO AMPLIFIER TYPICAL SYSTEM WIRING SCHEMATIC.jpg"></a><br><sub>1970|3 · 00-02-012 - AUDIO AMPLIFIER TYPICAL SYSTEM WIRING SCHEMATIC · <a href="SCHEMATICS/1970%20-%20M600%20-%2000-02-012%20-%20AUDIO%20AMPLIFIER%20TYPICAL%20SYSTEM%20WIRING%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVR6a3dRT19MWjQ/view?resourcekey=0-aX2ijDjI66Xv2RCPadpY5A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVR6a3dRT19MWjQ&resourcekey=0-aX2ijDjI66Xv2RCPadpY5A" width="240" alt="1970 - M600 - 122-02-001 - COM GAIN SET (2).jpg"></a><br><sub>1970|3 · 122-02-001 - COM GAIN SET (2) · <a href="SCHEMATICS/1970%20-%20M600%20-%20122-02-001%20-%20COM%20GAIN%20SET%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZUtuSkxjcGhFRmc/view?resourcekey=0-ppQqZs-RUIEIlkHbLbHfOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZUtuSkxjcGhFRmc&resourcekey=0-ppQqZs-RUIEIlkHbLbHfOg" width="240" alt="1970 - M600 - 122-02-001 - COM GAIN SET.jpg"></a><br><sub>1970|3 · 122-02-001 - COM GAIN SET · <a href="SCHEMATICS/1970%20-%20M600%20-%20122-02-001%20-%20COM%20GAIN%20SET%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFpaMGJNSlFJcDg/view?resourcekey=0-WKMZlidI1Fto_0JKNb0-FA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFpaMGJNSlFJcDg&resourcekey=0-WKMZlidI1Fto_0JKNb0-FA" width="240" alt="1970 - M600 - 122-06-012 - AMPLIFIER ASSEMBLY COMPONENT LAYOUT.jpg"></a><br><sub>1970|3 · 122-06-012 - AMPLIFIER ASSEMBLY COMPONENT LAYOUT · <a href="SCHEMATICS/1970%20-%20M600%20-%20122-06-012%20-%20AMPLIFIER%20ASSEMBLY%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFFSU0NkUDhOWmc/view?resourcekey=0-lMTFdtZCrk4EIRCYk84TSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFFSU0NkUDhOWmc&resourcekey=0-lMTFdtZCrk4EIRCYk84TSQ" width="240" alt="1970 - M600 - 122-06-012.jpg"></a><br><sub>1970|3 · 122-06-012 · <a href="SCHEMATICS/1970%20-%20M600%20-%20122-06-012%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOFJHV0V5LXQ0V0E/view?resourcekey=0-MZvernaCejaIwunNmPuXVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOFJHV0V5LXQ0V0E&resourcekey=0-MZvernaCejaIwunNmPuXVQ" width="240" alt="1970 - M600 - 600-02-010 - LOG SENSITIVITY CONTROL.jpg"></a><br><sub>1970|3 · 600-02-010 - LOG SENSITIVITY CONTROL · <a href="SCHEMATICS/1970%20-%20M600%20-%20600-02-010%20-%20LOG%20SENSITIVITY%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVl6el9MNnYzTlE/view?resourcekey=0-oa9Dk2Y_MNQPbw0bFrGQvw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVl6el9MNnYzTlE&resourcekey=0-oa9Dk2Y_MNQPbw0bFrGQvw" width="240" alt="1970 - M600 - 600-02-011 - PAO BOARD ASSY.jpg"></a><br><sub>1970|3 · 600-02-011 - PAO BOARD ASSY · <a href="SCHEMATICS/1970%20-%20M600%20-%20600-02-011%20-%20PAO%20BOARD%20ASSY%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKblgyRW5CQVJLOFU/view?resourcekey=0-sN7dAQtDJUKmqqA1fxGDGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKblgyRW5CQVJLOFU&resourcekey=0-sN7dAQtDJUKmqqA1fxGDGg" width="240" alt="1970 - M600 - 600-02-012 - INSULATED MOUNTING FRAME GROUND BAR AND CHASSIS.jpg"></a><br><sub>1970|3 · 600-02-012 - INSULATED MOUNTING FRAME GROUND BAR AND CHASSIS · <a href="SCHEMATICS/1970%20-%20M600%20-%20600-02-012%20-%20INSULATED%20MOUNTING%20FRAME%20GROUND%20BAR%20AND%20CHASSIS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnFUbktkbUtQcVU/view?resourcekey=0-y_xuMYxQ7cJjv4MRYVy3sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnFUbktkbUtQcVU&resourcekey=0-y_xuMYxQ7cJjv4MRYVy3sg" width="240" alt="1970 - M600 - 800-02-010 - AUDIO AMPLIFIER SCHEMATIC.jpg"></a><br><sub>1970|3 · 800-02-010 - AUDIO AMPLIFIER SCHEMATIC · <a href="SCHEMATICS/1970%20-%20M600%20-%20800-02-010%20-%20AUDIO%20AMPLIFIER%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1v_0UWew7dYh30XrDINJhvmJxirNEZ4XY/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1v_0UWew7dYh30XrDINJhvmJxirNEZ4XY" width="240" alt="1975 - 600-02-001 - AUDIO AMPLIFIER SCHEMATIC - DRN DM - ISS 14.jpg"></a><br><sub>1975|8 · 600-02-001 - AUDIO AMPLIFIER SCHEMATIC - DRN DM - ISS 14 · <a href="SCHEMATICS/1975%20-%20600-02-001%20-%20AUDIO%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%2014%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M600 - DOC - M600 - 600-02-003 - DOCUMENT](https://drive.google.com/file/d/0B0yR0b5T78SKbzFPMzQ3MnpXN1k/view?resourcekey=0-KXRDzVnJG-vFioaQ8RgXtQ) · [19xx - M600 - DOC - M600 - 600-06-001 - DOCUMENT](https://drive.google.com/file/d/0B0yR0b5T78SKc1pkdE9wVndpZGs/view?resourcekey=0-nUyqy3BVjjuk__lGeydGpw)

Not on Google Drive yet: `1970 - 600-02-005 - M600R SYSTEM FOR CDL A V SWITCHER APPLICATION.jpg`, `1987 - 600-02-001 - INPUT CHANNEL SCHEMATIC - DRN JRG - ENG JRG - ISS 1.png`, `1987 - 600-02-002 - STEREO OUTPUT CHANNEL SCHEMATIC - DRN JRG - ENG JRG - ISS 2.png`, `1987 - 600-02-003 - MONO OUTPUT CHANNEL SCHEMATIC - DRN JRG - ENG GEB - ISS 2.png`, `1987 - 600-02-004 - MONITOR SCHEMATIC - DRN JRG - ENG JRG - ISS 1.png`, `1987 - 600-02-005 - LINE SELECTORS SCHEMATIC - DRN JRG - ENG JRG - ISS 1.png`, `1987 - 600-02-007 - CUE CHANNEL SCHEMATIC - DRN JRG - ENG GEB - ISS 1.png`, `1987 - 600-02-008 - TALKBACK SCHEMATIC - DRN JRG - ENG JRG - ISS 1.png`, `1987 - 600-02-009 - POWER SUPPLY WIRING SCHEMATIC - DRN JRG - ENG JRG - ISS 1.png`, `19xx - 600-02-010 - AUDIO AMPLIFIER SCHEMATIC - ISS 1.jpg`, `19xx - 600-02-012 - AUDIO AMPLIFIER TYPICAL SYSTEM WIRING SCHEMATIC - ISS 1.jpg`, `19xx - 600-02-100 - M625B D TEST JIG SCHEMATIC (T625B) - DRN T. RICHARDSON - ENG T. RICHARDSON - ISS 1.png`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKajgyREdyNTA1bUE/view?resourcekey=0-F2ZbjMNiFR8wm3nyGytFSQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKajgyREdyNTA1bUE&resourcekey=0-F2ZbjMNiFR8wm3nyGytFSQ" width="240" alt="1970 - M600 - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC.jpg"></a><br><sub>1970|3 · 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC · <a href="PINOUTS/1970%20-%20M600%20-%20600-02-011%20-%20AUDIO%20AMPLIFIER%20OUTPUT%20STRAPPING%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1diTUX0kLAzPIB3jd9sLBW31VVorNAsNv/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1diTUX0kLAzPIB3jd9sLBW31VVorNAsNv" width="240" alt="1975 - 600-02-006 - EXTERNAL CONNECTIONS - DRN DM - ISS 1.jpg"></a><br><sub>1975|8 · 600-02-006 - EXTERNAL CONNECTIONS - DRN DM - ISS 1 · <a href="PINOUTS/1975%20-%20600-02-006%20-%20EXTERNAL%20CONNECTIONS%20-%20DRN%20DM%20-%20ISS%201%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC - ISS 3.jpg`, `19xx - M600 - M600 Audio Amplifier P1 Connector Layout 150 ohm strapping.jpg`

## RTO-144 pinout

Read from 5 pinout pictures (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- polarity assumed: 2 contacts given + / − that the drawing does not mark (e.g. P1-16 INPUT -) (M600: 1970 - M600 - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC.jpg)
- polarity assumed: 2 contacts given + / − that the drawing does not mark (e.g. P1-16 INPUT -) (M600: 19xx - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC - ISS 3.jpg)

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 2 | +48 V | power |  | high |
| 3 | OUTPUT A | out | OUTPUT | high |
| 4 | OUTPUT STRAP | strap |  | high |
| 6 | GAIN SET / INPUT SHIELD | strap | INPUT shield | high |
| 7 | INPUT STRAP | strap |  | high |
| 8 | INPUT A | in | INPUT | high |
| 9 | CHASSIS GROUND | ground |  | high |
| 10 | 48 V B- / COMMON | ground |  | high |
| 11 | OUTPUT B | out | OUTPUT | high |
| 12 | OUTPUT STRAP | strap |  | high |
| 14 | GAIN SET | strap |  | high |
| 15 | INPUT STRAP | strap |  | high |
| 16 | INPUT B | in | INPUT | high |

**Straps:** 600 OHM OUTPUT: P1-4 P1-12 · 600 OHM INPUT: P1-7 P1-15 · 150 OHM OUTPUT: P1-3 P1-4 · 150 OHM INPUT: P1-7 P1-8 · GAIN: P1-6 P1-14 · 7-15: P1-7 P1-15 · 6-14 3K9: P1-6 P1-14 · 4-12: P1-4 P1-12 · GAIN SET: P1-14 P1-6

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRzNPcG85ZEwwdDQ/view?resourcekey=0-xG8tXIUjk_LccPOWfmHriQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRzNPcG85ZEwwdDQ&resourcekey=0-xG8tXIUjk_LccPOWfmHriQ" width="240" alt="1970 - M600 - Audio Amplifer (2).pdf"></a><br><sub>1970|3 · Audio Amplifer (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRExGWE1KX0dXYTg/view?resourcekey=0-cq7mFuy_EHTORfZq0tq8mw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRExGWE1KX0dXYTg&resourcekey=0-cq7mFuy_EHTORfZq0tq8mw" width="240" alt="1970 - M600 - Audio Amplifer.pdf"></a><br><sub>1970|3 · Audio Amplifer</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRDVPN2lzdG5jTEU/view?resourcekey=0-NOuKp6qdlgjRZummh5e66w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRDVPN2lzdG5jTEU&resourcekey=0-NOuKp6qdlgjRZummh5e66w" width="240" alt="1970 - M600 - P003 - 1-1.jpg"></a><br><sub>1970|3 · P003 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa29zekpGUWlMMDQ/view?resourcekey=0-g1r42loZRTxVCGqEnz-Pzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa29zekpGUWlMMDQ&resourcekey=0-g1r42loZRTxVCGqEnz-Pzg" width="240" alt="1970 - M600 - P004 - 2-1.jpg"></a><br><sub>1970|3 · P004 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1B4eVV4dlM5ZEU/view?resourcekey=0-BKeiz8pvj8zD7-Wv8MOQTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1B4eVV4dlM5ZEU&resourcekey=0-BKeiz8pvj8zD7-Wv8MOQTQ" width="240" alt="1970 - M600 - P005 - 3-1.jpg"></a><br><sub>1970|3 · P005 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMWJlR181Qm4xTk0/view?resourcekey=0-RWc3JjS7rINGEODtS6VbZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMWJlR181Qm4xTk0&resourcekey=0-RWc3JjS7rINGEODtS6VbZg" width="240" alt="1970 - M600 - P006 - 3-2.jpg"></a><br><sub>1970|3 · P006 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOTIzbGFyaXBoUHc/view?resourcekey=0-Z0saFGOL-uBbrKZX4lspSg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOTIzbGFyaXBoUHc&resourcekey=0-Z0saFGOL-uBbrKZX4lspSg" width="240" alt="1970 - M600 - P007 - 4-1.jpg"></a><br><sub>1970|3 · P007 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWpiRjVMQmxZbTQ/view?resourcekey=0-epfIh-kJgs-GnX8hkuoXdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWpiRjVMQmxZbTQ&resourcekey=0-epfIh-kJgs-GnX8hkuoXdg" width="240" alt="1970 - M600 - P008 - 5-1.jpg"></a><br><sub>1970|3 · P008 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFRiNWRuTk5hbVU/view?resourcekey=0-Vc5zQgdhPiViUHfRiNboTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFRiNWRuTk5hbVU&resourcekey=0-Vc5zQgdhPiViUHfRiNboTA" width="240" alt="1970 - M600 - P009 - 6-1.jpg"></a><br><sub>1970|3 · P009 - 6-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1FFSkp1VjBQTms/view?resourcekey=0-lzPvdV8jNgNCS9Aq0fLLtg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1FFSkp1VjBQTms&resourcekey=0-lzPvdV8jNgNCS9Aq0fLLtg" width="240" alt="1970 - M600 - P010 - 7-1.jpg"></a><br><sub>1970|3 · P010 - 7-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUQwRjFwbXN6bUU/view?resourcekey=0-jma3A5w9Gvncv_xs4PSpmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUQwRjFwbXN6bUU&resourcekey=0-jma3A5w9Gvncv_xs4PSpmw" width="240" alt="1970 - M600 - P011 - 8-1.jpg"></a><br><sub>1970|3 · P011 - 8-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdDdLVVNkcXY3TWc/view?resourcekey=0-0CX27c9JIdU0-im1qW0Xzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdDdLVVNkcXY3TWc&resourcekey=0-0CX27c9JIdU0-im1qW0Xzg" width="240" alt="1970 - M600 - P012 - 9-1.jpg"></a><br><sub>1970|3 · P012 - 9-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHRiVUxuekxid2s/view?resourcekey=0-z_gj8wGvhAMFdZmUEXatzw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHRiVUxuekxid2s&resourcekey=0-z_gj8wGvhAMFdZmUEXatzw" width="240" alt="1970 - M600 - P013 - 9-2.jpg"></a><br><sub>1970|3 · P013 - 9-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRVoyYV9HNGpyQzA/view?resourcekey=0-z1wxt-lz6hwsydo2vvIZoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRVoyYV9HNGpyQzA&resourcekey=0-z1wxt-lz6hwsydo2vvIZoA" width="240" alt="1970 - M600 - P014 - 9-3.jpg"></a><br><sub>1970|3 · P014 - 9-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYTZidnVDTlhzQkU/view?resourcekey=0-dMidSc0qlqUEfHo6B7mISA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYTZidnVDTlhzQkU&resourcekey=0-dMidSc0qlqUEfHo6B7mISA" width="240" alt="1970 - M600 - P015 - 10-1.jpg"></a><br><sub>1970|3 · P015 - 10-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1pHQk5kSmIyTlk/view?resourcekey=0-LEqRv78-5KdwJBq4zp4-Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1pHQk5kSmIyTlk&resourcekey=0-LEqRv78-5KdwJBq4zp4-Lw" width="240" alt="1970 - M600 - P017 - 11-1.jpg"></a><br><sub>1970|3 · P017 - 11-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzRreWlBd1l2WlU/view?resourcekey=0-BL9JKFnHT2naE3Ck_SUzQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzRreWlBd1l2WlU&resourcekey=0-BL9JKFnHT2naE3Ck_SUzQA" width="240" alt="1970 - M600 - Ward Beck Systems M600 b.jpg"></a><br><sub>1970|3 · Ward Beck Systems M600 b</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMlBTTHBsWHRBeXM/view?resourcekey=0-SezfuZR9kZhUujDW4kn3SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMlBTTHBsWHRBeXM&resourcekey=0-SezfuZR9kZhUujDW4kn3SA" width="240" alt="1970 - M600 - Ward Beck Systems M600.jpg"></a><br><sub>1970|3 · Ward Beck Systems M600</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3JiVTByNlp3dnM/view?resourcekey=0-TLjmXjXK4d5a8WLQMAg2IQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3JiVTByNlp3dnM&resourcekey=0-TLjmXjXK4d5a8WLQMAg2IQ" width="240" alt="1970 - M600 - wbsps - promo - m600 - front.jpg"></a><br><sub>1970|3 · wbsps - promo - m600 - front</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M600 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3lwMHVRalBZcnM/view?resourcekey=0-4JRMi_4sTzheUS899drXIA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3lwMHVRalBZcnM&resourcekey=0-4JRMi_4sTzheUS899drXIA" width="240" alt="1987 - M600 - P001 - Title Page.jpg"></a><br><sub>1987|20 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzVBVVQ2bTZqVnM/view?resourcekey=0-repGA0g2M-cYjkNLkdVC3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzVBVVQ2bTZqVnM&resourcekey=0-repGA0g2M-cYjkNLkdVC3g" width="240" alt="19xx - M600 - DOC - 7000 series - 001 (2).jpg"></a><br><sub>19xx - M600 - DOC - 7000 series - 001 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmpjMlhlWWFVN2s/view?resourcekey=0-w3Y1UUp--G6NBkxFWSM2kg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmpjMlhlWWFVN2s&resourcekey=0-w3Y1UUp--G6NBkxFWSM2kg" width="240" alt="19xx - M600 - DOC - 7000 series - 001.jpg"></a><br><sub>19xx - M600 - DOC - 7000 series - 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWJVRFZCOWs4Uk0/view?resourcekey=0-ZJor6LD49vuAcIvMSiy5cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWJVRFZCOWs4Uk0&resourcekey=0-ZJor6LD49vuAcIvMSiy5cg" width="240" alt="19xx - M600 - DOC - 7000 series - promo - 002.jpg"></a><br><sub>19xx - M600 - DOC - 7000 series - promo - 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa3Z1TElRTy1WWGs/view?resourcekey=0-Gfu4moQPp0YgnxvHPqrpig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa3Z1TElRTy1WWGs&resourcekey=0-Gfu4moQPp0YgnxvHPqrpig" width="240" alt="19xx - M600 - DOC - US Sales Brochure pg 2.jpg"></a><br><sub>19xx - M600 - DOC - US Sales Brochure pg 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFJvOWdfR1lGSnM/view?resourcekey=0-i3np6j3RFFkqPP8iEkeKrA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFJvOWdfR1lGSnM&resourcekey=0-i3np6j3RFFkqPP8iEkeKrA" width="240" alt="19xx - M600 - DOC - US Sales Brochure pg 7.jpg"></a><br><sub>19xx - M600 - DOC - US Sales Brochure pg 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEdXWktjYjVqaGs/view?resourcekey=0-DzOvvo6HkagzpGqoC-g3VA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEdXWktjYjVqaGs&resourcekey=0-DzOvvo6HkagzpGqoC-g3VA" width="240" alt="19xx - M600 - DOC - US Sales Brochure pg 9.jpg"></a><br><sub>19xx - M600 - DOC - US Sales Brochure pg 9</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWhnM3l1NUNsM0E/view?resourcekey=0-hb6wbOZu8-jiM2d9WGqejQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWhnM3l1NUNsM0E&resourcekey=0-hb6wbOZu8-jiM2d9WGqejQ" width="240" alt="19xx - M600 - DOC - Ward Beck Systems MF6.jpg"></a><br><sub>19xx - M600 - DOC - Ward Beck Systems MF6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM09MSGZTbG1najA/view?resourcekey=0-CdUJhT2w3TBOWyw-3_hUIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM09MSGZTbG1najA&resourcekey=0-CdUJhT2w3TBOWyw-3_hUIg" width="240" alt="19xx - M600 - DOC - promo - 7000 series - 002.jpg"></a><br><sub>19xx - M600 - DOC - promo - 7000 series - 002</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1970|3 · wbsps - module - m600 - front](https://drive.google.com/file/d/0B0yR0b5T78SKWmFCc1F0QVI3SUE/view?resourcekey=0-VYudnE311AFjTZouFHIF4Q)

Not on Google Drive yet: `1967 - 60-4 - 60-4 INPUT TRANSFORMER.png`, `19xx - M600 - M600 (3).jpg`, `19xx - M600 - M600.jpg`, `M600 - P002.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1970 - 600-02-005 - M600R SYSTEM FOR CDL A V SWITCHER APPLICATION.kicad_sch](KICAD/1970%20-%20600-02-005%20-%20M600R%20SYSTEM%20FOR%20CDL%20A%20V%20SWITCHER%20APPLICATION.kicad_sch)
- [1970 - M600 - 00-02-012 - AUDIO AMPLIFIER TYPICAL SYSTEM WIRING SCHEMATIC.kicad_sch](KICAD/1970%20-%20M600%20-%2000-02-012%20-%20AUDIO%20AMPLIFIER%20TYPICAL%20SYSTEM%20WIRING%20SCHEMATIC.kicad_sch)
- [1970 - M600 - 122-02-001 - COM GAIN SET (2).kicad_sch](KICAD/1970%20-%20M600%20-%20122-02-001%20-%20COM%20GAIN%20SET%20(2).kicad_sch)
- [1970 - M600 - 122-02-001 - COM GAIN SET.kicad_sch](KICAD/1970%20-%20M600%20-%20122-02-001%20-%20COM%20GAIN%20SET.kicad_sch)
- [1970 - M600 - 600-02-010 - LOG SENSITIVITY CONTROL.kicad_sch](KICAD/1970%20-%20M600%20-%20600-02-010%20-%20LOG%20SENSITIVITY%20CONTROL.kicad_sch)
- [1970 - M600 - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC.kicad_sch](KICAD/1970%20-%20M600%20-%20600-02-011%20-%20AUDIO%20AMPLIFIER%20OUTPUT%20STRAPPING%20SCHEMATIC.kicad_sch)
- [1970 - M600 - 600-02-011 - PAO BOARD ASSY.kicad_sch](KICAD/1970%20-%20M600%20-%20600-02-011%20-%20PAO%20BOARD%20ASSY.kicad_sch)
- [1970 - M600 - 600-02-012 - INSULATED MOUNTING FRAME GROUND BAR AND CHASSIS.kicad_sch](KICAD/1970%20-%20M600%20-%20600-02-012%20-%20INSULATED%20MOUNTING%20FRAME%20GROUND%20BAR%20AND%20CHASSIS.kicad_sch)
- [1970 - M600 - 800-02-010 - AUDIO AMPLIFIER SCHEMATIC.kicad_sch](KICAD/1970%20-%20M600%20-%20800-02-010%20-%20AUDIO%20AMPLIFIER%20SCHEMATIC.kicad_sch)
- [1970 - M600 - Audio Amplifer (2) p21.kicad_sch](KICAD/1970%20-%20M600%20-%20Audio%20Amplifer%20(2)%20p21.kicad_sch)
- [1970 - M600 - Audio Amplifer (2) p27.kicad_sch](KICAD/1970%20-%20M600%20-%20Audio%20Amplifer%20(2)%20p27.kicad_sch)
- [1970 - M600 - Audio Amplifer p19.kicad_sch](KICAD/1970%20-%20M600%20-%20Audio%20Amplifer%20p19.kicad_sch)
- [1970 - M600 - Audio Amplifer p21.kicad_sch](KICAD/1970%20-%20M600%20-%20Audio%20Amplifer%20p21.kicad_sch)
- [1975 - 600-02-001 - AUDIO AMPLIFIER SCHEMATIC - DRN DM - ISS 14.kicad_sch](KICAD/1975%20-%20600-02-001%20-%20AUDIO%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%2014.kicad_sch)
- [1975 - 600-02-006 - EXTERNAL CONNECTIONS - DRN DM - ISS 1.kicad_sch](KICAD/1975%20-%20600-02-006%20-%20EXTERNAL%20CONNECTIONS%20-%20DRN%20DM%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-001 - INPUT CHANNEL SCHEMATIC - DRN JRG - ENG JRG - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-001%20-%20INPUT%20CHANNEL%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-002 - STEREO OUTPUT CHANNEL SCHEMATIC - DRN JRG - ENG JRG - ISS 2.kicad_sch](KICAD/1987%20-%20600-02-002%20-%20STEREO%20OUTPUT%20CHANNEL%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%202.kicad_sch)
- [1987 - 600-02-003 - MONO OUTPUT CHANNEL SCHEMATIC - DRN JRG - ENG GEB - ISS 2.kicad_sch](KICAD/1987%20-%20600-02-003%20-%20MONO%20OUTPUT%20CHANNEL%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20GEB%20-%20ISS%202.kicad_sch)
- [1987 - 600-02-004 - MONITOR SCHEMATIC - DRN JRG - ENG JRG - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-004%20-%20MONITOR%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-005 - LINE SELECTORS SCHEMATIC - DRN JRG - ENG JRG - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-005%20-%20LINE%20SELECTORS%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-007 - CUE CHANNEL SCHEMATIC - DRN JRG - ENG GEB - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-007%20-%20CUE%20CHANNEL%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20GEB%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-008 - TALKBACK SCHEMATIC - DRN JRG - ENG JRG - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-008%20-%20TALKBACK%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%201.kicad_sch)
- [1987 - 600-02-009 - POWER SUPPLY WIRING SCHEMATIC - DRN JRG - ENG JRG - ISS 1.kicad_sch](KICAD/1987%20-%20600-02-009%20-%20POWER%20SUPPLY%20WIRING%20SCHEMATIC%20-%20DRN%20JRG%20-%20ENG%20JRG%20-%20ISS%201.kicad_sch)
- [19xx - 600-02-010 - AUDIO AMPLIFIER SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20600-02-010%20-%20AUDIO%20AMPLIFIER%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [19xx - 600-02-011 - AUDIO AMPLIFIER OUTPUT STRAPPING SCHEMATIC - ISS 3.kicad_sch](KICAD/19xx%20-%20600-02-011%20-%20AUDIO%20AMPLIFIER%20OUTPUT%20STRAPPING%20SCHEMATIC%20-%20ISS%203.kicad_sch)
- [19xx - 600-02-012 - AUDIO AMPLIFIER TYPICAL SYSTEM WIRING SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20600-02-012%20-%20AUDIO%20AMPLIFIER%20TYPICAL%20SYSTEM%20WIRING%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [19xx - 600-02-100 - M625B D TEST JIG SCHEMATIC (T625B) - DRN T. RICHARDSON - ENG T. RICHARDSON - ISS 1.kicad_sch](KICAD/19xx%20-%20600-02-100%20-%20M625B%20D%20TEST%20JIG%20SCHEMATIC%20(T625B)%20-%20DRN%20T.%20RICHARDSON%20-%20ENG%20T.%20RICHARDSON%20-%20ISS%201.kicad_sch)
- [19xx - M600 - DOC - M600 - 600-02-003 - DOCUMENT.kicad_sch](KICAD/19xx%20-%20M600%20-%20DOC%20-%20M600%20-%20600-02-003%20-%20DOCUMENT.kicad_sch)
- [M600.kicad_sym](KICAD/M600.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
