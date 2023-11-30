# gpt-fine-tuning-exp

curl --location 'https://api.openai.com/v1/files' \
--header 'Authorization: Bearer ' \
--form 'purpose="fine-tune"' \
--form 'file=@"myJson.jsonl"'
