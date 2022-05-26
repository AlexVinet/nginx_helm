# nginx-helm

**nginx-helm** is a repository containing multiple (one for now) helm chart to deploy different nginx server with basic configuration.

Terra Station Wallet extension allows users to:

- View the balances and values of coins and tokens held in the connected wallet.
- View a list of transactions signed by the connected wallet.
- Send tokens to another Terra wallet.
- Swap currencies on the Terra network at the effective exchange rate.

## installing an nginx webServer

Install nginx webServer service with the following commands:

```
git clone https://github.com/AlexVinet/nginx-helm.git
cd nginx-helm/webServer/
helm install webServer -f values.yaml .
```