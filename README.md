# gbm
# means bold
## slightly less bold
in order to make code need to enter "tab"
always explain your code, put as much detail as possible so that you and others will know what you did
    
    blah blah blah
 # open terminal side by side with github   
 raw data is usually on our servers
 # pwd in terminal tells you where you are
 want to navigate to the data you want to open

 
 if youre using linux you right click on file and open in terminal
 
# check quality of reads
    fastqc is the program you call and and enter name of file, will offer names of files similar 
    using software installed it will do the thing
    puts report in the same folder you navigated to
    click the report and it will open
    check for adapter sequences, if there then trim of the sequence --> use a sequence trimmer software, most times aligner software willjust ignore adapter sequence 
 # download reference genome (most people still use hg38)
     use genome reference to align your reads
 # histat2
    after downloaded your reference genome
    to align the sequences against the genomix index 
    this is the actual program you call
    you need to put barcoding into the program
    have to specify read groups
    each read has its own barcoding but if you dont specify the barcode, you wont have any at the end --> specifying read groups helps preserve the barcodes
    everything is run in the same flowcell, billions of reads, demultiplex by sequencing each sample with barcoding differences
    barcoding = sample identification
        sequencing folks gives barcoding excel --> add it to histat2
        can look in the raw data file to barcoding if missing 
        side note: zcat command to get that (sample/file) | head
        barcoding index is with the nucleotide calls on the first line
        run the program
        
   
        
    
