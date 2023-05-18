python: 3.7
pip install -r requirements.txt
pip install scikit-learn  
pip install numpy
pip install transformers
pip install torch


Changes:
lcf_bert.py: 
- X from transformers.modeling_bert import BertPooler, BertSelfAttention 
- from transformers.models.bert.modeling_bert import BertPooler, BertSelfAttention