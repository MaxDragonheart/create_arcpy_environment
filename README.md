# create_arcpy_environment

1- Installare ArcGIS Pro

2- Installare Conda o Miniconda

3- Avviare 'Anaconda Prompt', quindi digitare 'where conda' in modo da elencare le directory principali di Conda o Miniconda

4- Cercare le 'System environment variables', si aprirà la finestra che segue, in cui bisognerà cliccare su 'Environment Variables'.

5- Nella nuova finestra editare i 'Path' in modo da aggiungere le directory al punto 3

6- Avviare come amministratore il prompt di Windows e verificare la versione di conda digitando 'conda --version'. Se si sono seguiti correttamente i passaggi precedenti verrà mostrata la versione di Conda e quindi sarà possibile procedere con i passi successivi.

7- Creare l'ambiente conda eseguendo dal prompt avviato al passo 6 'conda create --name *nome_ambiente* python=*versione_python*'. La versione di Python da scegliere deve essere quella compatibile con la versione di ArcGIS Pro installata. Per ArcGIS Pro 3.4 la versione di Python è 3.11. A comando lanciato seguire le indicazioni, quindi attivare l'ambiente usando 'conda activate *nome_ambiente*'.

8- Ora è possibile installare ArcPy e la libreria ArcGIS per Python usando il comando 'conda install -c esri arcpy arcgis'.

