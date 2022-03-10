# SCD1-Implementation-using-HIVE
Problem which we have here is upstream is sending one file daily in landing directory and we need to load data in mysql first. Once done take backup of mysql data and load data in HDFS.
Then load data in hive managed table which is truncate and load table evry time. Then load data in hive external table from other teas can take data and implement SCD1 and finally write data back to mysql and do reconcillation.

## Problem Statement:
![WhatsApp Image 2022-03-04 at 5 07 09 PM](https://user-images.githubusercontent.com/100192175/157570169-4b3b7f2a-667d-4263-a45b-1016795da8a5.jpeg)

## Directory Structure:
<img width="359" alt="image" src="https://user-images.githubusercontent.com/100192175/157570244-158c0eee-e596-4819-8750-2feafe081dad.png">

