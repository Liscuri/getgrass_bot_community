
# getgrass.io community node bot 🚀

A easy to use non-ui and ui based program to keep grass running by connecting to their server without a extension. This can be used on a VPS or ran locally with or without proxies.

# How to run 📝

Clone the project

```
git clone https://github.com/Liscuri/getgrass_bot_community
```

Install the dependecies
```
pip install -r requirements.txt
```

Follow the instructions below on how to configure

For the proxy version:
```
python proxy.py
```
For the non-proxy version:
```
python no-proxy.py
```
For the ui version:
```
python ui.py
```

# How to configure 🛠️

## Proxies 🌐
If you want to use proxies you can either open the `proxy.py` file and input your proxies in the array on line `71` in the `main()` function.

The proxies should be input like this;
```json
socks5_proxy_list = [
        'socks5://user:pwd@ip:port',
        'socks5://user:pwd@ip:port',
    ]
```

While using the `ui.py` you fill in the `user_id` and your `sock5 proxy`. You can only use one proxy.

## Non proxies 🛜
If you don't want to use proxies open the `no_proxy.py` file and input your user_id on line `68` in the `main()` function.
# Original creator  👨‍💻

The original creator of this project can be found [here](https://github.com/ymmmmmmmm/getgrass_bot).

The original still uses the normal node (1x gain), but this is updated to use the community node (1.25x gain). The URLs inside `ui.py` are still the original. If you want to support him by using his [referral link](https://app.getgrass.io/register/?referralCode=0PhrIR8TAQX6IG4) feel free to.

# Cheap proxies 💸

For cheap static residential socks5 proxies check out [IPRoyal](https://iproyal.com/?r=494893).

<a href="https://iproyal.com/?r=494893" target="_blank">
<img src="https://dashboard.iproyal.com/img/b/728_1.jpg" alt="https://iproyal.com/">
</a>

# Issues 🐛

For any issues feel free to create an issue!
