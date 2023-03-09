int main()
{
 int b = 50;
 int *a = &b;   //в указатель записи а записали адрес прежней b
 cout << "adress \t *a\t b\n";
 cout << a << "\t" << *a << "\t" << b << endl;
 b += 10;
 
 cout << a << "\t" << *a << "\t" << b << endl;
 *a = 100;
 cout << a << "\t" << *a << "\t" << b << endl;
 
 
    return 0;
}



adress   *a      b
0x7ffc6f19029c  50      50
0x7ffc6f19029c  60      60
0x7ffc6f19029c  100     100
