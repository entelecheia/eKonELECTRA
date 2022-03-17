# eKonELECTRA
Korean ELECTRA for Economic Analysis


```python
from transformers import AutoTokenizer, AutoModelForPreTraining

tokenizer = AutoTokenizer.from_pretrained("entelecheia/ekonelectra-base-discriminator")

model = AutoModelForPreTraining.from_pretrained("entelecheia/ekonelectra-base-discriminator")
```

```python
from transformers import AutoTokenizer, AutoModelForPreTraining

tokenizer = AutoTokenizer.from_pretrained("entelecheia/ekonelectra-small-discriminator")

model = AutoModelForPreTraining.from_pretrained("entelecheia/ekonelectra-small-discriminator")
```
