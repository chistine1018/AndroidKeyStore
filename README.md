﻿# AndroidKeyStore
主要提供了三種功能：  
隨機產生Key  
限制Key的用途（加密、解密、認證⋯⋯）  
安全地存放Key  


RSA（非對稱加密）加密 AES 密鑰：  
KeyStore非對稱+對稱式加解密流程  
使用KeyStore產生隨機的RSA Key  
產生AES Key，並用RSA Public Key加密後存入SharedPrefs  
從SharedPrefs取出AES Key，並用RSA Private Key解密，用這把AES Key來加解密資料  



<img src="https://github.com/user-attachments/assets/a68f7e87-5c98-42ca-8471-d7dcb9de279f" width="300" alt="test1">

![image](https://github.com/user-attachments/assets/637bb2ee-3964-451d-b91a-cfa864521399)
