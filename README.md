## 設定


rollor_in:滾輪decoder的訊號

chenSel:給Analog Switch切換用，chennel/4

en:給usb3取值用，high取值

tria:usb3同步訊號，確保在第0 chennel時抓值

totalChen:Analog Switch切換次數，chennel/4+1

delaydata:計數多少sp後重置

wen_total_count:rollor的上下緣各要產生多少wen，(每個rollor取的線數)x(Analog Switch切換次數+1)

sp_wen:wen的寬度，光源數+1

> 目前rollor是上下線時各產生一個plus去清除wen的計數
