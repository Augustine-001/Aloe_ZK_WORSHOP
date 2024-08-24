# leo-testnet

The bootcamp was created on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust.

## Workshop 1

Transaction ID:at1507u5pe42v7q56mjzpdl7gfkhmu8acwg6fyfamfsalg9na888gyslatcwr

### Steps
1. Install rust on your pc
2. clone the leo repo from their official github page
3. `cd leo`
4. `cargo install --path .` to install the dependencies
5. `leo new todolist`
6. Note: the name of your project must be in lowercase
7. `cd todolist`
8. change the PRIVATE_KEY in your .env file to yours
9. `leo run`
10. `leo deploy`

![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(64).png?raw=true)


## Workshop 2

Transaction ID: at1al3psj6t07lfduvse6rx6yfz5t29men8rm59f5u8h9pldn8gt5rq0qh802

### Steps
1. Install rust on your pc
2. clone the leo repo from their official github page
3. `cd leo`
4. `cargo install --path .` to install the dependencies
5. `leo new newproject`
6. Note: the name of your project must be in lowercase
7. `cd newproject`
8. change the PRIVATE_KEY in your .env file to yours
9. `leo run mint yourwalletaddress 1000u64 --network testnet`
10. `leo run transfer "token" youraddress 100u64 --network testnet`
11. `leo deploy`

![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(65).png?raw=true)
![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(66).png?raw=true)


