# ansible
Password change of a user for multiple server at a time.

To change a user password you have to generate encrypted password first.

```python
echo 'import crypt,getpass; print crypt.crypt(getpass.getpass(), "$6$YOURSALT")' | python -
```

