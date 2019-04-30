# EMVCo-SGQR-encode-decode-crc
about EMVCo SGQR encode decode crc
## 一、结果
原始报文：
https://github.com/hisenyuan/EMVCo-SGQR-encode-decode-crc/blob/master/src/main/java/com/hisen/emvco/docs/emvco-str.txt

emvco qr：

ps:product code

![emvco qr code](/src/com/hisen/emvco/img/emvco_qr_code[product].png)

## 二、功能
1. encode：crc加密得到可用的二维码数据;
2. decode：二维码数据解析，得到TLV(一种报文格式：Tag,Length,Value)，具体TLV的含义得结合相关文档;

## 三、文档
[emvco documents on this resp](https://github.com/hisenyuan/EMVCo-SGQR-encode-decode-crc/tree/master/src/main/java/com/hisen/emvco/docs)

## 四、说明
1. 本项目是SGQR(新加坡标准聚合二维码项目)相关调研;
2. SGQR基于emvco ISO标准;
3. 支持的国内第三方支付服务商有：支付宝、微信、银联;
4. 本项目中生成出来的二维码数据根据新加坡某真实商户的二维码解析、修改、生成而来，如果支付会产生真实的费用;
5. 如有相关问题欢迎探讨;