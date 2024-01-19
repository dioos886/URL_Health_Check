# URL_Health_Check
## URL批量存活检测工具

将收集的资产放入urls.txt

用法（必须要带-f）：
python3 URL_Health_Check.py -f urls.txt

检测结果会在result.csv文件中保存

![image](https://github.com/dioos886/URL_Health_Check/assets/31064101/f80349df-9b4d-4a98-b12e-9b825bc372c1)

2024年1月19日改进，在没有http协议情况下检测资产几乎是无法访问，增加协议判断
![image](https://github.com/dioos886/URL_Health_Check/assets/31064101/fd8704b0-c236-43e2-8681-5349c76fb3a6)
