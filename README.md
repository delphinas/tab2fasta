# tab2fasta
This is a python script to convert .xlsx (Microsoft Excel Open XML Spreadsheet) to FASTA format.



## **What is FASTA ?**

FASTA is a text-based format used in biochemistry and bioinformatics. It stores either nucletide sequences or amino acid sequences. Both are represented in the single-letter code.

An example of amino acid sequence in FASTA format:

```
>AMINO-ACID-SEQUENCE
MTEITAAMVKELRESTGAGMMDCKNALSETNGDFDKAVQLLREKGLGKAAKKADRLAAEG
LVSVKVSDDFTIAAMRPSYLSYEDLDMTFVENEYKALVAELEKENEERRRLKDPNKPEHK
IPQFASRKQLSDAILKEAEEKIKEELKAQGKPEKIWDNIIPGKMNSFIADNSQLDSKLTL
MGQFYVMDDKKTVEQVIAEKEKEFGGKIKIVEFICFEVGEGLEKKTEDFAAEVAAQL
```

```
>NUCLEOTIDE-SEQUENCE
ATGTTGTAGTAATGGTTGTAGGTTGTAGGTTGTTGTAGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTAGGTTGTGTTGTAGGTTGTAGGTTGTGTTGTAGGTTGTAGGTTGTGTTGTAGGTTGTAGGTTGTGTTGTAGGTTGTAGGTTGT
```



## **How to use it:**

Before you start, define the following:

* **my_file** = 'example.xlsx'
* **name_co**l = 'Name of the peptide/nucleotide **name** column'
* **seq_col** = 'Name of the peptide/nucleotide **sequence** column' 
* **output_filename** = 'example.fa'



## **Dependencies:**

* Python 3.*
* Pandas



## References:

* [Inspiration](http://seqanswers.com/forums/showthread.php?t=22147)
* [Wikipedia - What is Fasta](https://en.wikipedia.org/wiki/FASTA_format)

