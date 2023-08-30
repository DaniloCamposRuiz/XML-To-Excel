Código para Extração de Informações de Notas Fiscais (NF-e)
Este é um script Python que extrai informações de arquivos XML de Notas Fiscais Eletrônicas (NF-e) e as organiza em um arquivo Excel.

Pré-requisitos
Certifique-se de ter os seguintes pacotes instalados em seu ambiente Python:

xmltodict
pandas
Você pode instalá-los usando o seguinte comando:

bash
Copy code
pip install xmltodict pandas numpy openpyxl
Como usar
Crie uma pasta chamada "nfs" no mesmo diretório onde este script está localizado.
Coloque os arquivos XML das Notas Fiscais que deseja processar na pasta "nfs".
Execute o script XmlToExcel.py.
O script irá analisar os arquivos XML na pasta "nfs", extrair informações como número da nota, empresa emissora, nome do cliente, endereço e peso, e em seguida, gerar um arquivo Excel chamado "NotasFiscais.xlsx" contendo uma tabela com essas informações.

Certifique-se de modificar o nome do arquivo de saída e os caminhos de acordo com suas necessidades.

Observações
Se o arquivo XML da NF-e estiver na estrutura padrão (NFe > infNFe), o script funcionará conforme esperado.
Se o arquivo XML estiver na estrutura comum de processamento (nfeProc > NFe > infNFe), o script também funcionará.
Caso você encontre problemas ao executar o script ou precise lidar com estruturas XML diferentes, ajustes podem ser necessários no código.

Lembre-se de que este é um script básico e pode não cobrir todos os cenários possíveis de arquivos XML de NF-e. Adaptações adicionais podem ser necessárias para atender a casos específicos.

Nota: Este README é uma descrição geral do funcionamento do script. Certifique-se de personalizá-lo de acordo com suas necessidades e incluir qualquer informação adicional relevante.
