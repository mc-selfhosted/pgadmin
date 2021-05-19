# pgadmin

## setup

- copy and adjust .env file:

```bash
cp .env.template .env
vi .env
```

- after first run, to 'fix' permission issue stop service and run

```bash
sudo chown a+rwx ./data
```

