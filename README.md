# Du an Thuc hanh Embedded C & Git Workflow

Kho luu tru thuc hanh quy trinh quan ly ma nguon chuyen nghiep (Branching, Pull Request, Code Review) ket hop cau truc du an lap trinh C/Vi dieu khien.

## Cau truc thu muc
- `main.c`: Chuong trinh chinh dieu khien luong xu ly.
- `uart.c`: Driver khoi tao va giao tiep chuan UART.
- `sensor.c`: Module doc va hieu chinh du lieu cam bien nhiet do.

## Huong dan bien dich (Build)
Su dung trinh bien dich `gcc` tren moi truong Linux / Git Bash:

    gcc main.c uart.c sensor.c -o build/app.exe
    ./build/app.exe

## Tac gia
- **Ha Xuan Bach** - GitHub: [@Xuanbach06112005](https://github.com/Xuanbach06112005)
