**Let's play with ProP-PD results!**\
Let's say you made selection experiments with the bait: WW domain (Pfam accession PF00397) of the protein Histone-lysine N-methyltransferase SETD2 (UniProt accession Q9BYW2) against the RiboVD (RNA viruses disorderome) library. After your hard work you analised your data and found these peptides to be enriched:\
`AELNPPPYNHSYESLH`\
`NHHYAELNPPPYNHSY`\
`PPPYNHSYESLHPIPQ`\
`IPPPPPNGEDELVVSY`\
`PTPELVKKIPPPPPNG`\
`DWDEPPSYSDSRYGCY`\
`MPPPEYVPLTQVKGKA`\
`PDDDDIWMPPPEYVPL`\
`PDDDDLWMPPPEYVPL`\
`PNDDDLWLPPPEYVPL`\
`PPEYVPLTQVKGKASV`\
`PPSYSDSRYGCYPSAP`\
`NTYMQYLNPPPYADHG`\
`PPPYADHGANQLIPAD`\
`QYLNPPPYADHGANQL`\
`TAPPAYADIGYPMSML`\
`VTVPTAPPAYADIGYP`\
`PPPPPVPVDPQAQQMQ`\
`PVYYPPPPPVPVDPQA`\
`SIISNHHYAELNPPPY`\
`DLPSYPPKKEVSEWSD`\
`QSPSALPNYEPTPRIH`\
`TVEPPPPPAENLMTKP`\
`LDDDDLWLPPPEYVPL`\
`LGIAPPPYEEDTSMEY`\
`LPPPEYVPLAEITGKK`\
`LPPPEYVPLHEISSKG`\
`LPPPEYVPLKELTGKK`\
`LPPPEYVPLSEMTGKK`\
`LPPPEYVPLTEITGKK`\
`PDDDDLWLPPPEYVPL`\
`PPEYVPLTQIKGKENV`\
`VSFMDWDEPPSYSDSR`\
`SLVRVDDTISQPPRYA`\
`LPTYRYPLELDTANNR`\
`IILETPPPPATTTVIC`\
`TPPPPATTTVICEPTV`\
`ALPNYEPTPRIHIPGK`\
`NFPSTPPLTLPTTNLQ`\
`TMPPTYERVKDDSPPG`\
`KWNSSMDYDSPPSYQD`\
`PPPYDESCPMETQPSA`\
`PPPYEEDTSMEYAPSA`\
`MKSSPTAPPAYAAIPS`\
`PPLYAQEKRQDPIQHP`\
`EDAVLQRNKRRPTIIR`\
`HVDLENPIPPPRPKRA`\
`KYAEIILETPPPPATT`\
`PTAPPPEATNPPPYSP`\
`SSPSAPPSPSPPPYSP`\
`GGLSTVQLLCVFFLLW`\
`MEHSRERGRSSNMRHN`\
`GDPREPAPPAYSPADF`\
`MTLALNREYKPRRRRA`


**TOOL 1: Annotation with PepTools**\
To know from which viruses this peptides come from we'll use the annotation tool PepTools (https://slim.icr.ac.uk/tools/peptools/input). Check that you selected the correct "Species" group and if you want you can include the UniProt accession of the bait to let the tool check for previously published evidence of itneractions.\
(here's a link to a pre-run project in case it's taking too long: https://slim.icr.ac.uk/tools/peptools/results/annotations?jobId=03577d20b40bb6c2d5874cbdf413c139)

**TOOL 2: Expanding hits with SLiMSearch**\
Now that you have the `[LP]P.Y` regular expression describing the SLiM binding the WW domain from STED2, let's check if we can find more instances of the motif in a specific disorderome informatically using the tool SLiMSearch (https://slim.icr.ac.uk/tools/slimsearch/input).

**TOOL 3: Explore our published data in the ProP-PD portal**\
Finally, all of our mid-/high-confidence annotated binding results from ProP-PD selections can be found at the ProP-PD portal (https://slim.icr.ac.uk/proppd/). Check it!

**TOOL 4: Exploring motifs in MoMap**\
The MoMap database (https://slim.icr.ac.uk/momap/) compiles curated information from published works about motif instances. It's kind of "on the making" and we expect to publish it later this year! Here you can check for your bait (as the binding domain) or your binding peptides or even more generally for the known binders for the type of domain (WW, use the Pfam accession).

**Final task**\
Can you think of a way to use ProP-PD for your research project? What library would you use? Maybe you would need a new library? What baits?
