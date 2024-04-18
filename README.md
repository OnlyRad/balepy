# balepy

<p align=center>
<img src="https://s8.uupload.ir/files/balethon_uvi2_esnh.png" style="width: 300px; height: 300px;" align=center alt="background">
</p>
<h3 align="center"> balepy a Library Python for create bot API in bale application <br> <h5 align=center> <a href="https://balepy.github.io"> Docs</a> | <a href="https://t.me/TheLinuxGP">Community</a> | <a href="https://t.me/TheCommit">Telegram Channel</a> | <a href="https://github.com/OnlyRad">Owner</a></h5></h3>


## Install and Update:
```bash
pip install -U balepy
```

## START:
```python
from bale import Client
from asyncio import run


__token = 'your-token-here'
client = Client(__token, timeout=10)

async def main():
    async for message in client.on_message():
        await message.reply('hello __from__ **balepy**')


if __name__ == '__main__':
    run(main())
```


## Thanks To:
### <a href="https://github.com/metect">AmirAli</a>

<h3>Thanks to all those who contributed directly or indirectly to the development of the module</h3>
