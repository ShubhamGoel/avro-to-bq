1. Install apache beam for gcp using 
```
pip install apache-beam[gcp]
```
2. Create a table in Biguery and define schema. For this example 
```
Table Name : avrotable
dataset : detaset
schema : {name : STRING , post_abbr : STRING}
```
3. Edit the avrotobq.py according to your cloud project. 
4. Create a dataflow job by running 
```
python avrotobq.py
```
