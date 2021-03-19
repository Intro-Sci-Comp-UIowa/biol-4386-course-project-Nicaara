## Data
SGD_stereum_alignment.fasta is the MAFFT alignment of the ITS sequences I (SGD) use in my manuscript. 
 * These sequences include the Stereum species:
    * S. fasciatum
    * S. lobatum
    * S. subtomentosum
    * S. complicatum
    * S. hirsutum
    * S. gausapatum
    * S. sanguinolentum
    * S. striatum
    * (Outgroup) Xylobolus subpileatus - Xylobolus is a genus in the Stereaceae
Stereum_all_1_MAFFT.fasta is a collection of sequences retreieved from GenBank using the sequences from SGD_stereum_alignment.fasta (and actually includes some of those reference sequences) 
 * This is my preliminary dataset. 
 * Next, I will pull *all* ITS sequences labeled as *Stereum*, discard any that are <375 base pairs, and discard any mislabeled as *Stereum* (similarity of less than 85% compared to the sequences in SGD_stereum_alignment.fasta).
