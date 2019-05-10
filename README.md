# nix-cygwin
Building and installing the Nix Package Manager in Cygwin.

## 1
Install Cygwin with wget.

## 2
In Cygwin console execute:
```
wget https://raw.githubusercontent.com/MDeltaX/nix-cygwin/master/nix-install
chmod +x nix-install
./nix-install
```

## WIP issues
Suggestions welcome.
* Binary cache download makes Nix fail silently (workaround: *nix-shell -p hello* **--option substitute false**)
* Using newer Nixpkgs than *18.09* results in *infinite recursion*
