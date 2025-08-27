cd Documentos
mkdir pipeline_dados
Pastas:
    data_processed
    data_raw
    notebooks
    scripts

sudo apt-get update
sudo apt-get upgrade -y
python3 --version
python3 -V
sudo apt install python3-pip -y
sudo apt install python3-venv -y

# Crie um ambiente virtual com o comando 'python3 -m venv nome_do_ambiente'
python3 -m venv nome_do_ambiente

# Ative o ambiente virtual com o comando 'source nome_do_ambiente/bin/activate'

source myvenv/bin/activate
deactivate

No venv - Ambiente Virtual do Python
pip install requests==2.28.2
pip install pandas==2.0.0
pip install notebook==7.0.3

wget [opções] [URL]

wget -r https://www.exemplo.com/
-r ou --recursive: Esta opção permite baixar recursivamente todo o conteúdo de um site, incluindo links internos. Por exemplo:

wget -P /caminho/do/diretorio https://www.exemplo.com/arquivo.txt
-P ou --directory-prefix: Esta opção permite definir um diretório de destino para salvar os arquivos baixados. Por exemplo:

wget -O arquivo.txt https://www.exemplo.com/arquivo.txt
-O ou --output-document: Esta opção permite que você especifique o nome do arquivo de saída para o arquivo que está sendo baixado. Por exemplo:

