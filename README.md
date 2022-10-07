# Projeto-do-GNPY

Adicionado new_model no json eqpt_config.
Adicionado elif para carregar o caminho da power_mask.
Adicionado feature 'power_mask_path' no default_values do Amp.
Adicionado variavel pow_mask_path(linha 187).
Adicionado variavel data(linha 243) para ser o json_data + o path do power_mask, ao invés de passar **json_data no return, agora passa **data.
Editado o arquivo edfa_example_network para substituir os std_low_gain pelo new_model_example.
Para acessar o path na função que o Allan tá fazendo: self.params.power_mask_path.
No _nf(do EDFA no elements.py) foi adicionado um elif na linha 706 para o novo type_def. 
