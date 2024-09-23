## Configuration

1. **Create a `config.json` file**

    The `config.json` file should be in the root directory of the project. Here is a sample configuration:

    ```json
    {
    "use_proxy": false,
    "auto_upgrade_skill": false,
    "auto_complete_task": false,
    "auto_open_box": false,
    "auto_open_box_max_price": 7000,
    "auto_buy_item": false,
    "auto_buy_item_max_price": 6000,
    "account_delay": 5,
    "countdown_loop": 3800
    }


    ```
    - `use_proxy`: enable or disable the proxy usage
    - `auto_upgrade_skill`: enable or disable the automatic upgrade skill
    - `auto_complete_task`: enable or disable the automatic do tasks
    - `auto_open_box`: enable or disable the automatic open box feature
    - `auto_open_box_max_price`: set a maximum price for the open cyber box
    - `auto_buy_item`: enable or disable the automatic purchase of items feature
    - `auto_buy_item_max_price`: set a maximum price for the item to be purchased
    - `account_delay`: Delay between processing each account (in seconds).
    - `countdown_loop`: how long is the waiting time to return to the first account

2. **Create a `proxies.txt` file**

    The `proxies.txt` file should be in the root directory and contain a list of proxies in the format `username:password@host:port`.

    Example:

    ```
    user1:pass1@ip1:port1
    user2:pass2@ip2:port2
    ```

3. **Create a `data.txt` file**

    The `data.txt` file should be in the root directory and contain one account per line.

    Example:

    ```
    query1
    query2
    ```