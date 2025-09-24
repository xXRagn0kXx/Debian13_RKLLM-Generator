# Debian13_RKLLM-Generator

1. descargar RKLLM
2.
```bash
git clone https://github.com/airockchip/rknn-llm.git
cd rknn-llm
```

3. descargar miniconda
```bash
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

3 Añadir miniconda al path

```bash
echo 'export PATH="$HOME/miniconda3/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

4 Crear entorno conda

conda create -n rkllm-conversor python=3.12

5 Activar  entorno conda
```bash
conda init 
```
Cerramos y entreamos de nuevo a la terminal 
```bash
conda activate rkllm-conversor
```
pasara de 
(base) davisito@RKNN-Generator:~$ conda activate rkllm-conversor
a
(rkllm-conversor) davisito@RKNN-Generator:~$

6 Instalar RKLLM-Toolkit

Necsitamos torch
sin cuda:
```bash
pip install torch 
```

con cuda:
```bash
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

RKLLM-Toolkit es un kit de desarrollo de software que permite a los usuarios cuantificar y convertir modelos LLM con formato Huggingface en PC X86.
```bash
 pip3 install rkllm-toolkit/rkllm_toolkit-1.2.1-cp312-cp312-linux_x86_64.whl
```

