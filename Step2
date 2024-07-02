Step 2: Loading the model

llama_model = AutoModelForCausalLM.from_pretrained(pretrained_model_name_or_path = "aboonaji/llama2finetune-v2",
                                                   quantization_config = BitsAndBytesConfig(load_in_4bit = True, bnb_4bit_compute_dtype = getattr(torch, "float16"), bnb_4bit_quant_type = "nf4"))
llama_model.config.use_cache = False
llama_model.config.pretraining_tp = 1

