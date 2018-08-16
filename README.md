# cnnCNV
cnnCNV version 1.4.3b7, 20180504"
Program: cnnCNV_genImg
Contact: StudMs <dms@mail.buct.edu.cn>

usage: cnnCNV_genImg <bed_path> <bam_path> <sample_name> <out_dir> <tool_label>
example: </path/to/vcf.bed> </path/to/bam.bam> <NA12878> </path/to/output/> <delly/freec/cnvnator/readdepth/breakdancer>
Note: fields of bed
<chr> <left_breakpoint> <right_breakpoint> <copy_number_label>
file name of output img: /dir/<sample_name>-<chr>-<left_breakpoint>-<right_breakpoint>-<copy_number_label>-<length_of_cnv>-<tool_label>
