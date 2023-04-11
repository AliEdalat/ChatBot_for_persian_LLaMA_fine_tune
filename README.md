# ChatBot_for_persian_LLaMA_fine_tune
ChatBot for persian, fine tune LLaMa on instructed data (preprocessed alpaca dataset )

- we use [preprocessed alpaca dataset](https://github.com/thisserand/alpaca-lora-finetune-language.git) as dataset. we translate no_translate data to persian with [mt5](https://huggingface.co/persiannlp/mt5-large-parsinlu-translation_en_fa). ([train and test dataset](https://huggingface.co/datasets/AliEdalat/Persian_ChatBot_dataset_Fine_Tuning_Alpaca_Model) with 2k example is ready)
- we use LLaMA as generative model for create chatbot model. we fine-tune model with our persian dataset and test it.
- for improving ChatBot performance, replace "برای اینکه این کار را بکنم" with ""
