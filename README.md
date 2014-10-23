# send2kindle

dump url using w3m and send to kindle

`~/.send2kindle.toml`

```toml
from = "account@mail.com"
kindle = "yourname@kindle.com"

[smtp]

host = "smtp.mail.com"
port = 25
account = "account"
password = "password"
```

usage

```sh
send2kindle http://mosaicscience.com/story/man-golden-blood
```

