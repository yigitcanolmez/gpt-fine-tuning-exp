# gpt-fine-tuning-exp

curl --location 'https://api.openai.com/v1/files' \
--header 'Authorization: Bearer ' \
--form 'purpose="fine-tune"' \
--form 'file=@"myJson.jsonl"'

curl --location 'https://api.openai.com/v1/fine_tuning/jobs' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer ' \
--data '{
    "training_file": "file-VmBJNn########",
    "model": "gpt-3.5-turbo"
  }'
  
  reminder

Fine-tuning jobs cannot be created on an Explore plan. You can upgrade to a paid plan on your billing page: https://platform.openai.com/account/billing/overview", 
  
