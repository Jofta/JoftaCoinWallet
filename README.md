This is GUI Wallet for experimental cryptocurrency JoftaCoin (JFT).

## Building JoftaCoinWallet

### On *nix

**1. Clone wallet sources**

```
git clone https://github.com/Jofta/JoftaCoinWallet.git
```

**2. Create git submodule:**

```
cd JoftaCoinWallet

git submodule add https://github.com/Jofta/JoftaCoin.git cryptonote
```

**4. Build**

```
mkdir build && cd build && cmake .. && make
```

### On Windows
Dependencies:
* Microsoft Visual Studio Community 2017
* cmake-3.11.1
* Qt 5.9.5
* boost 1.67.0


Good luck!
