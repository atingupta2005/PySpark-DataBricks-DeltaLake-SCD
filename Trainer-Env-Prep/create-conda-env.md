# Create Conda Environment
- Install Miniconda
- Create Conda Environment
```
conda env list
conda create -n --prefix ./conda-env python=3.9
conda env list
conda activate ./conda-env
```
- Install Packages
```
conda install -y pandas
conda install -y jupyterlab
conda install -y openjdk
conda install -y pyspark
conda install -y -c conda-forge findspark
```

- Export environment
```
conda env export --from-history > environment.yml
```

- Create env from file
```
conda env create -f environment.yml
```

## Install Spark locally on Windows 10
- Refer: https://phoenixnap.com/kb/install-spark-on-windows-10
- Install OpenJDK 11 or above
- Install Python

- Open PowerShell and Install
```
mkdir c:\Spark
cd c:\Spark
Invoke-WebRequest https://dlcdn.apache.org/spark/spark-3.2.1/spark-3.2.1-bin-hadoop3.2.tgz -OutFile spark-3.2.1-bin-hadoop3.2.tgz
Invoke-WebRequest https://github.com/cdarlint/winutils/raw/master/hadoop-3.2.2/bin/winutils.exe -OutFile winutils.exe
Invoke-WebRequest https://github.com/cdarlint/winutils/raw/master/hadoop-3.2.2/bin/hadoop.dll -OutFile hadoop.dll
```

- Extract
```
tar -xvfz spark-3.2.1-bin-hadoop3.2.tgz
```

- Add Paths
```
SETX /M SPARK_HOME "C:\Spark\spark-3.2.1-bin-hadoop3.2"
PATH=%PATH%;%SPARK_HOME%\bin
Get-ChildItem -Path Env:\SPARK_HOME
Get-ChildItem -Path Env:\PATH
```

- Open CMD and Copy winutils
```
move  winutils.exe spark-3.2.1-bin-hadoop3.2\bin
move  hadoop.dll spark-3.2.1-bin-hadoop3.2\bin
```

- Launch Spark
```
spark-shell
```

- Start Jupyter Hub
```
D:
cd D:\22-Trngs\2-Confirmed\5-PySpark-56-hours-Geet
conda activate ./conda-env
cd D:\22-Trngs\2-Confirmed\5-PySpark-56-hours-Geet\GH\Labs
python -m jupyterlab
```
