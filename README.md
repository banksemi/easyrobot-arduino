# easyrobot-arduino
이지로봇 아두이노 라이브러리 모음

### How to use:
1. Copy to arduino library folder.

2. Add a header file to your code.
#include "Easyrobot.h"

3. declare Easyrobot class and call update() on loop.
Easyrobot MainProcess;

void loop() {
  MainProcess.Update();
}

