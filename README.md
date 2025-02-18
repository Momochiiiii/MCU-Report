# ບົດທີ 1: Program

### 1. Git Bash:
### 2. Arduino IDE
### 3. Visual Studio Code
### 4. Obsidian
### 5. Fritzing

# ບົດທີ 2: Experiment Blink

### 1. ຈຸດປະສົງຂອງການທົດລອງ :

ໃນບົດນີ້ຈະເຮັດກ່ຽວກັບການເປີດ-ປິດດອກໄຟ ຫຼື ເອີ້ນວ່າ: LED Blink. ໂດຍໃຊ້ອາດຸຍໂນ(Arduino) ເປັນຕົວຄວບຄຸມການເຮັດວຽກຂອງດອກໄຟ(LED). ການເຮັດວຽກຂອງມັນແມ່ນ ດອກໄຟ(LED) ຈະເປີດ-ປິດ ຕາມເວລາທີ່ຕັ້ງໄວ້, ໂດຍLED ຈະຖືກຕັ້ງຄ່າໃຫ້ສະຫວ່າງເປັນເວລາ 1ວິ ແລະ ດັບເປັນເວລາ 1ວິ.

### 1. ອຸປະກອນ :

ວົງຈອນນີ້ໃຊ້ອຸປະກອນ 5 ຢ່າງເຊັ່ນ:

- Arduino UNO R3 (1)
- Green LED (1)
- Resistor 220Ω (1)
- Breadboard (1)
- Jumper wires (2)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### 1. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad

- ກຽມດອກໄຟ(LED) ມາໜຶ່ງດອກ(ຂາດອກໄຟຈະມີ 2 ຂາຄື: ຂາຂ້າງຍາວເປັນຂາບວກ ຫຼື Anode,​ ຂາຂ້າງສັ້ນເປັນຂາລົບ ຫຼື Cathode)
- ກຽມຄວາມຕ້ານ(Resistor) ມາໜຶ່ງອັນ ຂະຫນາດ220ໂອມ(Ω)
- ຕໍ່ຂາບວກ(+) ຂອງດອກໄຟເຂົ້າກັບຄວາມຕ້ານທານ ແລະ ປາຍອີກດ້ານຂອງຕົວຕ້ານທານ ຕໍ່ເຂົ້າກັບພິນທີ13(Pin13) ຂອງArduino.
- ຂາລົບ(-) ຂອງດອກໄຟຕໍ່ເຂົ້າກັບຂາດິນ(GND) ຂອງບອດArduino.

( Link Tinkercad )

- ອັບໂຫຼດໂຄດ(Code) ເພື່ອຄວບຄຸມການກະພິບ(Blink) ຂອງດອກໄຟ.
- Run Code & Output:

ເມື່ອໂຄດ(Code) ຖືກກວດສອບແລ້ວວ່າຖືກຕ້ອງ, ມັນກໍຈະຖືກອັບໂຫຼດໄປທີ່ບອດ Arduino. ຈາກນັ້ນດອກໄຟກໍຈະກະພິບຕາມຊ່ວງເວລາທີ່ເຮົາກຳນົດໄວ້ໃນໂຄດ(Code).

- ໄຟຈະເປີດເປັນເວລາໜຶ່ງວິນາທີ(1s)
- ໄຟຈະເປີດເປັນເວລາໜຶ່ງວິນາທີ(1s)
- ມັນຈະເຮັດວຽກວົນຫຼູບໄປເລື້ອຍໆ ເພາະຟັງຊັນ loop()ໃນ Arduinoຖືກອອກແບບໃຫ້ເຮັດວຽກແບບຊໍ້າໆ ດັ່ງນັ້ນ, ດອກໄຟຈະເປີດ-ປິດ ສະຫຼັບກັນໄປທຸກໆໜຶ່ງວິນາທີ(1s).

### 1. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ(Classroom Experiment) :
### 2. ກະກຽມອຸປະກອນ: Arduino(1), Breadboard(1), LED(1), Resistor(1), Jumpers(2), USB TypeB(1).

### 1. Upload Code ລົງArduino IDE :

- ອະທິບາຍໂຄດ(Code)
- ຟັງຊັນ setup() ຈະຖືກເອີ້ນໃຊ້ພຽງຄັ້ງດຽວເມື່ອເລີ່ມຕົ້ນໂປຣແກຣມ. ໃນຟັງຊັນນີ້, pinMode(LED_BUILIN, OUTPUT) ຈະຕັ້ງຄ່າໃຫ້ຂາ13 (ເຊິ່ງເປັນທີ່ຢູ່ຂອງLEDເທິງArduino) ເຮັດວຽກເປັນຂາອອກ.
- ຟັງຊັນ loop() ຈະເຮັດວຽກວົນໄປເລື້ອຍໆຕະຫຼອດເວລາ.
- digitalWrite(LED_BUILTIN, HIGH) ເຮັດໃຫ້LED ຮຸ່ງ(ໃຫ້ໄຟຟ້າອອກທີ່ຂາ13).
- digitalWrite(LED_BUILTIN, LOW) ເຮັດໃຫ້LED ດັບ(ບໍ່ໃຫ້ໄຟຟ້າອອກທີ່ຂາ13).
- delay(1000) ລໍຖ້າເປັນເວລາ 1000ມິນລີວິນາທີ = 1ວິນາທີ.

1. ຕໍ່ວົງຈອນຕົວຈິງ :

- ເຊື່ອມຕໍ່ບອດArduino ກັບ ຄອມພິວເຕີຂອງຕົນເອງ ແລະ ຄົ້ນຫາຊື່ບອດທີ່ໃຊ້ໃນ Arduino IDE. ກວດເຊັກເບິ່ງໂຄດວ່າຖືກຕ້ອງແລ້ວບໍ່. ຫຼັງຈາກເຊື່ອມໄດ້ແລ້ວກໍ Run Code.

ຮູບຕອນໄຟປິດ

ຮູບຕອນໄຟເປີດ

Output: ດອກໄຟຈະກະພິບຕາມຊ່ວງເວລາທີ່ເຮົາກຳນົດໄວ້ໃນໂຄດ ເປີດ1ວິນາທີ ແລະ ປິດ1ວິນາທີ.ວົນຫຼູບໄປເລື້ອຍໆ

# ບົດທີ 3: Switch

### I. ຈຸດປະສົງຂອງການທົດລອງ:

ໃນບົດນີ້ຈະເຮັດກ່ຽວກັບການທົດສອບການເຮັດວຽກຂອງສະວິດ (Push Button) ແລະ ດອກໄຟທີ່ມີຢູ່ໃນບອດ Arduino (Built-in LED) ໂດຍໃຊ້ອາດຸຍໂນ (Arduino) ເປັນຕົວຄວບຄຸມ.

### II. ອຸປະກອນ:

ວົງຈອນນີ້ໃຊ້ອຸປະກອນ 5 ຢ່າງເຊັ່ນ:

- Arduino UNO R3 (1)
- Push Button (1)
- Resistor 10kΩ (1)
- Breadboard (1)
- Jumper wires (3)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

\- ເມື່ອເຮົາບໍ່ໄດ້ກົດປຸ່ມ Button Serial Monitor ຈະສະແດງຄຳວ່າ Button Low ແລະເມື່ອເຮົາກົດປຸ່ມຄ້າງໄວ້ຈະສະແດງຄຳວ່າ Button High

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

2\. Upload Code ລົງ Arduino IDE:

3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່
- ທົດສອບການເຮັດວຽກຂອງສະວິດແລະເບິ່ງການເປີດ-ປິດຂອງດອກໄຟ Built-in LED

# ບົດທີ 4: LED RGB

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ການສຶກສາວິທີການຄວບຄຸມດອກໄຟ LED RGB ຜ່ານ Serial Monitor ຂອງ Arduino IDE ໂດຍໃຊ້ຄຳສັ່ງຈາກຜູ້ໃຊ້ ເພື່ອປ່ຽນສີແລະຄວບຄຸມສະຫວ່າງ.

- ວິທີການເຮັດວຽກ:
- ເມື່ອເປີດ Serial Monitor ແລ້ວ, ຜູ້ໃຊ້ສາມາດປ້ອນຄຳສັ່ງລົງໄປໃນຊ່ອງປ້ອນຂໍ້ມູນ.
- Arduino ຈະຮັບຄຳສັ່ງ ແລະປ່ຽນສະພາບຂອງ LED RGB ຕາມຄຳສັ່ງທີ່ໄດ້ປ້ອນ.
- ໃນກໍລະນີທີ່ຄຳສັ່ງບໍ່ຖືກຕ້ອງ, LED ຈະບໍ່ປ່ຽນສະພາບ ແລະຄວາມສະຫວ່າງຂອງມັນຈະຄົງຄ້າງ.
- ຖ້າປ້ອນ "off", LED ທັງຫມົດຈະປິດໃນທັນທີ.
- ຖ້າປ້ອນ "rgb" ຫຼື "on", LED RGB ຈະເປີດທັງ 3 ສີພ້ອມກັນ.
- ຖ້າປ້ອນ "r", "g", ຫຼື "b", LED ຈະເປີດສີທີ່ກຳນົດ.

### 1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno
- LED RGB (Cathode ລວມ)
- Resistor 220 Ω (3 ອັນ)
- Breadboard
- Jumper Wires

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

( Link Tinkercad )

- ວົງຈອນປົກກະຕິຂອງເຮົາ
- ເມື່ອເຮົາປ້ອນ “R” ສີຂອງດອກໄຟຈະປ່ຽນເປັນສີແດງ
- ເມື່ອເຮົາປ້ອນ “G” ສີຂອງດອກໄຟຈະປ່ຽນເປັນສີຂຽວ
- ເມື່ອເຮົາປ້ອນ “B” ສີຂອງດອກໄຟຈະປ່ຽນເປັນສີຟ້າ

1. ຂັ້ນຕອນການທົດລອງ:
2. ຕໍ່ວົງຈອນ LED RGB ກັບ Arduino:
    - Red (R) -> Pin 11
    - Green (G) -> Pin 10
    - Blue (B) -> Pin 9
    - Cathode -> GND
3. ເປີດ Serial Monitor ແລະປ້ອນຄຳສັ່ງ:
    - "r" ສຳລັບສີແດງ
    - "g" ສຳລັບສີຂຽວ
    - "b" ສຳລັບສີນ້ຳເງິນ
    - "rgb" ເພື່ອເປີດທຸກສີ
    - "off" ເພື່ອປິດທຸກສີ

# V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

### 1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

### 2\. Upload Code ລົງ Arduino IDE:

### 3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 5: Buzzer

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ການສຶກສາວິທີການຄວບຄຸມ buzzer ປະເພດ passive ແລະ active ຜ່ານ Arduino ໂດຍການສ້າງເພງຈາກຄວາມຖີ່ທີ່ກຳນົດໄວ້ ໃຫ້ມີຄວາມຄື່ນແລະລຳດັບໂດຍການໃຊ້ຄຳສັ່ງ tone().

- ວິທີການເຮັດວຽກ:
- ຄຳສັ່ງ tone() ຖືກໃຊ້ໃນການກຳນົດຄວາມຖີ່ຂອງ buzzer ໃຫ້ສ້າງສຽງຕາມໂນ໊ດຂອງໂປຣແກຣມ.
- Passive buzzer ຈະຕ້ອງການຄວາມຖີ່ທີ່ກຳນົດໄວ້ຜ່ານ tone(), ໃນຂະນະທີ Active buzzer ມີແຫຼ່ງຄວາມຖີ່ໃນຕົວ.
- ໂປຣແກຣມຈະສົ່ງໂນ໊ດທີ່ກຳນົດຂອງໂທນເພື່ອສ້າງເພງຕາມລຳດັບຂອງ melody.

### 1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno (1)
- Passive Buzzer (1)
- Active Buzzer (1)
- Jumper Wires
- Breadboard (1)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ

ຄຳອະທິບາຍໂຄດ:

- ກຳນົດຄ່າຄວາມຖີ່ຂອງໂນ໊ດທີ່ໃຊ້ສ້າງເພງ.
- ໃນ loop() ໂປຣແກຣມຈະສົ່ງໂນ໊ດຕາມລຳດັບໃຫ້ buzzer ຂັບສຽງອອກມາ.
- ຄຳສັ່ງ noTone() ຖືກໃຊ້ເພື່ອຢຸດສຽງລະຫວ່າງໂນ໊ດ.
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

( Link Tinkercad)

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

### 1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

1. Upload Code ລົງ Arduino IDE:

### 3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 6: Mood Indicator Project

### I. ຈຸດປະສົງຂອງການທົດລອງ:

ໃນບົດນີ້ຈະເຮັດກ່ຽວກັບການທົດນຳໃຊ້ອຸປະກອນທັງຫມົດເພື່ອມາສ້າງໂປຣເຈັກຂອງຕົວເອງເຊິ່ງໂປຣເຈັກຂອງເຮົາແມ່ນ ກ່ຽວກັບການນຳໃຊ້ Buzzer ແລະ LED ເພື່ອບົ່ງບອກອາລົມຂອງເຮົາຜ່ານສຽງເພງທີ່ຕ່າງກັນໄປ.

### II. ອຸປະກອນ:

ວົງຈອນນີ້ໃຊ້ອຸປະກອນ 7 ຢ່າງເຊັ່ນ:

- Arduino UNO R3 (1)
- Push Button (1)
- Resistor 10kΩ (1)
- Breadboard (1)
- Jumper wires
- LED (2)
- LED RGB (1 )

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

\- ເມື່ອເຮົາກົດປຸ່ມ Button LED RGB ຂອງເຮົາກໍ່ຈະປ່ຽນເປັນສີຂຽວ, ເພງຈາກ Buzzer ກໍ່ຈະດັງຂຶ້ນ ແລະ LED ດ້ານຊ້າຍມືກໍ່ຈະເປີດ

\- ເມື່ອເຮົາກົດປຸ່ມ Button ອີກຮອບ LED RGB ຂອງເຮົາກໍ່ຈະປ່ຽນເປັນສີຟ້າ, ເພງຈາກ Buzzer ກໍ່ຈະດັງຂຶ້ນ ແລະ LED ດ້ານຂວາມືກໍ່ຈະເປີດ.

\- ເມື່ອເຮົາກົດປຸ່ມ Button ອີກຮອບ LED RGB ຂອງເຮົາກໍ່ຈະປ່ຽນເປັນສີແດງ, ເພງຈາກ Buzzer ກໍ່ຈະດັງຂຶ້ນ ແລະ LED ທັງສອງດ້ານກໍ່ຈະປີດ.
### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

### 1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

### 2\. Upload Code ລົງ Arduino IDE:

### 3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 7: Relay

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ການສຶກສາວິທີການຄວບຄຸມການເປີດ-ປິດໄຟ LED ໂດຍນຳໃຊ້ Relay ຜ່ານ Arduino UNO.

### 1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno (1)
- LED (2)
- Relay (1)
- Breadboard (1)
- Jumper Wires
- Resistor

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

( link Tinkercad )

### 1. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

1. Upload Code ລົງ Arduino IDE:
2. . ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 8: Potentiometer

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ທົດລອງການນໍາ potentiometer ມາຄວບຄຸມຄ່າຄວາມສະຫວ່າງຂອງ LED ຜ່ານ Arduino UNO.

### 1. ອຸປະກອນທີ່ໃຊ້

- Arduino UNO R3 (1)
- Green LED (1)
- Resistor 220Ω (1)
- Breadboard (1)
- Jumper wires (2)
- Potentiometer (1)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

\- ເມື່ອເຮົາຫມຸນ Potentiometer ດອກໄຟ LED ຈະເປີດ

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

2\. Upload Code ລົງ Arduino IDE:

3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່
- ວິທີການຕໍ່ວົງຈອນ

1\. ຕໍ່ potentiometer ຂາເຂົ້າກາງໄປທີ່ A0 ຂອງ Arduino, ແລະ ຂາທີ່ເຫຼືອຕໍ່ໄປຫາ 5V ແລະ GND.

2\. ຕໍ່ LED ຂື້ນກັບຂາທີ່ 11 ຂອງ Arduino, ຜ່ານຕວັນຕ້ານ 220Ω ໄປຫາ GND.

ການເຮັດວຽກຂອງໂຄດ

1\. ໂຄດນີ້ເລີ່ມຕົ້ນໂດຍກຳນົດປ່ຽນແປງ analogValue ແລະ ledValue ເພື່ອໃຊ້ເກັບຄ່າ.

2\. ໃນ setup() ຂອງ Arduino, Serial Monitor ຖືກເປີດໃນຄວາມໄວ 9600 bps ເພື່ອສົ່ງຂໍ້ມູນຄ່າທີ່ອ່ານໄດ້ ແລະ ຂາ 11 ຖືກກຳນົດໃຫ້ເປັນຂາອອກ.

3\. ໃນ loop(), ໂຄດຈະອ່ານຄ່າຈາກ potentiometer ຜ່ານ analogRead(A0) ແລະ ສົ່ງຄ່ານີ້ໄປທີ່ Serial Monitor.

4\. ຄ່ານີ້ຖືກແປງໃຫ້ຢູ່ໃນຊ່ວງ 0-255 ດ້ວຍ map() ເພື່ອປ່ຽນໄລເດີຂອງ LED.

5\. analogWrite(11, ledValue) ໃຊ້ຄ່ານີ້ເພື່ອຄວບຄຸມຄວາມສະຫວ່າງ LED.

# ບົດທີ 9: Servo Motor

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ໃນບົດນີ້ຈະເຮັດກ່ຽວກັບການຄວບຄຸມເຊີໂວມໍເຕີ (Servo Motor) ໂດຍໃຊ້ຕົວຕ້ານທານປ່ຽນຄ່າໄດ້ (Potentiometer). ການເຮັດວຽກຂອງມັນແມ່ນ ເຊີໂວມໍເຕີຈະໝູນໄປຕາມຄ່າທີ່ອ່ານໄດ້ຈາກຕົວຕ້ານທານປ່ຽນຄ່າໄດ້, ໂດຍຈະປ່ຽນຄ່າຈາກ 0-1023 ໄປເປັນ 0-180 ອົງສາ.

- ເຮົາສາມາດໃຊ້ການຕໍ່ວົງຈອນນີ້ເພື່ອຮຽນຮູ້ການຄວບຄຸມເຊີໂວມໍເຕີ ແລະ ການອ່ານຄ່າແບບອະນາລັອກຈາກຕົວຕ້ານທານປ່ຽນຄ່າໄດ້. ນອກຈາກນີ້ຍັງໄດ້ຮຽນຮູ້ການແປງຄ່າໂດຍໃຊ້ຟັງຊັນ map() ແລະ ການສື່ສານແບບ Serial.

1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno
- Servo Motor
- Potentiometer
- Jumper Wires
- Breadboard

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

### 1\. ການຕໍ່ວົງຈອນ

- ຕໍ່ເຊີໂວມໍເຕີເຂົ້າກັບ Pin 9 ຂອງ Arduino
- ຕໍ່ຕົວຕ້ານທານປ່ຽນຄ່າໄດ້ເຂົ້າກັບ Pin A0
- ຕໍ່ສາຍໄຟບວກ (+5V) ແລະ ສາຍດິນ (GND) ໃຫ້ກັບອຸປະກອນທັງສອງ

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

2\. Upload Code ລົງ Arduino IDE:

3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 10: Seven Segment Display

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ການສຶກສາການໃຊ້ Seven Segment Display ກັບ Arduino ໂດຍການສະແດງຕົວເລກ 0-9 ແບບນັບຂຶ້ນແລະນັບລົງ ຜ່ານຄຳສັ່ງ digitalWrite().

- ວິທີການເຮັດວຽກ:
- Seven Segment Display ປະກອບດ້ວຍ 8 LED ສ່ວນ (A-H) ທີ່ໃຊ້ໃນການສະແດງຕົວເລກ.
- ຄຳສັ່ງ digitalWrite() ຖືກໃຊ້ເພື່ອຄວບຄຸມສະພາບ HIGH ຫຼື LOW ຂອງຂາສັງກັດໃນ Arduino.
- ໃນຄຳສັ່ງ loop(), ຂັ້ນຕອນການຄວບຄຸມຈະເຮັດວຽກໃນການນັບ 0-9 ແລ້ວຈຶ່ງນັບກັບຄືນ.

1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno
- Seven Segment Display (Common Cathode)
- Resistors 220 Ω
- Jumper Wires
- Breadboard

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

### 1\. ການຕໍ່ວົງຈອນ

- ຕໍ່ຂາ A ຂອງ 7-Segment ເຂົ້າກັບ Pin 13 ຜ່ານ Resistor
- ຕໍ່ຂາ B ຂອງ 7-Segment ເຂົ້າກັບ Pin 12 ຜ່ານ Resistor
- ຕໍ່ຂາ C ຂອງ 7-Segment ເຂົ້າກັບ Pin 11 ຜ່ານ Resistor
- ຕໍ່ຂາ D ຂອງ 7-Segment ເຂົ້າກັບ Pin 10 ຜ່ານ Resistor
- ຕໍ່ຂາ E ຂອງ 7-Segment ເຂົ້າກັບ Pin 9 ຜ່ານ Resistor
- ຕໍ່ຂາ F ຂອງ 7-Segment ເຂົ້າກັບ Pin 8 ຜ່ານ Resistor
- ຕໍ່ຂາ G ຂອງ 7-Segment ເຂົ້າກັບ Pin 7 ຜ່ານ Resistor
- ຕໍ່ຂາ H (DP) ຂອງ 7-Segment ເຂົ້າກັບ Pin 6 ຜ່ານ Resistor
- ຕໍ່ຂາ Common ເຂົ້າກັບ GND

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

\- ເມື່ອເຮົາ start simulate ແລ້ວໂຕເລກກໍ່ຈະເລີ່ມນັບຂຶ້ນຈາກ 0-9 ແລະຖອຍຫຼັງຈາກ 9-0.

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

2\. Upload Code ລົງ Arduino IDE:

3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່

# ບົດທີ 11: Temperature - Based Ventilation System

### 1. ຈຸດປະສົງຂອງການທົດລອງ:

ໂປຣເຈັກຈຳລອງການເຮັດວຽກຂອງລະບົບລະບາຍອາກາດຕາມອຸນຫະພູມໂດຍການໃຊ້ອຸປະກອນທັງໝົດທີ່ເຮົາເຄີຍຮຽນມາ.

- ວິທີການເຮັດວຽກ:
- ໝຸນ Potentiometer ເພື່ອເລືອກອຸນຫະພູມທີ່ຕ້ອງການ
- ຫຼັງຈາກນັ້ນ Arduino ຈະອ່ານຄ່າແລະປ່ຽນຄ່າແຮງດັນໄຟຟ້າເປັນຄ່າດິຈິຕອນ (0-1023)
- ເຊິ່ງຄ່າແຮງດັນໄຟຟ້າທີ່ເຮົາອ່ານໄດ້ຈະປ່ຽນເປັນອຸນຫະພູມທີ່ເຮົາຕັ້ງໄວ້ເຊິ່ງຈະຢູ່ໃນຊ່ວງ 0-9
- ແລ້ວສະແດງຄ່າອຸນຫະພູມທີ່ຕັ້ງໄວ້ເທິງໜ້າຈໍ Seven-Segment
- ຫຼັງຈາກນັ້ນເຊີໂວຈະໝຸນເພື່ອເປີດຫຼືປິດຊ່ອງລະບາຍອາກາດ
- ລີເລເປີດຫຼືປິດໄຟເມື່ອເຊີໂວໝຸນຄົບຮອບທີ່ກຳນົດ

### 1. ອຸປະກອນທີ່ໃຊ້:

- Arduino Uno
- Seven Segment Display (Common Cathode)
- Resistors 220 Ω
- Jumper Wires
- Breadboard
- Servo Motor
- Button
- Relay Module
- Potentiometer

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR4XmP4//8/AwAI/AL+GwXmLwAAAABJRU5ErkJggg==)

### III. ສ້າງວົງຈອນທົດລອງໃນ Tinkercad:

- ກຽມອຸປະກອນທັງໝົດມາວາງໃສ່ພື້ນທີ່ເຮັດວຽກ
- ຕໍ່ວົງຈອນຕາມແຜນຜັງທີ່ກຳນົດ

( Link Tinkercad )

- ຂຽນໂຄດຄວບຄຸມການເຮັດວຽກ
- ທົດສອບການເຮັດວຽກຂອງວົງຈອນ

### V. ທົດລອງຕໍ່ຕົວຈິງໃນຫ້ອງ (Classroom Experiment):

### 1\. ກະກຽມອຸປະກອນ:

- ກວດສອບອຸປະກອນທຸກຢ່າງໃຫ້ຄົບຖ້ວນ
- ກວດສອບການເຮັດວຽກຂອງອຸປະກອນແຕ່ລະຊິ້ນ

### 2\. Upload Code ລົງ Arduino IDE:

### 3\. ຕໍ່ວົງຈອນຕົວຈິງ:

- ຕໍ່ວົງຈອນຕາມແຜນຜັງ
- ກວດສອບການເຊື່ອມຕໍ່
