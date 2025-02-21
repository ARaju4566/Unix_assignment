#UNIX Assignment

##Data Inspection

###Attributes of `fang_et_al_genotypes`

```
here is my snippet of code used for data inspection
wc fang_et_al_genotypes.txt

awk -F "\t" '{print NF; exit}' fang_et_al_genotypes.txt

du -h fang_et_al_genotypes.txt
```

By inspecting this file I learned that:
The fang_et_al_genotypes.txt file contains 2783 lines  2744038 words  11051939 characters 986 columns

###Attributes of snp_position.txt
~~~
here is my snippet of code used for data inspection
wc snp_position.txt

awk -F "\t" '{print NF; exit}' snp_position.txt

du -h snp_position.txt
~~~
By inspecting this file I learned that:
The snp_position.txt file has 984 lines 13198 words and 82763 characters and 15 columns 

###attributes if transpose_genotypes.txt
~~~
here is my snippet of code used for data inspection
wc transpose_genotypes.txt
~~~
 By inspecting this file I learned that transpose_genotypes.txt has 986 lines 2744038 words 11051939 characters
 




