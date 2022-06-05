使用LSB-Steganography将info.txt（含学号 姓名）隐藏到颜色里
python3 LSBSteg.py encode -i input.png -o test.png -f info.txt
可以用指令查看被隐藏信息
python3 LSBSteg.py decode -i test.png -o info2.txt
附LSBSteg.py文件