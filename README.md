## Meowwww🐱

### WELCOME TO... MEEEEEEE

> So, I am doingggg nothing... and you shouldn't be here if u want to get a job🙂

```cpp
#include <cstdio>
#include <string>

#define GFX_CYAN "\033[36m"
#define GFX_GREEN "\033[32m"
#define GFX_MAGENTA "\033[35m"
#define GFX_BOLD "\033[1m"
#define GFX_DIM "\033[2m"
#define GFX_RED "\033[31m"
#define RESET "\033[0m"

using namespace std;
const char *hex_map = "0123456789ABCDEF";

string GenerateHexAddress(){
  static random_device rd;
  static mt19937 gen(rd());
  static uniform_int_distribution<> dis(0, 65535);

  stringstream ss;
  ss << "0x" << uppercase << setfill('0') << setw(4) << hex << dis(gen);
  return ss.str();
}

int main(){
  string systemBase = generateHexAddress();

  cin.tie(NULL);
  cout << GFX_DIM << "\n ACCESSING KERNEL MODULES..." << RESET << endl;
  this_thread::sleep_for(std::chrono::milliseconds(600));


  printf("This might seem like an aesthetic README because of this code, but dont fool urself! Now, gooo!!");
}
```
