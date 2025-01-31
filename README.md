### Installation

All Python packages needed are listed in [requirements.txt](requirements.txt). You can install them with the following commands:

    sudo apt install python3.12-venv (if not installed already)
    sudo apt install texlive (if not installed already)
    cd llm-email-spam-detection
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

if you are using windows don’t forget to also install the pywin32 package using this :
after:
pip install pywin32

### Usage

All source code used to generate the results and figures in the paper are in the `src` folder. The data used in this paper is automatically downloaded, processed, and stored in the `data` folder.

You can start training the 6 baseline ML techniques and fine tuning of the 3 large language models with the following command:

    python main.py
