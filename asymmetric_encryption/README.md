# Asymmetric Encryption with OpenSSL

## Introduction
In the digital age, privacy and security are paramount, especially when two people, Bob and Alice, need to exchange sensitive information over an insecure channel (email, chat or similar internet communication channels).

This exercise will take you on a journey where you, the learner, help Alice and Bob securely communicate using asymmetric encryption.

## Running the notebook
To run the notebook, use either:

### Bash script
```bash 
if ! command -v python &> /dev/null
then
    if ! command -v python3 &> /dev/null
    then
        echo "Python could not be found. Please install Python first."
        exit
    fi
fi

if ! command -v poetry &> /dev/null
then
    echo "Poetry could not be found. Please install Poetry first."
    exit
fi

# Run Jupyter notebook
poetry run jupyter notebook asymetric_encrpytion.ipynb
```

### IDE
Open directory [asymmetric_encryption](.) in:
 - [VSCode](https://code.visualstudio.com/)
 - [PyCharm](https://www.jetbrains.com/pycharm/)
 - Or text editor or IDE of your choice that has support for [Jupiter Notebooks](https://jupyter.org/try)