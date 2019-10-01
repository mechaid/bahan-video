# TIPS: Mengatasi Error Pkg Install Di Termux Untuk Android Versi 7 Keatas

1. Uninstall Termux, dan install kembali Termux
2. Masuk ke Termux biarkan dia update dulu dengan sendirinya
3. copy paste script dibawah ini ke Termux lalu tekan enter :
```
rm $PREFIX/etc/apt/sources.list && echo "deb https://termux.net stable main" >> $PREFIX/etc/apt/sources.list && apt-get update
```
4. copy paste script dibawah ini ke Termux lalu tekan enter :
```
echo "export LD_LIBRARY_PATH=/data/data/com.termux/files/usr/lib" >> ~/.bashrc && . ~/.bashrc
```
5. pkg install python
