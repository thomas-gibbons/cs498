CS498 AUDIO COMPUTING - SP20

ews_install
tjgibbo2@ECEB-2076-08 MINGW64 /u/Desktop/cs498 (master)
$ pip install pipenv
Collecting pipenv
  Downloading https://files.pythonhosted.org/packages/13/b4/3ffa55f77161cff9a5220f162670f7c5eb00df52e00939e203f601b0f579/pipenv-2018.11.26-py3-none-any.whl (5.2MB)
    100% |████████████████████████████████| 5.2MB 6.6MB/s
Collecting virtualenv-clone>=0.2.5 (from pipenv)
  Downloading https://files.pythonhosted.org/packages/ba/f8/50c2b7dbc99e05fce5e5b9d9a31f37c988c99acd4e8dedd720b7b8d4011d/virtualenv_clone-0.5.3-py2.py3-none-any.whl
Requirement already satisfied: pip>=9.0.1 in c:\program files\python37\lib\site-packages (from pipenv) (19.0.3)
Collecting virtualenv (from pipenv)
  Downloading https://files.pythonhosted.org/packages/05/f1/2e07e8ca50e047b9cc9ad56cf4291f4e041fa73207d000a095fe478abf84/virtualenv-16.7.9-py2.py3-none-any.whl (3.4MB)
    100% |████████████████████████████████| 3.4MB 3.3MB/s
Collecting certifi (from pipenv)
  Downloading https://files.pythonhosted.org/packages/b9/63/df50cac98ea0d5b006c55a399c3bf1db9da7b5a24de7890bc9cfd5dd9e99/certifi-2019.11.28-py2.py3-none-any.whl (156kB)
    100% |████████████████████████████████| 163kB 6.6MB/s
Requirement already satisfied: setuptools>=36.2.1 in c:\program files\python37\lib\site-packages (from pipenv) (40.8.0)
Installing collected packages: virtualenv-clone, virtualenv, certifi, pipenv
Could not install packages due to an EnvironmentError: [Errno 13] Permission denied: 'C:\\Program Files\\Python37\\Lib\\site-packages\\clonevirtualenv.py'
Consider using the `--user` option or check the permissions.

You are using pip version 19.0.3, however version 20.0.2 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

tjgibbo2@ECEB-2076-08 MINGW64 /u/Desktop/cs498 (master)
$ pip install pipenv --user
Collecting pipenv
  Using cached https://files.pythonhosted.org/packages/13/b4/3ffa55f77161cff9a5220f162670f7c5eb00df52e00939e203f601b0f579/pipenv-2018.11.26-py3-none-any.whl
Collecting certifi (from pipenv)
  Using cached https://files.pythonhosted.org/packages/b9/63/df50cac98ea0d5b006c55a399c3bf1db9da7b5a24de7890bc9cfd5dd9e99/certifi-2019.11.28-py2.py3-none-any.whl
Collecting virtualenv (from pipenv)
  Using cached https://files.pythonhosted.org/packages/05/f1/2e07e8ca50e047b9cc9ad56cf4291f4e041fa73207d000a095fe478abf84/virtualenv-16.7.9-py2.py3-none-any.whl
Requirement already satisfied: setuptools>=36.2.1 in c:\program files\python37\lib\site-packages (from pipenv) (40.8.0)
Requirement already satisfied: pip>=9.0.1 in c:\program files\python37\lib\site-packages (from pipenv) (19.0.3)
Collecting virtualenv-clone>=0.2.5 (from pipenv)
  Using cached https://files.pythonhosted.org/packages/ba/f8/50c2b7dbc99e05fce5e5b9d9a31f37c988c99acd4e8dedd720b7b8d4011d/virtualenv_clone-0.5.3-py2.py3-none-any.whl
Installing collected packages: certifi, virtualenv, virtualenv-clone, pipenv
  The script virtualenv.exe is installed in 'C:\Users\tjgibbo2\AppData\Roaming\Python\Python37\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  The script virtualenv-clone.exe is installed in 'C:\Users\tjgibbo2\AppData\Roaming\Python\Python37\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  The scripts pipenv-resolver.exe and pipenv.exe are installed in 'C:\Users\tjgibbo2\AppData\Roaming\Python\Python37\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed certifi-2019.11.28 pipenv-2018.11.26 virtualenv-16.7.9 virtualenv-clone-0.5.3
You are using pip version 19.0.3, however version 20.0.2 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

