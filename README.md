# iPython Jupyter Notebook: Uploading a Folder

1. Make sure the folder is still in .zip format
2. Upload the .zip file to your Jupyter Notebook directory (not home path)
> My zip file is named `PYNQ_Workshop-master.zip` and was uploaded my `/home/xilinx/jupyter_notebooks` directory.
3. Now that the .zip file is uploaded, we want to unzip it. So, in Jupyter Notebook, open a new **terminal session**, and run <br>
```! unzip /home/xilinx/jupyter_notebooks/PYNQ_Workshop-master.zip -d /home/xilinx/jupyter_notebooks```

Note: The above instructions are a quick and dirty method, under the assumption that: you are uploading the same-named file to the same-named directory path and that Jupyter Notebook is being ran locally on the ZYNQ board. For *Session_1* (Lab One), this should be the case.
<br>
<br>
<br>

#### General Instructions:
1. Make sure the folder is still in .zip format
2. Upload the .zip file to your Jupyter Notebook (assuming home path directory)
3. Now that the .zip file is uploaded, we want to unzip it. So, in Jupyter Notebook, open a new **terminal session**, and run <br> `! unzip ~/yourfolder.zip -d ~/`
---
where:

`!` specifies a Unix/OS command

`unzip` is the unzipping command

`~/yourfolder.zip` tells the command where your .zip folder is currently at. <br>`~/` assumes the .zip is stored in the home path of the directory. For paths other than home, remove the `~`

`-d ~/` specifies where you want to put the unzipped folder. It currently assumes you want to put it in the home path of the directory. For paths other than home, remove the `~`


<p style="text-align: center;">Made with ♥ from Muhammad Elarbi</p>
<p style="text-align: center;">elarbi.m@northeastern.edu</p>
