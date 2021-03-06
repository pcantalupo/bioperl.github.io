---
title: BSML sequence format
layout: default
---

Description
-----------

BSML format for exchanging sequences and their meta-data.

This file format can be parsed by the system using the module.

Example
-------

```
<?xml version="1.0" encoding="UTF-8"?>
<?format DECIMAL="."?>
<!DOCTYPE Bsml PUBLIC "-//EBI//Labbook, Inc. BSML DTD//EN" "http://www.ebi.ac.uk/xembl/dtd/BSML2_2.DTD">
<Bsml>
<Definitions>
 <Sequences>
  <Sequence id="MIVN83300" ic-acckey="U83300" title="MIVN83300" comment="Veniliornis nigriceps strain LSU1305 cytochrome b gene, mitochondrial 
gene encoding mitochondrial protein, partial cds. " length="946" topology="linear" molecule="dna">
   <Attribute name="version" content="U83300.1" />
   <Attribute name="organism-species" content="Veniliornis nigriceps (bar-bellied woodpecker)" />
   <Attribute name="organism-classification" content="Eukaryota; Metazoa; Chordata; Craniata; Vertebrata; Euteleostomi; Archosauria; Aves;Neognathae; Piciformes; Picidae; Veniliornis" />
   <Attribute name="source" content="Veniliornis nigriceps LSU1305" />
   <Attribute name="date-created" content="14-MAY-1997" />
   <Attribute name="date-last-updated" content="4-MAR-2000" />
   <Attribute name="database-xref" content="UniProt/TrEMBL:O03345" />
   <Attribute name="database-xref" content="GOA:O03345" />
   <Feature-tables>
    <Feature-table>
     <Reference>
      <RefAuthors>`Moore W.S., DeFilippis V.R.`</RefAuthors>
      <RefTitle>`The window of taxonomic resolution for phylogenies based on mitochondrial cytochrome b`</RefTitle>
      <RefJournal>`(in) Mindell D.R. (eds.). AVIAN MOLECULAR EVOLUTION AND SYSTEMATICS:81-116. Academic Press, Inc., San Diego, CA, USA (1997)
      </RefJournal>
     </Reference>
     <Reference>
      <RefAuthors>`Moore W.S., DeFilippis V.R.`</RefAuthors>
      <RefJournal>`Submitted (27-DEC-1996) to the EMBL/GenBank/DDBJ databases. Biological Sciences, Wayne State University, Biological Sciences  `
 Building, Detroit, MI 48202, USA</RefJournal>
     </Reference>
     <Feature id="FTR_U83300.1_0" class="SOURCE" value-type="source" title="source" display-auto="1">
      <Qualifier value-type="strain" value="LSU1305" />
      <Qualifier value-type="organelle" value="mitochondrion" />
      <Qualifier value-type="organism" value="Veniliornis nigriceps" />
      <Qualifier value-type="db_xref" value="TAXONOMY:56076" />
      <Interval-loc startpos="1" endpos="946" />
     </Feature>
     <Feature id="FTR_U83300.1_1" class="CDS" value-type="cds" title="CDS" display-auto="1">
      <Qualifier value-type="product" value="cytochrome b" />
      <Qualifier value-type="codon_start" value="1" />
      <Qualifier value-type="translation"  
       value="XFGSLLGICLMTQIVTGLLLATHYTADTTLAFSSVAHTCRNVQYGWLIRNLHANGASFFFICIYLHIGRGFYYGSYLFKETWNTGVILLLTLMSSD
            ATAFVGYVLPWGQMSSWGATVITNLFSALPYVGQTIVEWAWGGFSVDNPTLTRFFXLHFLLPFLIXGLTLIHFTFLHESGSNNPLGIVSDXDKIPFX 
            PYFSXKDILGFMFMLLPLVXLALFSPNLLGDXENXTPANPLVTPPHIKPEWYFLFAYAILRSIPNKLGGVLALAASVLILFLAPLLHTSKQRTMAFRPM
            FSQLLFWMLVANLLILTWIGXQPXEHP" />
      <Qualifier value-type="db_xref" value="GOA:O03345" />
      <Qualifier value-type="db_xref" value="UniProt/TrEMBL:O03345" />
      <Qualifier value-type="db_xref" value="PID:AAB53618.1" />
      <Interval-loc startpos="1" endpos="946" startopen="1" endopen="1" />
     </Feature>
    </Feature-table>
   </Feature-tables>
   <Seq-data>aantttggatctctcctaggcatttgcctaataacacaaattgtcacagg
cctcctgcttgccacccactacactgccgacacaaccctagccttttctt
ccgtcgcccatacatgccgcaacgttcaatacggctgactaatccgtaac
ctccatgccaacggggcctcattctttttcatctgcatctacttacacat
cggacgtggattctactacggatcctacttatttaaagaaacttgaaaca
cgggagtcatccttctcctcaccctcatagccaccgccttcgtcggctac
gtcctcccctgaggacaaatatcatcctgaggagcaaccgttattacaaa
tttattctcagccctcccctacgtaggacaaactatcgtcgaatgagcct
gaggaggattctctgtagacaaccccactctcacccgattcttcgnccta
cactttctcctcccattcttaattgnaggactcaccctaattcacttcac
tttcctccacgaatccggntcgaacaatcccctcggaatcgtatccgaca
gngataaaatcccctttcanccctacttctccntaaaagatatcctagga
ttcatattcatactcctccccctcgtnnccctagcnctattctcacctaa
cctcctaggagaccnggaaaatttnacgcccgcaaaccccctagtnacac
ccccccacatcaaaccagaatggtacttcctatttgcatatgctatccta
cgctcaatccccaataaactaggaggagtcctagccctagctgcctcagt
cctaattctattcctagcccccctccttcatacatccaaacaacgcacga
tagccttccgacccttttcccaactcctattctgaatactagtcgccaac
ctcctcatcctcacctgaatcggnagncaaccagnagaacatccct
   </Seq-data>
   </Sequence>
  </Sequences>
 </Definitions>
</Bsml>
```
