### pyjwt
---
https://github.com/jpadilla/pyjwt

```py
import jwt
encoded = jwt.encode({'some': 'payload'}, 'secret', algorithm='HS256')
jwt.decode(encoded, 'secret', algorithms=['HS256'])


```

```sh
pip install PyJWT
pyjwt --key=secret decode TOKEN
pyjwt decode --no-verify TOKEN
python setup.py test
```

```
```


