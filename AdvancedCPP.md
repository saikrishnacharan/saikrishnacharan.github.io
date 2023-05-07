```cpp
// ConstructorBasics.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
using namespace std;

class Shallow{

private:
  int* data;
  size_t size;

public:  
  Shallow(int d);
  Shallow(const Shallow& source);
  void PrintData();
  ~Shallow();
};

Shallow::Shallow(int d) 
{
  cout << "Constructor is called" << endl;
  data = new int;
  *data = d;
  size = d / 10;
}

Shallow::Shallow(const Shallow& source)
  :data{ source.data },size{ source.size }{
  cout << "Copy Constructor is called" << endl;
}

Shallow::~Shallow() {
  cout << "Destructor is called" << endl;
  delete data;
}

void Shallow::PrintData() {
  cout << (*data) << endl;
}

void PrintShallow(Shallow obj) {
  obj.PrintData();
}

int main()
{
  Shallow obj1(10);
  PrintShallow(obj1);
  //Shallow obj2{ obj1 };
  
  return 0;
}
```
