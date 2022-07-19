# listmonk 
[Bastille](https://github.com/bastillebsd/bastille) template for running [listmonk](https://listmonk.app) server in a FreeBSD jail


## Bootstrap

```shell
bastille bootstrap https://github.com/ddowse/listmonk-template
```

## Usage

```shell
bastille template TARGET ddowse/listmonk-template
```

Please have a look at the **Bastillefile** for any options and arguments that you could use.   
For instance you might want to change listmonks password.   

The block to get a SSL/TLS certificate as well as the nginx block are commented out.   
Change the arguments ```FQDN``` to your domain and remove the leading ```#``` from the lines. 
