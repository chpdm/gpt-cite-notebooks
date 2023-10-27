# gpt-cite-notebooks

Example notebooks for calling GPT detect software mentions.

- `gpt-cite-examples-function-clean.ipynb`: Our first attempt at a notebook with vanilla `gpt-3.5-turbo`.
- `gpt-cite-examples-function-custom-model.ipynb`: Our second attempt which uses a custom/fine-tuned `gpt-3.5-turbo` model trained on these data: https://github.com/chpdm/softcite-data-prep

### Rationale 

For our first attempt, we discovered that we had essentially created a proper noun detector. It would identify not only software names but also terms such as 'Stanford University'.

Fine tuning a model using the Softcite seemed to significantly improve our ability to ignore anything other than software mentions ✨.

Part of: [Identifying missing software citations with LLMs](https://github.com/chpdm/SoftwareImpactHackathon2023_MINT-AI)
