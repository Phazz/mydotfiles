Setup laptop and install dotfiles
=================================

1. Clone the repo
    ```sh
    git clone https://github.com/Phazz/mydotfiles.git
    ```

2. Cd the folder
    ```
    cd mydotfiles
    ```

3. Run the alias script
    ```
    ./alias.sh
    ```

4. Run the thoughbot laptop script
    ```sh
    curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
    less mac
    sh mac 2>&1 | tee ~/laptop.log
    ```

5. Enjoy a fresh and completely configured laptop
