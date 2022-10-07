# Projeto-do-GNPY

Adicionado new_model no json eqpt_config.

Adicionado elif no from_json(do Amp) para carregar o caminho da power_mask.

Adicionado feature 'power_mask_path' no default_values do Amp.

Adicionado variavel pow_mask_path(linha 187 do arquivo json_io).

Adicionado variavel data(linha 244 do arquivo json_io) para ser o json_data + o path do power_mask, ao invés de passar json_data no return, agora passa data.

Editado o arquivo edfa_example_network para substituir os std_low_gain pelo new_model_example.

Para acessar o path no interpol_params(no arquivo elements.py) na função que o Allan tá fazendo: self.params.power_mask_path.

No interpol_params(do EDFA no elements.py) foi adicionado um elif na linha 670 para o novo type_def. 
