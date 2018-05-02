# setup develop environemnt
```
$ pipenv shell --three
$ pipenv install --dev
```

# How to use
```
class Node(NodeBase):
    key = Column(Key, String())
    value = Column(String())

tree = Tree(Node,)

```