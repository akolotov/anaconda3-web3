Anaconda3 with python Ethereum libraries
====

## Information

This repo provides docker environment to run Jupyther notebooks in the Anaconda environment where the following set of libraries instaled additionally:
 * [py_ecc](https://github.com/ethereum/py_ecc)
 * [web3](https://github.com/ethereum/web3.py)
 * [ethereum](https://github.com/ethereum/pyethereum)

## Run Jupyther notebook

Use `docker-compose up` to run the Jupyther notebook. The container will occupy the port `8888` for the application.

Check the console to see the token to connect the the notebook and use it in the URL `http://127.0.0.1:8888/?token=<TOKEN>`.
