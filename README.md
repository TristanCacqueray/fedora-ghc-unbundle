# ghc-time-manager (for ghc-http2)

```
# rpmlint ~/rpmbuild/RPMS/x86_64/ghc-time-manager-*
sh: /usr/bin/python: No such file or directory
ghc-time-manager.x86_64: W: spelling-error Summary(en_US) Scalable -> Salable, Callable, Calculable
ghc-time-manager.x86_64: W: spelling-error %description -l en_US Scalable -> Salable, Callable, Calculable
ghc-time-manager.x86_64: E: library-not-linked-against-libc /usr/lib64/libHStime-manager-0.0.0-13VNl63DGne4Q77KbSs6r9-ghc8.6.5.so
ghc-time-manager.x86_64: W: no-documentation
ghc-time-manager-devel.x86_64: W: no-documentation
ghc-time-manager-prof.x86_64: W: no-documentation
ghc-time-manager-prof.x86_64: W: devel-file-in-non-devel-package /usr/lib64/ghc-8.6.5/time-manager-0.0.0/libHStime-manager-0.0.0-13VNl63DGne4Q77KbSs6r9_p.a
3 packages and 0 specfiles checked; 1 errors, 6 warnings.
```
