# Deep Code Search

## Keras Version

To implement the Keras version of deep code search. The instructions needs to be followed:

1. Create and activate a virtual environment.

``` 
python3 -m venv deep-CS
cd deep-CS/
. bin/activate
```
2. Clone this repo.

```
git clone https://github.com/monalisha31/deep-code-search-1.git
cd keras
```
3. Install the required packages

```
pip install --upgrade pip
pip install -r requirements.txt
```
4. Train the model.

```
python main.py --mode train
```

5. set ```reload``` in configs.py to 0.

6. Run the repr_code.

```
python main.py --mode repr_code
```

7. Test the code.

```
python main.py --mode search
```



https://user-images.githubusercontent.com/42024284/130725352-26c1c103-ce9c-4cf4-b3fc-a1796062a9b4.mp4










