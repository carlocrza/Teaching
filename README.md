starting build for URL: https://github.com/carlocrza/teaching
fetching source at https://github.com/carlocrza/teaching
Step 1 : FROM andrewosh/binder-base:latest
---> 10c75734a0d4
Step 2 : RUN mkdir /home/main/notebooks
---> Running in 5e7004b67bb7
---> e69c3a56a04a
Removing intermediate container 5e7004b67bb7
Step 3 : RUN chown main:main /home/main/notebooks
---> Running in bcfb94fe708e
[91m[TrustNotebookApp] Writing notebook-signing key to /home/main/.local/share/jupyter/notebook_secret[0m
Signing notebook: /home/main/notebooks/first_notebook.ipynb
---> 241a2854b093
Removing intermediate container 230947ca9eb9
Step 10 : USER main
---> Running in 39c6ae70799e
---> d35c62992cbc
Removing intermediate container 39c6ae70799e
Step 11 : WORKDIR $HOME/notebooks
---> Running in 43b08a541272
---> df76d18fa59e
Removing intermediate container 43b08a541272
Successfully built df76d18fa59e
registering template for carlocrza-teaching
