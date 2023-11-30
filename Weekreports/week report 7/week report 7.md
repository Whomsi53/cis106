***
Name: Wael Homsi
Course: CIS-106
Semester: Fall 23
---

# Week Report 7

### curl Command

>curl -O https://example.com/file.txt
>curl -o local_file.txt https://example.com/file.txt

### grep Command

>grep 'error' logfile.txt
>grep -c 'success' data.txt

### sort Command

>sort names.txt
>sort -r numbers.txt

### tr Command

>tr ' ' '_' < input.txt > output.txt
>tr -d '0-9' < data.txt > clean_data.txt

### awk Command

>awk -F',' '{print $2}' data.csv
>awk '{sum += $1} END {print sum}' numbers.txt
>awk '/error/' logfile.txt
>awk '{gsub(/old/, "new"); print}' input.txt
>awk 'length > 80' text.txt

### sed Command

>sed 's/apple/orange/' fruits.txt
>sed 'G' file.txt
>sed 's/ \+/ /g' text.txt
>sed 's/.*/\U&/' input.txt

