# TE-manual-curation

This is the database for manual curation of transposable elements.

#expanded-families folder

It contains the hmm (Hidden Markov Models) of expanded genes found in Mycorrhizal Fungi: Kinase domains, BTB/POZ (Broad-Complex, Tramtrack and Bric-a-brac/Poxvirus and Zinc finger) domains, Sel1-like tetratricopeptide repeats, and Kelch-like domains.
You can use it to search for these expanded families in your data by creating a hmmersearch database: hmmpress 01-expanded-genes.hmm, then apply hmmsearch in your data using these repeat databases.


#TE-domains folder

This folder contains several hmm profiles built based on alignments of domains described in the Supp-material S2 sheet.
All these profiles were combined in a single hmm file and it can be used as a database for hmmsearch in your data.


hmmpress 10-TE-domains-profiles.hmm

List of domains in 10-TE-domains-profiles.hmm: 
LINE,
PLE,
DIRS,
LTR,
LTR/Copia,
LTR/Bel,
LTR/Gypsy,
Helitron,
Crypton,
Academ,
CMC,
Ginger,
hAT,
Kolobok,
Merlin,
MULE,
Novosib,
P,
PIF-Harbinger,
PiggyBac,
Sola1,
Sola2,
Sola3,
Tc1-mariner,
Transib,
Zator,
Plavaka,
KDZ/Zizupton.
