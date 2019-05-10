# nix-cygwin
Building and installing the **Nix Package Manager** in **Cygwin**.

## 1
Install **Cygwin** with **wget**.

## 2
In **Cygwin console** execute:
```
wget https://raw.githubusercontent.com/MDeltaX/nix-cygwin/master/nix-install
chmod +x nix-install
./nix-install
```

## WIP issues
**Suggestions welcome!**
* [Binary cache downloads make Nix fail silently](https://github.com/MDeltaX/nix-cygwin/issues/1) (workaround: *nix-shell -p hello* **--option substitute false**)
* [Using newer Nixpkgs than **18.09** results in *infinite recursion*](https://github.com/MDeltaX/nix-cygwin/issues/2)
