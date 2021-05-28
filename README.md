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
| 發生原因 / 解決方案 | IP Ratelimit | [Queue based load leviling](https://docs.microsoft.com/zh-tw/azure/architecture/patterns/queue-based-load-leveling) | 熔斷降級 | 縮短 timeout | 探針 | Auto-scale |
|---|---|---|---|---|---|---|
| endpoint timeout (表太大，第三方API問題 等) | - | O | O | O | - | -|  
| 服務無法訪問 | - | - | - | - | O | - | 
| CPU/MEM 耗盡 | O | O | O| - | - | O | 




## Monitoring
