# ansible
Password change of a user for multiple server at a time.

To change a user password you have to generate encrypted password first.

```python
echo 'import crypt,getpass; print crypt.crypt(getpass.getpass(), "$6$YOURSALT")' | python -
```

You will get something as like below
$6$YOURSALT$Z.WZd6YP7WNq2IFPZdBFmZcqKWMUQqN2wNchgc/M/gJHTex8DoA1xSKT5mAkhlxPc8.JBoL/mqQvoRJipta.A.

Replace this key with your.
