# rMFilter
Acceleration of long read-based structure variation detection with chimeric read filtering

###Getting Start
	$ git clone https://github.com/tjiangHIT/rMFilter.git
	$ cd rMFilter
	$ make
	$ ./rMFilter-indexer indexDir ref.fa
	$ ./rMFilter-aligner indexDir read.fq > read.filter.fq
	
###Introduction

###Memory usage

The memory usage of rMFilter can fit the configurations of most modern servers and workstations.
Its peak memory footprint is about 18.00 Gigabytes (default setting), on a server with Intel Xeon CPU at 2.00 GHz, 1 Terabytes RAM running Linux Ubuntu 14.04. These reads were aligned to human reference genome GRCh37/hg19.


###Contact
For advising, bug reporting and requiring help, please contact ydwang@hit.edu.cn or tjiang@hit.edu.cn

