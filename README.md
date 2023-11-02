My personal kmonad config.

Run:
sudo kmonad ~/dev/KmonadConfig/kmonad.kbd -l debug

Install:
Follow instructions here: https://github.com/kmonad/kmonad/issues/334 using dext 2.1.0 https://github.com/kmonad/kmonad/pull/716

Recompile:
stack --system-ghc --compiler ghc-9.6.2 install --flag kmonad:dext --extra-include-dirs=c_src/mac/Karabiner-DriverKit-VirtualHIDDevice/include/pqrs/karabiner/driverkit:c_src/mac/Karabiner-DriverKit-VirtualHIDDevice/src/Client/vendor/include