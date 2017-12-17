**1. Clone wallet sources**

```
git clone https://github.com/nidscom/minercoinwallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../MinerCoin MinerCoin
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/nidscom/minercoinwallet.git MinerCoin
```

Replace URL with git remote repository of your coin.

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
