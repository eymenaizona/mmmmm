### Setup Instructions

1. Connect to the server via SSH:
    ```bash
    ssh <user>@<server-ip>
    ```

2. Navigate to the `aizona_trade_engine` repository and copy `setup_server.sh`.

3. Open `setup_server.sh` for editing:
    ```bash
    vi setup_server.sh
    ```

4. After editing, make the script executable:
    ```bash
    chmod +x setup_server.sh
    ```

5. Run the script:
    ```bash
    sudo ./setup_server.sh
    ```

6. Then, copy the `prep_env.sh` file from the `aizona_trade_engine` repository.

7. Open `prep_env.sh` for editing:
    ```bash
    vi prep_env.sh
    ```

8. Make the script executable:
    ```bash
    chmod +x prep_env.sh
    ```

9. Finally, run the `prep_env.sh` script:
    ```bash
    sudo bash ./prep_env.sh
    ```
