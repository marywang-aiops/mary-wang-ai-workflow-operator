# Payment Handling

Payment strategy: contact first, then send QR code.

## Public Wording

Use this wording in public pages:

`Payment is available by WeChat Pay or Alipay after scope confirmation. Email 939172168@qq.com to start.`

Chinese:

`确认服务范围后，可使用微信或支付宝付款。请先发邮件到 939172168@qq.com。`

## Private QR Code Storage

The QR codes are stored locally:

- `private/payment/wechat.jpg`
- `private/payment/alipay.jpg`

The whole `private/` folder is excluded by `.gitignore` and must not be published to GitHub.

## When To Send A QR Code

Send a payment QR code only after:

1. The buyer has described the workflow.
2. The audit scope is clear.
3. The buyer has agreed to the price.
4. The buyer knows what they will receive and when.

## Suggested Payment Email

Subject:

`Payment for AI Workflow Audit`

Body:

```text
Hi,

Thanks for confirming the AI Workflow Audit.

Scope:
[short scope]

Price:
RMB 699

Delivery:
Within 48 hours after payment and materials are confirmed.

You can pay by WeChat Pay or Alipay using the QR code attached to this email.

Please reply after payment with the payment screenshot and the materials for the audit.

Mary Wang
```

