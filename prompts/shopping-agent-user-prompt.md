Incoming trigger:

Telegram message:
{{telegramreceive.text}}

Scheduler trigger:
{{cronscheduler.timestamp}}

Behavior:
- If Telegram input exists, respond to the user request normally.
- If scheduler trigger exists, automatically scan tracked products from memory and look for deals.

Remember previously alerted deals.

Do not send repeated alerts for the same product unless:
- the price changes significantly
- stock status changes
- a much better deal appears
