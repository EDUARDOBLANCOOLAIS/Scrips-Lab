##### DESCARGAR LOS DATOS CRUDOS 

```wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_1/EBO_1_CKDL220014501-1A_HHMHJCCX2_L7_1.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_1/EBO_1_CKDL220014501-1A_HHMHJCCX2_L7_2.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_1/MD5.txt"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_2/EBO_2_CKDL220014502-1A_HHMHJCCX2_L7_1.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_2/EBO_2_CKDL220014502-1A_HHMHJCCX2_L7_2.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_2/MD5.txt"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_3/EBO_3_CKDL220014503-1A_HHMHJCCX2_L7_1.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_3/EBO_3_CKDL220014503-1A_HHMHJCCX2_L7_2.fq.gz"


wget "ftp://X202SC22062106-Z01-F002:y4bgp74t@usftp21.novogene.com:21/01.RawData/EBO_3/MD5.txt"```


···######## MAGGIE

CONSTRUIR GENOMA INDICES DE USCSC HUMANO

wget "https://hgdownload.soe.ucsc.edu/goldenPath/hg38/bigZips/hg38.fa.gz"

DESCOMPRIMIR 

gunzip hg38.fa.gz


conda activate hisat2-env


nohup hisat2-build /home/eblanco/sequencing/datos_crudos/genome_human/hg38.fa hg38 &
