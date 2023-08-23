# Usage

1. Install Pyenv by running:

      ```sh
      brew install pyenv
      ```

2. Installing pyenv should add another plugin by the name python-build. Confirm by running:

    ```sh
    ls /usr/local/bin | grep python-build
    ```

3. Run the following to install Python 2.7.18 system wide:

    ```sh
    sudo python-build 2.7.18 /usr/local/
    ```

4. Confirm if the python executable in `/usr/local/` is the correct version by running:

    ```sh
    /usr/local/bin/python --version
    ```

5. Tap the formula repo containing v8 by running:

    ```sh
    brew tap pol905/v8/v8_py2@3.15
    ```

6. Run the following command to install v8@3.15

    ```sh
    brew install v8_py2@3.15
    ```

7. Create a symlink by running:

    ```sh
    brew link --force v8_py2@3.15
    ```
