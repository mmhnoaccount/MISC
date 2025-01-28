pip install pywebview

pip install --upgrade pyinstaller==5.0
注意：一定要这个版本，版本低了需要crypto（但crypto不支持高版本python），版本高了不兼容cefpython3

如运行exe报一下错误（可能）：
Invalid file descriptor to ICU data received
则到以下地址下载hook-cefpython3.py文件，并放入D:\anaconda3\Lib\site-packages\PyInstaller\hooks文件夹中，然后重新生成exe：
https://github.com/cztomczak/cefpython/tree/master/examples/pyinstaller

