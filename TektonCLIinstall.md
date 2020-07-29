# Install Tekton CLI Tool

## Instruction

1. Download tar file

    ```
    curl -LO https://github.com/tektoncd/cli/releases/download/v0.11.0/tkn_0.11.0_Linux_x86_64.tar.gz
    ```

1. Extract `tkn` to your PATH (e.g. /usr/local/bin)

    ```
    sudo tar xvzf tkn_0.11.0_Linux_x86_64.tar.gz -C /usr/local/bin/ tkn
    ```

1. Verify 

    ```
    tkn version
    ```
    
Additional Tekton installation instructions can be found at https://github.com/tektoncd/cli.
