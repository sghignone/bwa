# BWA
The Burrow-Wheeler Aligner for short-read alignment, build from bioconda

Release 0.7.17 (23 October 2017)
--------------------------------
This release adds option -q to preserve the mapping quality of split alignment with a lower alignment score than the primary alignment. Option -5 automatically applies -q as well.

(0.7.17: 23 October 2017, r1188)

## Note
WORKDIR	/scratch

## Usage

docker run --rm -it -v 'path to your local dir':/scratch sghignone/bwa bwa (options)
