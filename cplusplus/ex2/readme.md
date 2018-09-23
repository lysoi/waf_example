# Static lib and dynamic lib.

To build the project

```bash
chmod 777 waf.py
./waf.py configure
./waf.py
cd build
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:.
./app
```