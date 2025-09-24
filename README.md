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

6 Descargar RKLLM



