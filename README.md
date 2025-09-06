# Virtual-Environment-Cheat-Sheet
This contains commands to operate virtual environment.
<body>
  <h2>Install Virtual Environment</h2>
  <p>
    pip install virtualenv
    <h3>or for Linux</h3>
    sudo apt install python3.10-venv
    <h3>Create Virtual Environment</h3>
    python -m venv venv or &lt;env_name&gt;
    <h3>Create Virtual Environment with system pakages </h3>
    python -m venv venv or &lt;env_name&gt; --system-site-packages
    <h3>Activate Virtual Environment</h3>
    venv\Script\activate.bat (Windows)<br>
    source env/bin/activate (Linux)
    <h3>List Pachages </h3>
    pip list
    <h3>List Pachages of virtual environment only</h3>
    pip list --local
    <h3>List Pachages with versions</h3>
    pip freeze
    <h3>List Packages with versions of virtual environment only</h3>
    pip freeze --local
    <h3>Export Packages with versions of virtual environment only</h3>
    pip freeze --local > requirements.txt
    <h3>Install packages from the requirements file</h3>
    pip install -r requirements.txt
  </p>
</body>
