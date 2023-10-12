# Command Line Interface (CLI) Basics

## Navigating

- `echo`: Display a message or variable.
- `cd`: Change the current directory.
  - **Common Use Case Example:** Suppose you are in the `/home/user/documents` directory, and you want to navigate to the `/home/user/downloads` directory:

    ```shell
    cd /home/user/downloads
    ```

- `pwd`: Print the current working directory.
- `ls`: List files and directories in the current directory.

## Managing Files

- `mkdir`: Create a new directory.
- `rm`: Remove files or directories.
  - **Use with Caution:** The `rm` command is used to delete files and directories, but it doesn't ask for confirmation, so use it carefully.
  - `rm -r` or `rm -rf`: Remove directories and their contents recursively.
    - **Warning:** The `rm -rf` command is extremely powerful and should be used with the utmost caution. It forcefully removes directories and their contents without confirmation. Once deleted, the data is usually irrecoverable, so ensure you are targeting the correct files or directories when using this command.
- `cp`: Copy files or directories.
- `touch`: Create an empty file.
- `cat`: Concatenate and display the contents of a file.
- `less`: View the contents of a file page by page.

## Text Editors

- `nano`: A simple terminal text editor.
- `vim`: A powerful terminal text editor.

### Nano

- To save changes and exit:
  - Press `Ctrl` + `O` (hold down the `Ctrl` key and press `O`).
  - It will prompt you to confirm the file name. Press `Enter` to save.
  - Then, press `Ctrl` + `X` to exit.

- To discard changes and exit:
  - Press `Ctrl` + `C` to cancel changes.
  - It will ask if you want to save modified buffers. Type `N` for "No" and press `Enter`.

### Vim

- To save changes and exit:
  - In normal mode, type `:w` and press `Enter`. This saves the file.
  - Then, type `:q` and press `Enter`. This quits Vim.

- To save changes and exit forcefully (if there are unsaved changes):
  - In normal mode, type `:wq` and press `Enter`. This saves and quits Vim.

- To discard changes and exit:
  - In normal mode, type `:q!` and press `Enter`. This quits Vim without saving changes.
