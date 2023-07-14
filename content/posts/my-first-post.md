---
title: "My First Post"
date: 2023-07-13T10:59:54+08:00
---
#ggg
smida
## Introduction

This is **bold** text, and this is *emphasized* text.

Visit the [Hugos](https://gohugo.io) website!

Raaa

* dddd
##body
**ssss**
https://www.markdownguide.org  f

>sadasdasdasddddddddd  
> hgjhgh

  

![sssssssdasdsasddddddddd](../../assets/647808a926617.jpg )  


\*如果没有开头的反斜杠字符的话，这一行将显示为无序列表。\
ssss\


ffff\
dddd
ddd\
ffff sss 
ssss  
ssss<br>
ssss<br>
ffff


    private function getPurchaseQuitOutRecordData($quitOutId){
    $quitOutInfo = QuitOut::query()->findOrFail($quitOutId)->toArray();
    $purchaseQuitOutRecordData = [
    'uniqueCode' => 1 ,//是	企业数据唯一标识
    'rtnTime' => 1 ,//是	退货日期（yyyy-MM-dd）
    'rtnNo' => 1 ,//是	退货单号
    'accNo' => 1 ,//是	原验收入库单号
    'rtnrsn' => 1 ,//是	退回原因
    'operName' => 1 ,//是	经手人
    'rePsnName' => 1 ,//是	复核人
    'breedList' => 1 ,//Array	是	药品购进退货品种关联对象
    
            ];
            $breedList[] = [
                'uniqueCode' => 1,//String	是	企业数据唯一标识
                'goodsId' => 1,//String	是	品种ID
                'quantity' => 1,//Number	是	退货数量
            ];
            return $purchaseQuitOutRecordData;
    
        }


![](../../assets/647808a926617.jpg)