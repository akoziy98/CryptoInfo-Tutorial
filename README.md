# CryptoInfo-Tutorial
This is tutorial for 1EX API https://rapidapi.com/1ex-1ex-default/api/cryptoinfo/details usage. 

## How to start
- install python 3.10 virtual environment. Follow the next steps. 
Be careful with current conda environments (placed in round brackets).  
```
(base)$ conda create -n py310 python=3.10
(base)$ conda activate py310
(py310)$ python3.10 -m venv .venv
(py310)$ conda deactivate
(base)$ conda deactivate
```
- Add your RapidApi private keys to ```os.environ```. We need to modify activate file:
```
nano .venv/bin/activate
```
And pass at the end of the file your key:
```
export X_RAPIDAPI_KEY=98as9dadjaksd9879qwejkhdad
```
Save and close the file. 

Activate environment:
```
source .venv/bin/activate
```
- install requirements:
```
pip install -r requirements.txt
```
- Run jupyter-notebook server:
```
jupyter-notebook
```
- Go to ```*_tutoral"``` folders in opened jupyter browser page or continue use your IDE to see requests examples. 