# Microservices 
# Why Microservices instead of Monolith structure
  * A small change might affects everything. 
  * Hard to refactor or upgrade
  * Complex git branches
  * Modules still depends on each other.
  * Reusing Service instead of Reusing Code.
  * Cross Language and Team.

# What issues will be faced
## How to separate into services

## Traffic between services


## Distributed transaction 


## Distributed tracing

## Non-stop deployment
## Avoiding avalanche affect
| 可能發生原因 | 解決方案 | 
|---|---|
| endpoint timeout (表太大，第三方響應慢) | 縮短 timeout / 熔斷 | 
| 服務死掉 | 探針 | 
| CPU/MEM 耗盡 | Auto-scale / [Queue based load leviling](https://docs.microsoft.com/zh-tw/azure/architecture/patterns/queue-based-load-leveling) | 

解決方案
|| 熔斷 | 節流|
|---|---|---|
|優點|  | |
|缺點| 一個 endpoint 問題，移除整個服務 | |



## Monitoring
