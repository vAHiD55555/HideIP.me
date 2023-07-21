### NOTE⛔

This proxy list is collected from the list of proxies available on the Internet. They are only displayed in this repository for easy access. I am not responsible for proxies.


### Donate

- BTC - 1KbXEYvGY4oURR7HCBvCMfhbyEcU3jM8mL
- [Other Coins](https://nowpayments.io/donation/hideip)
- Payeer - P1072424404
- [МИР / ЮMoney](https://yoomoney.ru/to/410014392099996)

#### HTTPS proxy example

###### Running Curl on Linux
```console
curl --proxy-insecure -k --proxy 'https://xxx.xxx.xxx.xxx:xxxx' -o - https://api.my-ip.io/ip
```

###### Running Chrome browser on windows with clean profile
```console
"C:\Program Files\Google\Chrome\Application\chrome.exe" --ignore-certificate-errors --ignore-ssl-errorsrs --proxy-server="https://xxx.xxx.xxx.xxx:xxxx" --user-data-dir="%TEMP%\chrprofile1" "https://ip-api.com/"
```

#### CONNECT proxy example

###### Running Curl on Linux
```console
curl --proxytunnel -k --proxy 'http://xxx.xxx.xxx.xxx:xxxx' -o - https://api.my-ip.io/ip
```

