Having python already installed we need to create a virtual space to work there

in your cmd type
python -m venv |NAME|                  (whitout the | )

e.g.
python -m venv uteq

After that we need to enter into our virtual space with
|NAME|\Scripts\activate,bat

e.g.
uteq\Scripts\activate.bat

Then we need to update our Pip repository with
Pip freeze

And install Jupyter notebook
Pip install notebook


And finally open Jupyter with
jupyter notebook
