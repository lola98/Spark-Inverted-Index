# Spark-Inverted-Index
14848 Cloud Infra hw5


## Setup Steps
1. Pull MML Spark docker container with the command ``docker pull mcr.microsoft.com/mmlspark/release``.

2. Run the docker image ``docker run -it -p 8888:8888 -e ACCEPT_EULA=yes mcr.microsoft.com/mmlspark/release``.

3. In the terminal, enter ``jupyter notebook``, and go to ``localhost:8888`` which runs the notebook. 

4. Upload files in `data` folder as well as the script `inverted_index.ipynb` to the docker container.

5. Run through the script and it will perform inverted index algorithm on the files provided. A sample output can be found in the file `inverted_index.pdf`.

