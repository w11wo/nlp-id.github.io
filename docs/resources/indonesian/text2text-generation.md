# Text2Text Generation

!!! summary

    _The task of producing a shorter version of one or several documents that preserves most of the input's meaning_

## Models

| Name                                   | Description                                                                                                                                                                              | Author           | Link                                                                   |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------------------- |
| Indonesian T5 Small                    | T5 (Text-to-Text Transfer Transformer) model pretrained on Indonesian mC4 with extra filtering. This model is pre-trained only and needs to be fine-tuned to be used for specific tasks. | Akmal            | [HuggingFace](https://huggingface.co/Wikidepia/IndoT5-small)           |
| Indonesian T5 Base                     | T5 (Text-to-Text Transfer Transformer) model pretrained on Indonesian mC4 with extra filtering. This model is pre-trained only and needs to be fine-tuned to be used for specific tasks. | Akmal            | [HuggingFace](https://huggingface.co/Wikidepia/IndoT5-base)            |
| Indonesian T5 Large                    | T5 (Text-to-Text Transfer Transformer) model pretrained on Indonesian mC4 with extra filtering. This model is pre-trained only and needs to be fine-tuned to be used for specific tasks. | Akmal            | [HuggingFace](https://huggingface.co/Wikidepia/IndoT5-large)           |
| Paraphrase Generation with IndoT5 Base | IndoT5-base trained on translated PAWS.                                                                                                                                                  | Akmal            | [HuggingFace](https://huggingface.co/Wikidepia/IndoT5-base-paraphrase) |
| mT5 Large ID QGen QA                   | mT5 fine-tuned on SQuAD, XQuad, and Tydiqa                                                                                                                                               | Samsul Rahmadani | [HuggingFace](https://huggingface.co/munggok/mt5-large-id-qgen-qa)     |
