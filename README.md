## Steps I'm following to setup:

1. Cloned both indy-plenum & indy-node.
2. Made a Python virtualenv.
3. Setup Plenum::> cd indy-plenum && python setup.py install   || No Errors
4. Setup Node::> cd indy-node && python setup.py install   || Errors

>> pip freeze
<details>
<summary>Output</summary>

```
base58==2.1.1
Cython==3.0.6
distro==1.8.0
flake8==6.1.0
importlib-metadata==3.10.1
# Editable install with no version control (indy-node==1.13.2rc6)
-e /home/psychopunk_sage/Hyperledger/Indy/.direnv/python-3.9.0/lib/python3.9/site-packages/indy_node-1.13.2rc6-py3.9.egg
indy-plenum==1.13.1rc4
-e git+https://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@github.com/PsychoPunkSage/indy-vdr.git@71c769768a730c34cb98b10ecd00f3cdb11daf74#egg=indy_vdr&subdirectory=wrappers/python
iniconfig==2.0.0
ioflo==2.0.2
jsonpickle==3.0.2
leveldb==0.201
libnacl==1.6.1
mccabe==0.7.0
msgpack-python==0.5.6
orderedset==2.0.3
packaging==23.2
pluggy==1.3.0
portalocker==2.8.2
prompt-toolkit==3.0.39
psutil==5.9.6
pycodestyle==2.11.1
pyflakes==3.1.0
Pympler==0.8
python-dateutil==2.8.2
python-ursa==0.1.1
pyzmq==22.3.0
rlp==0.6.0
semver==2.13.0
sha3==0.2.1
six==1.16.0
sortedcontainers==1.5.7
timeout-decorator==0.5.0
tomli==2.0.1
ujson==1.33
wcwidth==0.2.9
zipp==3.17.0
zmq==0.0.0
```

</details>
