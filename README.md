# 出海管道 · OPC Global (`opc-global`)

> 一人公司出海跨国资金流动与全球支付合规指南  
> Global payment pipelines, Stripe verification, banking & tax compliance for indie builders.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/realchendahuang/opc-global/pulls)

---

## 设立宗旨

做独立开发和一人公司出海，写出产品往往只完成了 30%，剩下 70% 的坑集中在收钱、合规与资金流转：
- Stripe 账户因地址或经营范围不符遭无预警冻结；
- 离岸公司注册后忽视年度报税导致高额罚款；
- 海外美元无法合法合规结算至国内银行账户。

出海管道（OPC Global）致力于梳理真实跑通的全球资金与合规路径，破除信息不对称。

---

## 核心实战指南

### 1. 海外实体选型对照
- **美国怀俄明州 LLC（Wyoming）**：维护成本极低（年审 62 美元），匿名性强，无州所得税，适合绝大多数纯软件出海；
- **英国公司（UK Ltd）**：注册快（几小时）、成本透明，但需注意休眠申报与增值税（VAT）要求；
- **新加坡公司**：声誉极高，适合有规模化融资或东南亚本地业务需求的团队。

### 2. Stripe 开通与防封控 Checklist
- [ ] 官方落地页必须包含真实的 Support 邮箱、清晰的退款政策（Refund Policy）；
- [ ] 域名 WHOIS 隐私保护需合规，网站必须具备完整的服务条款（Terms of Service）；
- [ ] 避免测试期用自己的信用卡进行异常大额刷单，平稳渡过新手风控窗口。

### 3. 资金合规流转闭环
```text
用户信用卡 / Apple Pay 
  ➔ Stripe 结算 
  ➔ Wise Business / Mercury 商业银行账户 
  ➔ 跨境结汇通道（万里汇 / 连连 / 银行合规结汇） 
  ➔ 国内完税个人账户
```

---

## 附录资产

- `templates/terms-of-service.md`：中英双语 SaaS 标准服务条款
- `templates/privacy-policy.md`：符合 GDPR 规范的极简隐私政策

---

## License

MIT License. Copyright (c) 2026 realchendahuang.
