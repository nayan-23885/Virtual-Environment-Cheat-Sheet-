# Virtual-Environment-Cheat-Sheet
This contains commands to operate the Virtual Environment.
<body>
  <h2>Install Virtual Environment</h2>
  <p>
    pip install virtualenv
    <h2>or for Linux</h2>
    sudo apt install python3.10-venv
    <h2>Create Virtual Environment</h2>
    python -m venv venv or &lt;env_name&gt;
    <h2>Create Virtual Environment with system pakages </h2>
    python -m venv venv or &lt;env_name&gt; --system-site-packages
    <h2>Activate Virtual Environment</h2>
    venv\Script\activate.bat (Windows)<br>
    source env/bin/activate (Linux/Mac)
    <h2>List Pachages </h2>
    pip list
    <h2>List Pachages of virtual environment only</h2>
    pip list --local
    <h2>List Pachages with versions</h2>
    pip freeze
    <h2>List Packages with versions of virtual environment only</h2>
    pip freeze --local
    <h2>Export Packages with versions of virtual environment only</h2>
    pip freeze --local > requirements.txt
    <h2>Install packages from the requirements file</h2>
    pip install -r requirements.txt
    <h2>Delete Virtual Environment</h2>
    rmdir /s /q venv (Windows)<br>
    rm -rf venv (Linux/Mac)
  </p>
</body>
